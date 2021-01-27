1.1 Dataset
	- fer2013.csv- The dataset used to train and evaluate Facial Emotion Recognition for this research.
	- music_mood.csv - The dataset used to train and evaluate the Music Classification for this research.
1.2 Python Code
	- facial.py- Code for model architecture used for various algorithms used for FER and saving the weights in pickle file.
	- tkinter_GUI.py- The main application which is used to capture the image and recommend apropriate music as per the predicted mood.
	- facial_training.ipynb- Training of various models for FER using the facial.py file and some data preprocessing and model evaluation graphs.
	- music_mood.ipynb- Training of various models to classify Music and storing the classified songs into their respective csv files which are utilized for music recommendation.
1.3 Music Files
	- Calm.csv- Names of songs classified as Calm.
	- Energetic.csv - Names of songs classified as Energetic.
	- Happy.csv - Names of songs classified as Happy.
	- Sad.csv -Names of songs classified as Sad.
1.4 Others
	- haarcascade_frontalface_default.xml- Used for face detection purposes.
	- cnn_model.pkl- Pickle file generated for CNN model on fer2013 data.

1.5 Order of executing:
	1.facial_training.ipynb : Creates required .pkl files for every model
	2.music_mood.ipynb : Creates .csv files of every mood
	3.tkinter_GUI.py: Main file it uses .pkl files and .csv files created in steps 1 and 2 for music recommendation.

Following libraries are required for running the application

	pip install tensorflow==1.14.0
	pip install keras==2.2.5


	if any module is missing :
	pip install module_name