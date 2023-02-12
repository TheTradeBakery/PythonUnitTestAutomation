Chapter 3 Examples from Python Unit Test Automation (unittest)

Examples:
* test_module01.py - basic unittest example 
* test_module02.py - shows order of test execution is alphabetical
* test_module05.py - demonstrates test fixtures
* __init__.py - lists all testing module to create a test package


Notes:
* Run test case with the following command: `python3 test_module01.py -v` (-v is for verbose if `__name__ == "__main__"` is calling `unittest.main()`)
* Alternatively, can run test cases with the following command: `python3 -m unittest test_model05 -v`
* Can run test package/suite with `python3 -m unittest discover
* 
