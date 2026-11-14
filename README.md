# 🐍 Python Programming for Business Analytics

**NEOMA Business School · MSc Business Analytics · 2026/27 · dr. Uroš Godnov**

Five sessions, fifteen hours. You already know R: now you answer the **same business questions with the same data in Python**, the language most companies use for analytics, automation and AI.

## 🗺️ The route

| Session | Format | Mission | Lecture notebook | Practice |
|---|---|---|---|---|
| 🧰 S00 · Before we begin | Self-paced | Hello, Python! Ready check | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S00_hello_python.ipynb) |  |
| 🐍 S1 · Python & notebooks | Live · 3 h | Types, lists, dicts, functions, first DataFrame | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S01_lecture_python_basics.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S01_practice.ipynb) |
| 🛡️ S2 · Python that does not break | Live · 3 h | Guard rails, exceptions, the bullet-proof importer | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S02_lecture_robust_python.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S02_practice.ipynb) |
| 🐼 S3 · pandas: the grammar of data | Live · 3 h | Filter, assign, groupby, merge, reshape, missing values | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S03_lecture_pandas.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S03_practice.ipynb) |
| 📊 S4 · Visualisation & storytelling | Live · 3 h | seaborn + matplotlib, from default charts to decisions | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S04_lecture_visualisation.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S04_practice.ipynb) |
| 📈 S5 · Correlation & regression | Asynchronous · 3 h | statsmodels: from "these move together" to "this is how much" | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S05_selfpaced_regression.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S05_practice.ipynb) |
| 📝 S5 deliverable | Asynchronous | Pay equity memo | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/S05_pay_equity_memo.ipynb) | |
| 🏆 Final project | Individual · 3 weeks | Data analysis and storytelling with Python | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/urosgodnov/neoma-python-2627/blob/main/notebooks/final_project_template.ipynb) | |

## ▶️ Two ways to work

**Google Colab (nothing to install).** Click *Open in Colab*, then *File → Save a copy in Drive*: the copy is yours. Run the ⚙️ Setup cell first. Gemini ✦ (bottom of the screen) explains code and errors.

**Positron (on your laptop).** *Code → Download ZIP* on this page, unzip, then in Positron *File → Open Folder* → `neoma-python-2627-main`. Create a Python environment and install the packages once:

```bash
pip install -r requirements.txt
```

The notebooks read the data from the local `data/` folder when it exists, otherwise from this repository.

## 🔤 Inside every notebook

🔮 Predict before you run · 💬 Discuss · 🧪 Try it · 🆚 R ↔ Python · ⚠️ Pitfall · 🤖 AI moment · ☕ Break after 90 minutes

## 📦 Data (identical to the R course)

| File | Source |
|---|---|
| `data/penguins.csv` | Palmer penguins (Horst, Hill & Gorman, 2020), column names as in base R 4.5 |
| `data/sales/` | Seven monthly sales files with deliberate problems (course data) |
| `data/nycflights13/` | All flights from New York in 2013, R package `nycflights13` (Wickham) |
| `data/gapminder.csv` | Gapminder, R package `gapminder` (Bryan) |
| `data/ames.csv` | Ames house prices (De Cock, 2011), `modeldata::ames` |
| `data/attrition.csv` | IBM HR attrition (fictional), `modeldata::attrition` |

CSV versions of the R datasets come from [Rdatasets](https://vincentarelbundock.github.io/Rdatasets/).

Solutions, quizzes and the final project grading grid are in Moodle for enrolled students.

© 2026 Uroš Godnov · teaching materials for Python Programming for Business Analytics at NEOMA Business School.
