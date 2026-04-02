# Contributing to Python Portfolio

Welcome! This guide explains how to submit your Python project to this portfolio.

## Prerequisites

- A [GitHub account](https://github.com/join)
- [Git](https://git-scm.com/downloads) installed on your computer
- [Python 3](https://www.python.org/downloads/) installed on your computer

## Step-by-Step Instructions

### 1. Fork the Repository

Click the **Fork** button at the top-right of this page to create your own copy of the repository.

### 2. Clone Your Fork

```bash
git clone https://github.com/<your-username>/python-portfolio.git
cd python-portfolio
```

### 3. Create Your Project Folder

Create a folder for yourself under `projects/`, then a subfolder for your project:

```bash
mkdir -p projects/<your_name>/<project_name>
```

For example:
```bash
mkdir -p projects/jane_doe/calculator
```

### 4. Add Your Files

Add your Python source files and a `README.md` to your project folder:

```
projects/jane_doe/calculator/
├── README.md
└── calculator.py
```

Your `README.md` should include at least:
- **What the project does**
- **How to run it**

Example `README.md`:
```markdown
# Calculator

A simple command-line calculator that supports addition, subtraction, multiplication, and division.

## How to Run

```bash
python calculator.py
```
```

### 5. Commit and Push Your Changes

```bash
git add projects/<your_name>/<project_name>
git commit -m "Add <project_name> by <your_name>"
git push origin main
```

### 6. Open a Pull Request

1. Go to your fork on GitHub.
2. Click **Compare & pull request**.
3. Add a short description of your project.
4. Click **Create pull request**.

## Guidelines

- Place your project inside `projects/<your_name>/<project_name>/` — do **not** add files to the root of the repository.
- Each project folder must contain a `README.md`.
- Keep your Python files clean and readable.
- One pull request per project is preferred.

## Need Help?

If you run into any trouble, feel free to open an [issue](../../issues) and ask for help!
