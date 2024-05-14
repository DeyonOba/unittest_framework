# unittest_framework

**Documentation**: https://docs.python.org/3/library/unittest.html

Unittest includes some important concepts from object oriented programming in Python.

### Test Fixture

A test fixture involves the preparation needed to perform one or more tests, and any associated cleanup actions. This may involve, for example, creating temporary or proxy databases, directories, or starting a server process.

### Test Case

A test case is the individual unit of testing. It checks for a specific responses to a particular set of inputs. Unittest provides a base class, **TestCases**, which may be used to create new test cases.

### Test Suite

A test suite is a collection of test cases, test suites, or both. It is used to aggregate test that should be executed together.

### Test Runner

A test runner is a component which orchestrates the execution of tests and provides the outcome to the user. The runner can use a GUI, or textual interface, or return a special value to indicate the results of executing the tests.
