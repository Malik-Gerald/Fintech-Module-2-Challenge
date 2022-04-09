# Project Title

This project solves the problem of needing to pick out my own clothes on any given occassion. It is a command line interface and written in python. 
---

## Technologies

This project leverages Python 3.9.7 ((default, Sep 16 2021, 16:59:28) [MSC v.1916 64 bit (AMD64)] :: Anaconda, Inc. on win32) with the following packages:
 
* [fire](https://github.com/google/python-fire) - For the command line interface, help page, and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs


---

## Installation Guide

Before running the application first install the following dependencies.

```python
  pip install sys
  pip install fire
  pip install questionary
  from pathlib import Path
```

---

## Usage

To use the clothes picker application simply clone the repository and run the **app.py** 

Upon launching the loans_qualifier_app you will need to enter in the following data for a return value:
? Enter a file path to a rate-sheet (.csv): ../loan_qualifier_app/data/daily_rate_sheet.csv
? What's your credit score?
? What's your current amount of monthly debt?
? What's your total monthly income?
? What's your desired loan amount?
? What's your home value?
? Would you like to save the qualifying loans? (Y/n)

---

## Contributors

Gerald Cortright and Berkeley FIntech teaching materials
---

## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
