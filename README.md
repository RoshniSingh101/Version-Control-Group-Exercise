# Version-Control-Group-Exercise
Names: Eesha, Jess, Roshni

## Program Function
Our program relays out an ask for the user to watch a movie together. 
The first two lines of code take in input. Specifically, the first will ask for the name of the user with the variable storage called "name". After the user has complied, the next ask will be what their favorite movie is with the variable storage called "favMovie". The last line relays out a print of "Hey (name), do you want to watch a movie together?" 

Example of input code: 
name = input("What is your name? ") 

--

## Getting started

### Installation

If you use [conda](https://docs.conda.io/en/latest/), [mamba](https://mamba.readthedocs.io/en/latest/), or [pip](https://docs.python.org/3/installing/index.html), you can install JupyterLab with one of the following commands.

- If you use conda:
  ```shell
  conda install -c conda-forge jupyterlab
  ```
- If you use mamba:
  ```shell
  mamba install -c conda-forge jupyterlab
  ```
- If you use pip:
  ```shell
  pip install jupyterlab
  ```
  If installing using `pip install --user`, you must add the user-level `bin` directory to your `PATH` environment variable in order to launch `jupyter lab`. If you are using a Unix derivative (e.g., FreeBSD, GNU/Linux, macOS), you can do this by running `export PATH="$HOME/.local/bin:$PATH"`. If you are using a macOS version that comes with Python 2, run `pip3` instead of `pip`.

For more detailed instructions, consult the [installation guide](http://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html). Project installation instructions from the git sources are available in the [contributor documentation](CONTRIBUTING.md).

#### Installing with Previous Versions of Jupyter Notebook

When using a version of Jupyter Notebook earlier than 5.3, the following command must be run after installing JupyterLab to enable the JupyterLab server extension:

```bash
jupyter serverextension enable --py jupyterlab --sys-prefix
```

### Running

Start up JupyterLab using:

```bash
jupyter lab
```

JupyterLab will open automatically in the browser. See the [documentation](http://jupyterlab.readthedocs.io/en/latest/getting_started/starting.html) for additional details.

If you encounter an error like "Command 'jupyter' not found", please make sure `PATH` environment variable is set correctly. Alternatively, you can start up JupyterLab using `~/.local/bin/jupyter lab` without changing the `PATH` environment variable.

### Prerequisites and Supported Browsers

The latest versions of the following browsers are currently _known to work_:

- Firefox
- Chrome
- Safari

See our [documentation](http://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html) for additional details.

---
