# Poker Recognization and Black Jack Stragegy

This is a app that can recognize dealer's and player's poker cards in image uploaded and provide corresponding strategy for the player to win the Blackjack game. We trained 2 models using Yolov4 with 2 different image data set, one without image aumentagion and one under proprocessing. 

## Data set
We collected poker card images from Internet. 

## Image preprocessing
We labels the poker card in images with a graphical image annotation tool called labelImg by drawing rectangles over images and defining their weight, height, X coordinates and Y coordinates.

<img width="512" alt="image" src="https://user-images.githubusercontent.com/43593664/121898296-d25a9c80-cd55-11eb-8d94-37bd21bdb44e.png">


## Models
Yolov4 is the state-of-the-art object recognition model with highest speed and accuracy. We retrained the Yolov4 with our own poker card images. 




## to run the app
cd streamlit
streamlit run app.py


