# 📘 Learn Machine Learning Python

**Learn Machine Learning Python** is a personal learning repository
containing Python code examples, experiments, and notes created while
studying machine learning. This project documents hands-on practice,
core ML concepts, and step-by-step workflows using essential libraries
such as **NumPy**, **Pandas**, **Scikit-learn**, **Matplotlib**, and
others.

The repository is designed to be simple, clean, and easy to
follow---perfect for beginners and for personal reference.

---

## 📂 Project Structure

    learn-machine-learning-python/
    │── .venv/                # Virtual environment (ignored by git)
    │── notebooks/            # Jupyter Notebook experiments
    │── pyproject.toml        # Project metadata (optional)
    │── .gitignore
    │── README.md

---

## 🔧 Setup Instructions

Follow these steps after cloning the repository.

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/<your-username>/learn-machine-learning-python.git
cd learn-machine-learning-python
```

### 2️⃣ Create a Virtual Environment

```bash
python -m venv .venv
```

### 3️⃣ Activate the Environment

**Windows (Git Bash / PowerShell):**

```bash
source .venv/Scripts/activate
```

**macOS / Linux:**

```bash
source .venv/bin/activate
```

### 4️⃣ Install Dependencies

**Using requirements.txt**

```bash
pip install -r requirements.txt
```

**Using pyproject.toml**

```bash
pip install .
```

### 5️⃣ Running Jupyter Notebook

```bash
pip install jupyter
jupyter notebook
```

### 6️⃣ Running Python Scripts

```bash
python src/<file_name>.py
```

Example:

```bash
python src/iris_standardization.py
```

### 7️⃣ Deactivate the Environment

```bash
deactivate
```

---

## 🧠 Topics Covered

- Basic ML workflow\
- Data preprocessing (scaling, splitting, cleaning)\
- Exploratory Data Analysis (EDA)\
- Classification & Regression\
- Model evaluation\
- Feature engineering\
- Notebook-based experimentation

---

## 📦 Requirements

- Python **3.10.x** (recommended: 3.10.11)
- pip 21+
- Virtual environment support

---

## 📄 License

This repository is intended for **personal learning and educational
purposes**.\
Feel free to fork or reference it.
