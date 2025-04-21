# Checkmark
A unittest support for AOS 3.2+ development.
This is a foretaste of an upcoming tool.

## Object
Helping developpers to easily write unit tests to check functionnalities and non-regression of their developments.

## Files
Checkmark includes a lone header file, <checkmark/test.h> which offers macros to build test suites.

## Operating principle

* a main source defines the main() function, which will run each test suite through the CHECKMARK_RUN_SUITE() macro, e.g.

