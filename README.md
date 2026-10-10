# Python for Data Science

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Level](https://img.shields.io/badge/Level-Beginner-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

**A complete, runnable Python-fundamentals course in a single Jupyter notebook** — clear explanations, tables, code you can run and edit, exercises, and answers. It builds the foundation that every data-science library (NumPy, pandas, Matplotlib, scikit-learn) is built on.

> Start from zero: install Python, learn the language step by step, and finish by building a small quiz application.

---

## Table of contents

- [What's inside](#whats-inside)
- [Who this is for](#who-this-is-for)
- [Quick start](#quick-start)
- [How to use the notebook](#how-to-use-the-notebook)
- [Module outline](#module-outline)
- [Repository structure](#repository-structure)
- [Where to go next](#where-to-go-next)
- [License and credits](#license-and-credits)

---

## What's inside

Everything lives in one file: [`Python_for_Data_Science.ipynb`](Python_for_Data_Science.ipynb).

| # | Module | What you learn |
|---|---|---|
| 0 | Python Environment, pip, uv and Virtual Environments | Installing Python, `pip`, `venv`, `uv`, `requirements.txt`, Jupyter |
| 1 | Introduction to Programming and Python | Programs, algorithms, how Python runs code, notebooks, comments, indentation, naming |
| 2 | Variables, Data Types and Operators | Variables, `int` / `float` / `str` / `bool` / `None`, type conversion, all operators, precedence |
| 3 | Input and Output | `print()`, `sep` / `end`, escape characters, `input()`, f-strings, `.format()`, full interactive programs |
| 4 | Strings | Indexing, slicing, immutability, string methods, text processing |
| 5 | Decision Making | `if` / `elif` / `else`, conditions, nesting, the conditional expression |
| 6 | Loops and Iteration | `for`, `while`, `range()`, `break` / `continue` / `pass`, counters and accumulators, nested loops |
| ★ | Mini Project — Quiz Application and Grade Report | Everything combined into one real program |
| ★ | Quick Reference (Cheat Sheet) | One-page summary of the syntax |

Every module follows the same pattern: **concept → syntax → examples → common mistakes → exercises**.
The exercises include a quick review, *predict the output*, *find the error*, programming exercises and challenge problems — with the answers hidden until you click to expand them.

## Who this is for

- Beginners with **no programming experience**.
- University students starting a data-science, computer-science or engineering degree.
- Anyone who wants solid Python fundamentals before moving on to NumPy, pandas and machine learning.

No prerequisites — only a computer and curiosity.

## Quick start

**1. Get the files**

Download the repository as a ZIP (**Code → Download ZIP**) or clone it:

```bash
git clone https://github.com/<your-username>/python-for-data-science.git
cd python-for-data-science
```

**2. Create a virtual environment (recommended)**

```bash
# Windows
python -m venv .venv
.venv\Scripts\activate

# macOS / Linux
python3 -m venv .venv
source .venv/bin/activate
```

**3. Install the requirements**

```bash
python -m pip install -r requirements.txt
```

**4. Start JupyterLab and open the notebook**

```bash
jupyter lab
```

Then open `Python_for_Data_Science.ipynb` in the file browser.

> The notebook also works in VS Code and Google Colab (upload the `.ipynb` file). Python 3.10 or newer is required. Module 0 inside the notebook explains installation in detail.

## How to use the notebook

1. **Run a cell:** click it and press `Shift + Enter`. Run the notebook **from the top, in order** — later cells reuse variables created by earlier ones.
2. **Change the code and run it again.** Edit a number, a word or a condition and watch the output change. This *edit → run → observe* loop is how programming is learned.
3. **Interactive cells** (Module 3 and the Mini Project) use `input()`. A box appears when you run them — type your answer and press `Enter`. The saved output is a *sample run*.
4. **"Predict the Output" cells** are saved without output on purpose: guess first, then run to check yourself.
5. **Answers** are hidden inside `▶ Answers` blocks — try the exercise first, then click to expand.
6. **Something broke?** Use `Kernel → Restart` to clear all variables and run again from the top. For a cell stuck in an endless loop, use `Kernel → Interrupt`.
7. Each module ends with an empty **practice cell** for your own solutions.

> **Note:** "Run All" will pause at every `input()` cell and wait for you to type.

## Module outline

<details>
<summary><strong>Module 0 — Python Environment, pip, uv and Virtual Environments</strong></summary>

Why environments exist · installing Python · Python versions · ways to run Python · `pip` · virtual environments with `venv` · `requirements.txt` · `uv` as a faster alternative · checking your setup.
</details>

<details>
<summary><strong>Module 1 — Introduction to Programming and Python</strong></summary>

What programming is · programs and algorithms · problem solving · high-level vs low-level languages · why Python · the interpreter and bytecode · running Python (REPL, `.py`, notebooks) · Jupyter cells and the kernel · comments · indentation · keywords · identifiers and naming conventions · your first programs.
</details>

<details>
<summary><strong>Module 2 — Variables, Data Types and Operators</strong></summary>

Variables and reassignment · naming rules · multiple assignment · constants by convention · names and objects (`id()`) · dynamic typing · `int`, `float`, `complex`, `bool`, `str`, `None` · `type()` · type conversion · arithmetic, comparison, logical, assignment, membership and identity operators · `==` vs `is` · expressions and statements · operator precedence · real-world examples (area, average, temperature, interest, speed, currency).
</details>

<details>
<summary><strong>Module 3 — Input and Output</strong></summary>

`print()` with `sep` and `end` · escape characters · `input()` and the golden rule (it always returns a string) · converting input · handling invalid input · f-strings and number formatting · `.format()` · complete interactive programs (introduction card, calculator, percentage calculator, temperature converter, shopping bill).
</details>

<details>
<summary><strong>Module 4 — Strings</strong></summary>

Creating strings · indexing (positive and negative) · slicing and steps · concatenation, repetition, membership, comparison · immutability · `len()` · case, whitespace, replace, split/join and search methods · text-processing examples (word count, palindrome check, normalising text).
</details>

<details>
<summary><strong>Module 5 — Decision Making</strong></summary>

Boolean logic · `if` · `if ... else` · `if ... elif ... else` · indentation rules · combined and nested conditions · the conditional expression · practical programs (grading, electricity bill with slabs, login check, calculator, menu).
</details>

<details>
<summary><strong>Module 6 — Loops and Iteration</strong></summary>

Why loops · `for` and `range()` · looping over strings · `while` and infinite loops · `break`, `continue`, `pass` · counters and accumulators (count, sum, product, min/max, average, frequency) · nested loops and patterns · practical problems (reverse a number, primes, Fibonacci, guessing game, menu skeleton).
</details>

<details>
<summary><strong>Mini Project — Quiz Application and Grade Report</strong></summary>

Requirements → algorithm → pseudocode → step-by-step implementation → complete interactive program → testing → possible improvements. Uses only what Modules 1–6 teach.
</details>

## Repository structure

```text
python-for-data-science/
├── Python_for_Data_Science.ipynb   # the complete course notebook
├── README.md                       # this file
├── requirements.txt                # minimal requirements (JupyterLab)
├── .gitignore
└── LICENSE
```

## Where to go next

1. **Functions** — turn reusable chunks of code into named, reusable pieces.
2. **Collections** — lists, tuples, dictionaries and sets.
3. **Files and error handling** — read and write data files; handle mistakes gracefully.
4. **Data-science libraries** — **NumPy** (numerical arrays), **pandas** (tables of data), **Matplotlib** (charts) and **scikit-learn** (machine learning).

## License and credits

Released under the **MIT License** — see [`LICENSE`](LICENSE). The notebook is based on open, MIT-licensed course material; the original copyright and permission notice is kept in the `LICENSE` file as the license requires.

Found a typo or have an idea? Issues and pull requests are welcome.
