# I want to install tinygrad and its dependencies to start exploring its features and contributing to the project.

_Install tinygrad using pip and set up the development environment._

## Steps

1. Clone the tinygrad repository using the command `git clone https://github.com/tinygrad/tinygrad.git`
2. Navigate to the cloned repository using `cd tinygrad`
3. Install the required dependencies using `pip install -r requirements.txt`
4. Verify the installation by running `python -c 'import tinygrad as tg; print(tg.__version__)'`
5. Set up a virtual environment for development using `python -m venv tinygrad-env` and activate it with `source tinygrad-env/bin/activate`

## Pitfalls

- Forgetting to activate the virtual environment before installing dependencies