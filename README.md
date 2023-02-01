# Getting-started-in-the-lab
## If you don't want to set up a python environment you can instead run the tutorials on google colab
## If you want to make a local enviroment then follow these directions
### Install Anaconda onto your computer [Link](https://www.anaconda.com/products/distribution)
### If on windows open the Anaconda promt which was just installed if on Mac/linux just open a terminal window and type this command
```
conda create --name bmtk python=3.8
```
### Then run the follow commands to activate your enviroment and install the python packages. If you are on a windows computer, to install neuron visit this [link](https://www.neuron.yale.edu/neuron/download) instead of using pip. You can also build bmtk from their GitHub but that should not be needed for now. Also make sure to downlaod this GitHub repo (WHICH ONE?) so you have the requirements.txt file on your computer. Then make sure to change your directory to this (WHICH ONE?) folder on your computer. 
```
conda activate bmtk
pip install -r requirements.txt
pip install bmtk, neuron
```
### Once these packages are all installed you should be good to go. You can run the tutorials by lauching jupyter notebook with this command
```
jupyter-notebook
```
### Then simply run the tutorials. If you wish to do some serious coding I would advice installing an IDE like [VS code](https://code.visualstudio.com/download) and linking your anaconda environment with VS code. If you need help with this step or any other step in this document i would try googling things like how to set up a conda enviroment and how to get started with python coding in VS code. 
