# Loan Qualifier Application

This is a command line application to match applicants with qualifying loans.

---

## Technologies

Describe the technologies required to use your project such as programming languages, libraries, frameworks, and operating systems. Be sure to include the specific versions of any critical dependencies that you have used in the stable version of your project.

The project is implemented by Python and expected to work on Linux, Windows and MacOS.

---

## Installation Guide

This project depends on Fire and Quetionary to build CLI, the following is the way to install them.
pip install fire questionary

---

## Usage

python ./app.py
? Enter a file path to a rate-sheet (.csv): ./data/daily_rate_sheet.csv
? What's your credit score? 740
? What's your current amount of monthly debt? 1000
? What's your total monthly income? 10000
? What's your desired loan amount? 3000
? What's your home value? 100000
The monthly debt to income ratio is 0.10
The loan to value ratio is 0.03.
Found 14 qualifying loans
? Are you sure to save the qualifying loans? Yes
? Enter a file path to a save the qualifying loans (.csv): ./test.csv

---

## Contributors

bevingo@gmail.com

---

## License

Copyright (c) 2022 Wenge Zhang

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
