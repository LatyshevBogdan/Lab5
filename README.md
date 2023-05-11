# Lab5
Не проходит тест "test_Transaction.cpp", Изменяем 39 строчку в Transaction.cpp:
```
bool success = Debit(to, sum + fee_); --> bool success = Debit(from, sum + fee_);
```
[![Coverage Status](https://coveralls.io/repos/github/LatyshevBogdan/Lab5/badge.svg?branch=master)](https://coveralls.io/github/LatyshevBogdan/Lab5?branch=master)
