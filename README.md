# Computational Theory

Jupyter notebook for the Computational Theory module assessment at [ATU](https://www.atu.ie/).
The problems investigate the SHA-256 hash algorithm defined in [FIPS 180-4 - Secure Hash Standard](https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf)

## Contents

'problems.ipynb' is the assessment notebook, one section per problem.
'requirements.txt' Python packages needed to run the notebook.

### Running the notebook

```bash
# Clone the repository.
- git clone https://github.com/lynch4360/computational-theory.git
- cd computational-theory

# Create and activate a virtual environment.
python -m venv .venv
source .venv/bin/activate # windows is .venv\Scripts\activate

# Install the dependencies
pip install -r requirements.txt

# Start the Jupyet Lab and open problems.ipynb
jupyter lab

# You can also use [GitHub Codespaces](https://docs.github.com/en/codespaces),
# which comes with python and Jupyter already set up
```