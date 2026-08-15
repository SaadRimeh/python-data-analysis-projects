<h1 align="center">🐍 Python Data Analysis — Learning Repository</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-Arrays-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status"/>
</p>

<p align="center">
  A structured, hands-on Python learning journey — from core fundamentals to data analysis with Pandas & NumPy.
</p>

---

## 👤 Author

| Field        | Details              |
|--------------|----------------------|
| **Name**     | Saad Rimeh           |
| **Focus**    | Python & Data Analysis |
| **Tool**     | Jupyter Notebook     |

---

## 📁 Repository Structure

```
Data_Analyse/
│
├── 📓 Example.ipynb       # Main learning notebook (Python fundamentals + Data Analysis)
├── 📂 New Folder/         # Workspace directory (created via os.makedirs)
└── 📄 README.md           # Project documentation (this file)
```

---

## 📚 Topics Covered

The notebook `Example.ipynb` is organized into the following sections:

### 🔵 Python Fundamentals

| # | Topic | Key Concepts |
|---|-------|-------------|
| 1 | **First Print** | `print()`, output basics |
| 2 | **Data Types** | `int`, `float`, `str`, `bool` |
| 3 | **Operators** | `+`, `-`, `*`, `/`, `%` (arithmetic) |
| 4 | **String Methods** | `.upper()`, `.lower()`, `.title()`, `.count()`, `.replace()` |
| 5 | **Variables** | Assignment, f-strings, string concatenation |
| 6 | **Lists** | Indexing, slicing, `.append()`, `.insert()`, `.remove()`, `.pop()`, `del`, `.sort()`, `.copy()` |
| 7 | **Dictionary** | Key-value pairs, `.keys()`, `.values()`, `.items()`, `.update()`, `.copy()`, `.pop()`, `.clear()` |
| 8 | **If Statement** | `if` / `elif` / `else` conditional logic |
| 9 | **For Loop** | Iteration, `enumerate()`, looping over dictionaries |
| 10 | **Functions** | `def`, parameters, `return`, built-in functions (`len`, `max`, `min`, `range`) |
| 11 | **Modules** | `import`, OS Module (`os.getcwd()`, `os.listdir()`, `os.makedirs()`) |

### 🟠 Data Analysis

| # | Topic | Key Concepts |
|---|-------|-------------|
| 12 | **NumPy Arrays** | `np.array()`, multi-dimensional arrays |
| 13 | **Pandas DataFrames** | `pd.DataFrame()`, custom index & columns |

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.x installed, then install the required libraries:

```bash
pip install jupyter pandas numpy
```

### Running the Notebook

```bash
# Navigate to the project directory
cd Data_Analyse

# Launch Jupyter Notebook
jupyter notebook
```

Then open `Example.ipynb` in your browser.

---

## 🧩 Key Concepts Snapshot

```python
# Variables & f-strings
message_1 = "I am learning Python "
message_2 = "and it is fun!"
message = f'{message_1}{message_2}'
# → 'I am learning Python and it is fun!'

# List operations
countries = ['Japan', 'Brazil', 'Canada', 'Australia', 'Egypt']
countries.append('Syria')        # Add to end
countries.insert(0, 'Spain')     # Add at index
countries.sort()                 # Sort ascending

# Dictionary
my_data = {'name': 'saad', 'age': 25}
my_data['height'] = 1.8          # Add new key
my_data.update({'height': 1.9})  # Update existing key

# For loop with enumerate
for i, country in enumerate(countries):
    print(f"{i}: {country}")

# Custom function
def sum_values(a, b):
    return a + b

# Pandas DataFrame from NumPy array
import pandas as pd
import numpy as np

data = np.array([[1, 4], [2, 5], [3, 6]])
df = pd.DataFrame(data, index=['row1', 'row2', 'row3'], columns=['col1', 'col2'])
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Python 3.x** | Core programming language |
| **Jupyter Notebook** | Interactive development environment |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computing and array operations |
| **OS Module** | File system interaction |

---

## 📈 Learning Roadmap

- [x] Python syntax & print statements
- [x] Data types & type checking
- [x] Arithmetic operators
- [x] String manipulation methods
- [x] Variables & f-strings
- [x] Lists — CRUD operations & sorting
- [x] Dictionaries — key-value management
- [x] Conditional logic (`if`/`elif`/`else`)
- [x] Loops (`for`, `enumerate`)
- [x] Functions & built-in functions
- [x] Modules (OS module)
- [x] NumPy arrays
- [x] Pandas DataFrames
- [ ] Data cleaning & preprocessing
- [ ] Data visualization (Matplotlib / Seaborn)
- [ ] Exploratory Data Analysis (EDA)

---

## 📝 Notes & Best Practices

> **💡 Tip:** In a Jupyter cell with multiple expressions, only the **last expression** is displayed automatically. Use `print()` to display all outputs.

> **💡 Tip:** Use `list.copy()` or `list[:]` to make a **shallow copy** of a list. Assigning with `=` creates a **reference**, not a copy.

> **💡 Tip:** `pop()` removes an item **and returns its value**, while `del` removes it **without returning** anything.

> **💡 Tip:** Python is **case-sensitive** — `'a'` and `'A'` are different characters in string methods like `.count()`.

---

## 📄 License

This project is open for educational purposes. Feel free to explore, learn, and build upon it.

---

<p align="center">
  Made with ❤️ by <strong>Saad Rimeh</strong> | Powered by Python 🐍
</p>
