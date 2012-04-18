autotest2junit
--------------

Autoconf Autotest `testsuite.log` to JUnit `testsuite.xml` converter.

Creates `JUnit <http://junit.org/>`_ xml files from
`Autoconf Autotest <http://www.gnu.org/software/autoconf/manual/autoconf.html#Using-Autotest>`_
framework output files to be used in Jenkins CI.

Tool parses `testsuite.log` and outputs `testsuite.xml` file.

Usage
======

Run the script in the directory where your `testsuite.log` is stored, this creates
`testsuite.xml` in the same directory.

