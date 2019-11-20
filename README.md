# Rock-Paper-Scissors-Image-Classifier-Using-Deep-Learning

An AI to play the Rock Paper Scissors game using your webcam.


## Requirements
- Python 3
- Keras
- Tensorflow
- OpenCV


## Set up instructions

1. Install the dependencies
```sh
$ pip install -r requirements.txt
```

2. Gather Images for each gesture (rock, paper and scissors and none):
here we gather 800 images for the "paper"
```sh
$ python3 gather_images.py paper 800
```

3. Train the model
```sh
$ python3 train.py
```

4. Play the game with your computer!
```sh
$ python3 play.py
```
