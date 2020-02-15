# TV Script Generation
In this project, you'll generate your own Seinfeld TV scripts using RNNs. You'll be using part of the Seinfeld dataset of scripts from 9 seasons. The Neural Network you'll build will generate a new ,"fake" TV script, based on patterns it recognizes in this training data. Final Project Notebook

1. Installation
Download Anaconda

Linux	Mac	Windows
64-bit	64-bit (bash installer)	64-bit (bash installer)	64-bit (exe installer)
32-bit	32-bit (bash installer)		32-bit (exe installer)
Install Anaconda on your machine. Detailed instructions:

2. Create and Activate the Environment
Please go though this doc before you creating an environment. After that create a environment using following command

conda create --name deep-learning
Then activate the environment using following command

activate deep-learning
Git and version control
These instructions also assume you have git installed for working with Github from a terminal window, but if you do not, you can download that first with the command:

conda install git
Now, you can create a local version of the project

Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
git clone https://github.com/koushik-elite/TV-Script-Generation.git
cd TV-Script-Generation
Install PyTorch and torchvision; this should install the latest version of PyTorch.

Linux or Mac:
conda install pytorch torchvision -c pytorch 
Windows:
conda install pytorch -c pytorch
pip install torchvision
Install a few required pip packages, which are specified in the requirements text file (including OpenCV).

pip install -r requirements.txt
Or

conda install --yes --file requirements.txt
That's it!, Now run the project using following command, check you default browser and open dlnd_tv_script_generation.ipynb file
jupyter notebook
