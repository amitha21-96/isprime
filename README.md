# iMyproject1
Steps to test is prime or not using pytest (internet connection required) on Pycharm terminal
1. pip - h
2. pip install virtualenv
3. virtualenv isprime (create directory)
4. cd isprime
5. cd Scripts
6. activate
7. pip install pytest
8. create 2 files inside isprime directory- isprime.py (for coding) & test_isprime.py (for testing)
9. run the files in terminal by typing any :a) pytest
			           	   b) pytest -q test_isprime.py

Test report 
(primes) D:\PYCHARM\pythonProject1\primes>pytest
======================================================================= test session starts =======================================================================
platform win32 -- Python 3.8.8, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: D:\PYCHARM\pythonProject1\primes
collected 1 item                                                                                                                                                   

test_primes.py F                                                                                                                                             [100%]

============================================================================ FAILURES =============================================================================
______________________________________________________________________ test_prime_low_number ______________________________________________________________________

    def test_prime_low_number():
>       assert isprime(1) == False
E       NameError: name 'isprime' is not defined

test_primes.py:2: NameError
===================================================================== short test summary info =====================================================================
FAILED test_primes.py::test_prime_low_number - NameError: name 'isprime' is not defined
======================================================================== 1 failed in 1.27s ========================================================================

(primes) D:\PYCHARM\pythonProject1\primes>pytest
======================================================================= test session starts =======================================================================
platform win32 -- Python 3.8.8, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: D:\PYCHARM\pythonProject1\primes
collected 1 item                                                                                                                                                   

test_primes.py F                                                                                                                                             [100%]

============================================================================ FAILURES =============================================================================
_____________________________________________________________________ test_prime_prime_number _____________________________________________________________________

    def test_prime_prime_number():
>       assert isprime(29)
E       NameError: name 'isprime' is not defined

test_primes.py:7: NameError
===================================================================== short test summary info =====================================================================
FAILED test_primes.py::test_prime_prime_number - NameError: name 'isprime' is not defined
======================================================================== 1 failed in 1.31s ========================================================================

(primes) D:\PYCHARM\pythonProject1\primes>pytest
======================================================================= test session starts =======================================================================
platform win32 -- Python 3.8.8, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: D:\PYCHARM\pythonProject1\primes
collected 1 item                                                                                                                                                   

test_primes.py F                                                                                                                                             [100%]

============================================================================ FAILURES =============================================================================
______________________________________________________________________ test_prime_low_number ______________________________________________________________________

    def test_prime_low_number():
>       assert isprime(15) == False
E       NameError: name 'isprime' is not defined

test_primes.py:11: NameError
===================================================================== short test summary info =====================================================================
FAILED test_primes.py::test_prime_low_number - NameError: name 'isprime' is not defined
======================================================================== 1 failed in 1.31s ========================================================================

(primes) D:\PYCHARM\pythonProject1\primes>pytest
======================================================================= test session starts =======================================================================
platform win32 -- Python 3.8.8, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: D:\PYCHARM\pythonProject1\primes
collected 1 item                                                                                                                                                   

test_primes.py F                                                                                                                                             [100%]

============================================================================ FAILURES =============================================================================
______________________________________________________________________ test_prime_low_number ______________________________________________________________________

    def test_prime_low_number():
>       assert isprime(25) == False
E       NameError: name 'isprime' is not defined

test_primes.py:14: NameError
===================================================================== short test summary info =====================================================================
FAILED test_primes.py::test_prime_low_number - NameError: name 'isprime' is not defined
======================================================================== 1 failed in 1.49s ========================================================================

======================================================================= test session starts =======================================================================
platform win32 -- Python 3.8.8, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: D:\PYCHARM\pythonProject1\primes
collected 1 item                                                                                                                                                   

test_primes.py F                                                                                                                                             [100%]

============================================================================ FAILURES =============================================================================
______________________________________________________________________ test_prime_low_number ______________________________________________________________________

    def test_prime_low_number():
>       from primes.primes import isprime
E       ModuleNotFoundError: No module named 'primes.primes'; 'primes' is not a package

test_primes.py:15: ModuleNotFoundError
===================================================================== short test summary info =====================================================================
FAILED test_primes.py::test_prime_low_number - ModuleNotFoundError: No module named 'primes.primes'; 'primes' is not a package
======================================================================== 1 failed in 1.23s ========================================================================

(primes) D:\PYCHARM\pythonProject1\primes>pytest
======================================================================= test session starts =======================================================================
platform win32 -- Python 3.8.8, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: D:\PYCHARM\pythonProject1\primes
collected 1 item                                                                                                                                                   

test_primes.py F                                                                                                                                             [100%]

============================================================================ FAILURES =============================================================================
______________________________________________________________________ test_prime_low_number ______________________________________________________________________

    def test_prime_low_number():
>       assert isprime(25) == 5
E       assert 26 == 5
E        +  where 26 = isprime(25)

test_primes.py:22: AssertionError
===================================================================== short test summary info =====================================================================
FAILED test_primes.py::test_prime_low_number - assert 26 == 5
======================================================================== 1 failed in 1.26s ========================================================================

(primes) D:\PYCHARM\pythonProject1\primes>pytest
======================================================================= test session starts =======================================================================
platform win32 -- Python 3.8.8, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: D:\PYCHARM\pythonProject1\primes
collected 0 items                                                                                                                                                  

====================================================================== no tests ran in 1.24s ======================================================================

======================================================================= test session starts =======================================================================
platform win32 -- Python 3.8.8, pytest-6.2.4, py-1.10.0, pluggy-0.13.1
rootdir: D:\PYCHARM\pythonProject1\primes
collected 2 items                                                                                                                                                  

test_primes.py FF                                                                                                                                            [100%]

============================================================================ FAILURES =============================================================================
_________________________________________________________________ TestClassDemoInstance.test_one __________________________________________________________________

self = <test_primes.TestClassDemoInstance object at 0x00000281E0700250>

    def test_one(self):
>       assert 0
E       assert 0

test_primes.py:34: AssertionError
_________________________________________________________________ TestClassDemoInstance.test_two __________________________________________________________________

self = <test_primes.TestClassDemoInstance object at 0x00000281E07000D0>

    def test_two(self):
>       assert 0
E       assert 0

test_primes.py:37: AssertionError
===================================================================== short test summary info =====================================================================
FAILED test_primes.py::TestClassDemoInstance::test_one - assert 0
FAILED test_primes.py::TestClassDemoInstance::test_two - assert 0
======================================================================== 2 failed in 1.27s ========================================================================

import math
def isprime(n):
    if n%2 == 0 or n%3 == 0 or n%5==0:
        return False
    for i in range(7, math.floor(math.sqrt(n)), 2):
        if n%i == 0:
            return False
    return True

from primes import isprime
def test_isprime():
     assert isprime(23)==True


