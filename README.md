# Bootstrapping Computational Art

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fimg.huffingtonpost.com%2Fasset%2F5b6b3e792000009f00379402.jpeg%3Fops%3Dscalefit_720_noupscale&f=1&nofb=1" width=30%>

Baron Munchausen demonstrating an act of [Bootstrapping](https://www.huffpost.com/entry/pull-yourself-up-by-your-bootstraps-nonsense_n_5b1ed024e4b0bbb7a0e037d4).

## Requirements

### Git

Git is a free and open source distributed version control system.
Macs should have it preinstalled, otherwise you can download it here:

https://github.com/git-guides/install-git

### Anaconda for python

Anaconda is a package manager, an environment manager, and Python distribution that contains a collection of many open source packages.
You can find the install instructions for your platform here:

https://docs.anaconda.com/anaconda/install/index.html

Once anaconda is installed you can open a terminal or anaconda prompt (for windows). If it was installed correctly you should see `(base)` next to your username. Alternatively you can type `conda` in your terminal to check if it works.

To create an environment for this class enter the following into your terminal:

`conda create --name bca python=3.9`
This command will set up an environment called 'bca' using python 3.9.

To activate the environment in your current terminal session, simply type:

`conda activate bca`

### Jupyter Lab

We will use Jupyter to work with python notebooks directly in the browser.
Once you have Anaconda up and running and activated your environment you can simply install jupyter with pip by entering:

`pip install jupyterlab`

to run jupyter:
`jupyter lab`

### Clone this repository

Finally clone this repository. To do so, first change your directory to the location where you would like to install it using the `cd` command in your terminal. On Mac you could for example `cd Desktop` and press enter.

Now you can write the following in your terminal:
`git clone https://github.com/coralreefman/bca.git`

done.

## Planning

|Day             |Description                    |Focus                         |
|----------------|-------------------------------|------------------------------|
|1               |boot day                       |install fest and python basics|
|2               |noise day                      |randomness and noise          |
|3               |algorithm day                  |generative code fundamentals  |
|4               |data day                       |data retrieval and structures |
|5               |transformation day             |what to do with data?         |
|----------------|-------------------------------|------------------------------|
|6               |project day                    |work on personal project      |
|7               |project day                    |work on personal project      |
|8               |project day                    |work on personal project      |
|9               |birth day                     |the first prototype           |
|10              |studio visit D&V               |visit and presentation        |

_“In the computer field, the moment of truth is a_
_running program; all else is prophecy.”_

Herbert Simon
