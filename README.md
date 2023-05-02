Download Link: https://assignmentchef.com/product/solved-comp9044-test-8-print-your-median-argument
<br>
Write a Perl program median_number.pl that given positive integers as command line arguments prints the median (middle) value.

Your program can assume is given an odd number of arguments. Your program can assume all its arguments are positive integers.

For example:

$ <strong>./median_number.pl 1 333 42</strong>

42

$ <strong>./median_number.pl 3 4 2 1 7 6 5</strong>

4

$ <strong>./median_number.pl 15 15 8 11 8</strong>

11

$ <strong>./median_number.pl 42 42 244 244 42</strong> 42

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest median_number</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test08_median_number median_number.pl</strong>

Write a Shell program, ls_identical.sh which takes the pathnames of 2 directories as argument.

It should print in alphabetical order the names of all files which occur in both directories and have exactly the same contents.

Files must have the same name in both directories and the same contents for their name to be printed.

Do not print the names of files with same contents but different names in both directories.

For example:

$ <strong>ls_identical.1.sh directory1 directory2</strong>

You can assume file names do not start with ‘.’.

Your answer must be Shell. You can not use other languages such as Perl, Python or C.

No error checking is necessary.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest shell_ls_identical</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test08_shell_ls_identical ls_identical.sh</strong>

Write a Perl program, ls_identical.pl which takes the pathnames of 2 directories as argument.

It should print in alphabetical order the names of all files which occur in both directories and have exactly the same contents.

Files must have the same name in both directories and the same contents for their name to be printed.

Do not print the names of files with same contents but different names in both directories.

For example:

<table width="961">

 <tbody>

  <tr>

   <td width="961">$ <strong>mkdir directory1 directory2</strong>$ <strong>echo hello &gt;directory1/same.txt</strong>$ <strong>echo hello &gt;directory2/same.txt</strong>$ <strong>echo hello &gt;directory1/different.txt</strong>$ <strong>echo world &gt;directory2/different.txt</strong>$ <strong>echo hello &gt;directory1/one.txt</strong>$ <strong>echo hello &gt;directory2/two.txt</strong> $ <strong>touch directory1/empty.txt directory2/empty.txt</strong>$ <strong>ls directory1</strong> different.txt empty.txt one.txt same.txt $ <strong>ls directory2</strong> different.txt empty.txt same.txt two.txt$ <strong>ls_identical.pl directory1 directory2</strong> empty.txt same.txt</td>

  </tr>

 </tbody>

</table>

You can assume file names do not start with ‘.’.

Your answer must be Perl only. You can not use other languages such as Shell, Python or C.

You may not run external programs, e.g. via system or backquotes. for example, you can’t run diff.

You may use any Perl module installed on CSE systems.

No error checking is necessary.

When you think your program is working you can autotest to run some simple automated tests:

$ <strong>2041 autotest perl_ls_identical</strong>

When you are finished working on this exercise you must submit your work by running give:

$ <strong>give cs2041 test08_perl_ls_identical ls_identical.pl</strong>