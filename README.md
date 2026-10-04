# Computational Theory

Jupyter notebook for the Computational Theory module assessment at [ATU](https://www.atu.ie/).
The problems investigate the SHA-256 hash algorithm defined in [FIPS 180-4 - Secure Hash Standard](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf).

## Contents

- `problems.ipynb`: the assessment notebook, one section per problem.
- `requirements.txt`: Python packages needed to run the notebook.
- `AGENTS.md`: agents file required by the assessment brief.
- `.gitignore`: files and folders Git should not track.

Progress on each problem is tracked with [GitHub Issues](https://github.com/Lynch4360/computational-theory/issues) (Problem 0).

### Running the notebook

The notebook was developed with Python 3.14. Both options below create a virtual environment in `.venv`,
which `.gitignore` already excludes.

#### Option 1: pip and venv

```bash
# Clone the repository.
git clone https://github.com/Lynch4360/computational-theory.git
cd computational-theory

# Create and activate a virtual environment.
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate

# Install the dependencies.
pip install -r requirements.txt

# Start Jupyter Lab and open problems.ipynb.
jupyter lab
```

#### Option 2: uv

[uv](https://docs.astral.sh/uv/) is a fast Python package and environment manager.
See the [uv installation guide](https://docs.astral.sh/uv/getting-started/installation/) to install it.
`uv pip` is uv's own replacement for pip, so pip itself is not needed.

```bash
# Clone the repository.
git clone https://github.com/Lynch4360/computational-theory.git
cd computational-theory

# Create a virtual environment with Python 3.14 (uv downloads it if needed).
uv venv --python 3.14

# Install the dependencies into .venv. No need to activate it first.
uv pip install -r requirements.txt

# Start Jupyter Lab inside .venv and open problems.ipynb.
uv run jupyter lab
```

You can also open the repository in [GitHub Codespaces](https://docs.github.com/en/codespaces),
which gives you a ready-made development environment in the browser.