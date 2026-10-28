# find_lowest_number automated tests

This repository contains `find_lowest_number.py`, three input/expected-output test pairs in `test_data/`, and a GitHub Actions workflow.

The workflow runs on every `push` event. Each test runs the Python application and uses `diff -u` to compare the generated output file with its expected output.

Test cases:
1. Ten numbers — expects `-12.0`
2. One number — expects `42.0`
3. Blank input — expects `No numbers found in file`
Automated workflow verification.
