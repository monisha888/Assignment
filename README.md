# 🐍 Python - Assignments: Lists, Dictionaries & Strings

A collection of beginner-to-intermediate Python practice problems covering three core data structures: **Lists**, **Dictionaries**, and **Strings**. Each notebook contains 10 hands-on coding questions with sample inputs/outputs, designed for interactive learning in Jupyter/Google Colab.



---

## 📁 Repository Structure

```
.
├── copy_of_python_list.py          # 10 questions on Python Lists
├── copy_of_python_dictionary_.py   # 10 questions on Python Dictionaries
├── copy_of_python_strings_.py      # 10 questions on Python Strings
└── README.md                       # You are here
```

Each file is a Python script exported from a Google Colab notebook (`.ipynb` → `.py`), where Markdown cells (questions) are preserved as triple-quoted comments, and code cells contain the corresponding solutions.

---

## 📚 Topics Covered

### 1. `copy_of_python_list.py` — Python Lists

| # | Question | Concept |
|---|----------|---------|
| 1 | Count elements in a list without `len()` | Manual iteration/counting |
| 2 | Find max and min values | Comparison logic |
| 3 | Remove first occurrence of an element | List building, flags |
| 4 | Find the average of all elements | Sum + count |
| 5 | Check if a list is empty | Conditional checks |
| 6 | Find index of a specified element | `range()`, indexing |
| 7 | Check if numbers in a list are palindromes | Digit reversal |
| 8 | Find common elements between two lists | Nested loops |
| 9 | Remove duplicates from a list | Membership check (`in`) |
| 10 | Sort strings in ASCII order | Bubble sort using `ord()` |

### 2. `copy_of_python_dictionary_.py` — Python Dictionaries

| # | Question | Concept |
|---|----------|---------|
| 1 | Get value for a given key | Key access |
| 2 | Update dictionary with a new key-value pair | `.update()` |
| 3 | Check if a key exists | `in` / `not in` |
| 4 | Sum all values in a dictionary | `.values()` |
| 5 | Get a list of all keys | `.keys()` |
| 6 | Get a list of all values | `.values()` |
| 7 | Count key-value pairs | Iteration/counting |
| 8 | Merge two dictionaries | Manual merge loop |
| 9 | Sort a dictionary by values (ascending) | *(left as an exercise — see [Notes](#-notes--known-issues))* |
| 10 | Find the key with the maximum value | `max()` |

### 3. `copy_of_python_strings_.py` — Python Strings

| # | Question | Concept |
|---|----------|---------|
| 1 | Count characters without `len()` | Manual counting |
| 2 | Reverse a string without `[::-1]` | Loop-based reversal |
| 3 | Check if a string is a palindrome | String comparison |
| 4 | Find the most common character | Frequency dictionary |
| 5 | Check if two strings are anagrams | Nested loop comparison |
| 6 | Remove all vowels from a string | Conditional filtering |
| 7 | Find the longest word in a string | Word splitting by space |
| 8 | Capitalize the first letter of each word (no `.title()`) | ASCII manipulation (`ord`/`chr`) |
| 9 | Find frequency of each character | Frequency dictionary |
| 10 | Sum ASCII values of all "even" characters | `ord()`, modulo |

---

## 🚀 How to Run

1. **Clone or download** this repository.
2. Open any `.py` file in a Python environment (VS Code, Jupyter, Colab, or plain terminal).
3. Run the file directly:
   ```bash
   python copy_of_python_list.py
   ```
   > Note: The string and dictionary exercises use `input()` for several questions, so you'll be prompted to type values when running those scripts.
4. Alternatively, open the original Colab notebooks (linked at the top of each file) to run questions cell-by-cell.

### Requirements
- Python 3.x (no external libraries required — all solutions use built-in functionality only)

---

## 🎯 Learning Goals

These exercises are designed to build a strong foundation by **avoiding shortcuts** wherever possible — for example:
- Counting elements without `len()`
- Reversing strings without slicing (`[::-1]`)
- Capitalizing words without `.title()`

This forces practice with core programming concepts like loops, conditionals, and manual algorithm design rather than relying on built-in convenience functions.

---

## 🧩 Problem-Solving Pattern

Most solutions in this repo follow the same general approach:

1. **Read the question and sample input/output carefully** — identify exactly what's given and what's expected back.
2. **Identify the restriction** — many questions ban a built-in shortcut (`len()`, `[::-1]`, `.title()`); note this before writing any code.
3. **Pick a manual technique** that achieves the same result — usually a `for` loop with a counter, accumulator, or temporary list/dict.
4. **Initialize state before the loop** — counters at `0`, results as `[]` or `{}`, flags as `False`.
5. **Update state inside the loop** — increment, compare, append, or build up the result one element/character at a time.
6. **Handle the edge case** — empty input, no match found, single-element input, etc.
7. **Print or return the result** in the format shown in the sample output.

This pattern (read → restrict → initialize → loop → handle edge case → output) repeats across nearly all 30 questions, just applied to lists, dicts, or strings.

## 🤔 Ask Yourself Before Solving

Before writing code for any of these questions, pause and answer:

- What does the question give me, and what exactly should I return or print?
- Is there a built-in function I'm *not allowed* to use? What would I use instead?
- Do I need to track a running value (sum, count, max/min) or build up a new collection?
- What's the smallest/empty/edge-case input, and does my logic still work for it?
- Can I trace through the sample input by hand and get the sample output before running the code?
- Is there a simpler loop structure (single loop vs. nested loop) that solves this?

