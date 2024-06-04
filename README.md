# Chatbot tutorial
This repository contains some jupyter-notebooks to serve as a tutorial on how to create a RAG agent with LangChain.

# Pre-requesist

Please run these steps **before** the workshop. There are two ways to be ready for the workshop
1. Google Colab: Requires the least amount of set-up but requires a google account
2. Local: You can run all of this locally, but you would need to install a couple of things first

## Google Colab
Please sign-up with you Google account and go to: https://colab.research.google.com/ 

You can select GitHub and put this repository URL: https://github.com/ericksantillan-planday/chatbot-tutorial.git

On the page select Google_Colab.ipynb

Run the first two cells to be sure that you are ready for the workshop! And that's it :)

## Locally
You have to make sure that you have:
* Python installed
* Git installed
* Jupyter-lab or Jupyter-notebooks installed

### Install Python
For python you can use `Self-service`: Search for python and click installed.
Once it's been installed open a terminal and run the following to make sure you have python
```shell
python3 --version
```
For more info please see: https://www.python.org/downloads/


Now, clone the repository:
```shell
git clone https://github.com/ericksantillan-planday/chatbot-tutorial.git
```

Go to the repository and install the dependencies
```shell
cd chatbot-tutorial
pip3 install -r requirements.txt
```
Note: for simplicity we're installing everything in the default environment. If you want to have a separate environment please see: https://docs.python.org/3/library/venv.html

### Install Jupyter-notebooks
Once python is installed run:
```shell
pip3 install jupyterlab
jupyter lab
```
This should run a small web server and redirect you to a localhost page where all the notebooks are. Open [1-Basics_of_LangChain.ipynb](1-Basics_of_LangChain.ipynb) and run the first cells. Everything should be fine.

For more information about Jupyter, please see: https://jupyter.org/install

If something is not running feel free to ping us!