Archive of test results collected by [cl-test-grid](https://github.com/cl-test-grid/cl-test-grid).

The .lisp files in this repository store the data structure documented
in the [test-grid-data](https://github.com/cl-test-grid/cl-test-grid/tree/master/data) module.
The results are split into several files in order to obey the
[github file size limit] (https://help.github.com/articles/working-with-large-files).

To read the archive use `test-grid-data:read-archive` function, it joins all the files
into a single DB structure.