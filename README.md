# Build A Salary Prediction Web App With Streamlit

Build a Machine Learning web application from scratch in Python with Streamlit. We use real world data to build a machine learning model. In the first part of the video you learn how we analyze the data and build our model, and in the second part we build the web app using streamlit.

# Install Streamlit
Table of contents
Prerequisites
Install Streamlit on Windows
Install Streamlit on macOS/Linux
Prerequisites
Before you get started, you're going to need a few things:

Your favorite IDE or text editor
Python 3.7 - Python 3.10
PIP
Set up your virtual environment
Regardless of which package management tool you're using, we recommend running the commands on this page in a virtual environment. This ensures that the dependencies pulled in for Streamlit don't impact any other Python projects you're working on.

Below are a few tools you can use for environment management:

pipenv
poetry
venv
virtualenv
conda

## Install Streamlit on Windows
Streamlit's officially-supported environment manager on Windows is Anaconda Navigator.

Install Anaconda
If you don't have Anaconda install yet, follow the steps provided on the Anaconda installation page.

Create a new environment with Streamlit
Next you'll need to set up your environment.

Follow the steps provided by Anaconda to set up and manage your environment using the Anaconda Navigator.

Select the "▶" icon next to your new environment. Then select "Open terminal":

"Open terminal" in Anaconda Navigator
In the terminal that appears, type:

pip install streamlit
Copy
Test that the installation worked:

streamlit hello
Copy
Streamlit's Hello app should appear in a new tab in your web browser!

Use your new environment
In Anaconda Navigator, open a terminal in your environment (see step 2 above).

In the terminal that appears, use Streamlit as usual:

streamlit run myfile.py
Copy

## Install Streamlit on macOS/Linux
Streamlit's officially-supported environment manager for macOS and Linux is Pipenv. See instructions on how to install and use it below.

Install Pipenv
Install pip. More details about installing pip can be found in pip's documentation.

On a macOS:

python -m ensurepip --upgrade
Copy
On Ubuntu with Python 3:

sudo apt-get install python3-pip
Copy
For other Linux distributions, see How to install PIP for Python.

Install pipenv.

pip3 install pipenv
Copy
Install Xcode command line tools on macOS
On macOS, you'll need to install Xcode command line tools. They are required to compile some of Streamlit's Python dependencies during installation. To install Xcode command line tools, run:

xcode-select --install
Copy
Create a new environment with Streamlit
Navigate to your project folder:

cd myproject
Copy
Create a new Pipenv environment in that folder and activate that environment:

pipenv shell
Copy
When you run the command above, a file called Pipfile will appear in myprojects/. This file is where your Pipenv environment and its dependencies are declared.

Install Streamlit in your environment:

pip install streamlit
Copy
Or if you want to create an easily-reproducible environment, replace pip with pipenv every time you install something:

pipenv install streamlit
Copy
Test that the installation worked:

streamlit hello
Copy
Streamlit's Hello app should appear in a new tab in your web browser!

Use your new environment
Any time you want to use the new environment, you first need to go to your project folder (where the Pipenv file lives) and run:

pipenv shell
Copy
Now you can use Python and Streamlit as usual:

streamlit run myfile.py
Copy
To stop the Streamlit server, press ctrl-C.

When you're done using this environment, just type exit or press ctrl-D to return to your normal shell.

Now that you've installed Streamlit, take a few minutes to read through Main concepts to understand Streamlit's data flow model.
