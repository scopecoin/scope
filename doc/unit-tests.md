Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the scoped tests manually, launch `src/test/test_scope`.

To add more scoped tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the scope-qt tests manually, launch `src/qt/test/test_scope-qt`

To add more scope-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
