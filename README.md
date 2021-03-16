#Your First Neural Network
Build your first neural network using PyTorch!
## Overview
In this session, you will build your first neural network from scratch!   You will be analyzing a synthetic dataset from a fictional lemonade stand.  After training, your neural network will be able to predict the number of lemons likely sold on a given day!  Let's get started!
## Session Agenda
1.  Deep learning basics
2.  PyTorch Overview
3.  Load and explore the dataset
4.  Build your neural network
5.  Train the network
6.  Make predictions!
## Setting Up Your Environment
You have 3 options to follow along.  If you have a GPU on your laptop/desktop, you can load the libraries and dataset locally and run the notebook locally.   Otherwise, you can choose to run the notebook (free) in Google Colab.  Note, it is not required that you run the notebook to attend the session but it will help you understand the content.
### Option 1 - Setup your own laptop/PC with GPU for this workbook
If you have a GPU and want to work on your own laptop/PC:
1.  Download the dataset from leaky.ai/datasets/lemonade.csv
2.  Download Anaconda  (https://www.anaconda.com/distribution/)
3.  Create a virtual environment using Anaconda on your local machine by following these commands:

```
conda create –name python3 python=3.8
conda activate python3
conda install pytorch torchvision cudatoolkit=10.2 -c pytorch
conda install matplotlib jupyter
conda install -c intel scikit-learn
pip install efficientnet_pytorch
pip install torchsummary
python -m ipykernel install --user --name python3 --display-name "python3 "
git clone https://github.com/LeakyAI/FirstNeuralNet 
jupyter notebook
```

4. Skip Option 2 below and deactivate the first code cell of the notebook by selecting it and typing "R" (intended for Colab only)
5. Specify the directory of your dataset in the 2nd cell below.

### Option 2 - Follow along in a Google Colab workbook

If you want to work in Google Colab, into Colab and pull the notebook file from GitHub:
1.  Go to colab.research.google.com
2.  Click **GitHub** and paste the address ** https://github.com/LeakyAI/FirstNeuralNet **
3.  Click **Search Icon**
4.  Click on ** FirstNeuralNetworkSolution.ipynb **, notebook should now open
5.  Set the notebook settings to **Python** and **GPU** (**Edit -> Notebook Settings**) 

Then, we will load the dataset into Colab by executing the first cell (click the cell, then click **crtl+enter**).

### Option 3 - Just follow along during the presentation
Running the notebook is not required to get something out of the session :)
