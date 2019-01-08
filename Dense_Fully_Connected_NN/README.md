# Dense, fully connected neural networks

This section is devoted to using exclusively traditional dense, fully connected neural networks to predict the outcome of hockey games. <br>

Both tensorflow and pytorch will be used to create the netoworks. Their performance (both in terms of speed and other performanc metrics such as accuracy, F1 score, precision, recall, etc.) will be measured and compared. <br>

The data source for this section can be found [here](https://www.kaggle.com/martinellis/nhl-game-data/version/1#_=_) thanks to the Kaggle of [Martin Ellis](https://www.kaggle.com/martinellis). 

# Packages and Libraries

In order to run this code, you will need to have both TensorFlow and PyTorch installed on your machine. 

If you're **running MacOS**, then simply open a command window and run the following commands to install the necessary libraries. 

1. Run `pip install --upgrade tensorflow` to make sure your version of TensorFlow is up to date
2. Run `pip install tflearn` 
3. If you're not using a virtual environment, Run: `sudo pip install keras` <br> 
If you're using a virtual environment, Run: `pip install keras` 
4. Run `pip3 install torch torchvision` 

