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

The `setUp()` and `tearDown()` methods allow you to define instruction that will be executed before and after each test method.

- [Further Reading](https://docs.python.org/3/library/unittest.html#organizing-tests)

**Commonly used assert methods**

|Method|Check that|
|:--|:--|
|`assertEqual(a, b)`| `a==b`|
|`assertNotEqual(a, b)`| `a!=b`|
|`assertTrue(x)`| `bool(x) is True`|
|`assertFalse(x)`| `bool(x) is False`|
|`assertIs(a, b)`| `a is b`|
|`assertIsNot(a, b)`| `a is not b`|
|`assertIsNone(x)`| `x is None`|
|`assertIsNotNone(x)`| `x is not None`|
|`assertIn(a, b)`| `a in b`|
|`assertNotIn(a, b)`| `a not in b`|
|`assertIsInstance(a, b)`| `isinstance(a, b)`|
|`assertNotIsInstance(a, b)`| `not is instance(a, b)`|
