# Jupyter-Supplemental-Exercises

Welcome to the UP Data Science Society's Jupyter tutorials made by students, for fellow students. To fully utilize these Jupyter Supplemental Exercises (JSEs), please refer to the following pre-installation instructions below.

# Pre-installation

The following instructions refer to installing this library using the `uv` package manager. It is a lightweight, robust alternative to installing in `pip`, complete with the additional benefits of dependency management and fast package installation.

## Installing uv
First, install `uv` if you haven't already:

### macOS/Linux
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### Windows
```powershell
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"
```

### Alternative: Using pip
```bash
pip install uv
```

## Creating and Setting Up Your Virtual Environment

### 1. Create a new virtual environment
```bash
uv venv
```
This creates a virtual environment named `myproject-env` in your current directory.

### 2. Activate the virtual environment

**macOS/Linux:**
```bash
source .venv/bin/activate
```

**Windows:**
```bash
.venv\Scripts\activate
```

### 3. Verify activation
Your terminal prompt should now show `(Jupyter-Supplemental-Exercises)` at the beginning, indicating you're in the virtual environment.

### 4. Install packages
```bash
# Install packages using uv (much faster than pip)
uv pip install pandas matplotlib jupyter
```

### 5. Deactivate when done
```bash
deactivate
```

# Usage

When locally tinkering with these JSEs, it is best to do so while in a virtual environment with the listed packages above.