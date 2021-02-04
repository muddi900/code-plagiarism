# Code Plagiarism Analysis

## 1. Collaboration rules

### 1.1. Code style

- C++ google style ([guide](https://google.github.io/styleguide/cppguide.html))

- Python PEP8 style ([guide](https://www.python.org/dev/peps/pep-0008/))

### 1.2. Taskboard

- Trello [invite](https://trello.com/invite/b/sovrr5dJ/afd614ed4dc319c14986e1792b53d896/identifying-plagiarism-in-source-code)

## 2. Install requirements

- pip install -r ./requirements.txt

- python version 3.6+ or even 3.8+

## 3. Tests

- Testing for C/C++ analyzer
  > Test of canalyze.py functions
  ```
    $ python3 test/cplag/test_canalyze.py
  ```

  > Flag `-v` for more testing information
  ```
    $ python3 test/cplag/test_canalyze.py -v
  ```
- Testing for python analyzer
  > Test of pyanalyze.py functions
  ```
    $ python3 test/pyplag/test_pyanalyze.py
  ```

  > Flag `-v` for more testing information
  ```
    $ python3 test/pyplag/test_pyanalyze.py -v
  ```

## 4. Work with analyzers

- python analyzer
  ```
    $ python3 src/pyplag <path/to/folder/with/py/files>
  ```
- C++/C analyzer
  ```
    $ python3 src/cplag/canalyze.py <path/to/folder/with/cpp/or/cc/files>
  ```
