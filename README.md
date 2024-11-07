# devops-demo
# calc.py

def add(a, b):
    return a + b

def subtract(a, b):
    return a - b
# test_calc.py
from calc import add, subtract

def test_add():
    assert add(2, 3) == 5

def test_subtract():
    assert subtract(5, 3) == 2
