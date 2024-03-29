# Shopping-cart-project

A software that allows you to enter the IDs of grocery store items and gives you a receipt.

## Prerequisites

  + Anaconda 3.7+
  + Python 3.7+
  + Pip

  ## Installation

Fork this [remote repository](https://github.com/averysomers/shopping-cart-project) under your own control, then "clone" or download your remote copy onto your local computer.

Then navigate there from the command line (subsequent commands assume you are running them from the local repository's root directory):

```sh
cd shopping-cart-project

Use Anaconda to create and activate a new virtual environment, perhaps called "shopping-cart-project":

```sh
conda create -n shopping-cart-project python=3.8
conda activate shopping-cart-project
```

After activating the virtual environment, install package dependencies (see the ["requirements.txt"](/requirements.txt) file):

```sh
pip install -r requirements.txt
```

> NOTE: if this command throws an error like "Could not open requirements file: [Errno 2] No such file or directory", make sure you are running it from the repository's root directory, where the requirements.txt file exists (see the initial `cd` step above).


## Usage

Run the shopping_cart script:

```py
python shopping_cart.py

When prompted, enter 1 through 20, depending on your item ID. Hit "Enter" in between each item. Enter "done" when you are completed. The software will then give you a receipt for the items.

> NOTE: if you see an error like "ModuleNotFoundError: No module named '...'", it's because the given package isn't installed, so run the `pip` command above to ensure that package has been installed into the virtual environment.
