# HackNRollStageCraft
A tool that helps budding actors practise a wide range of emotions aided by computer vision.
We wish to compete for the Best freshman Hack.

Inspiration
We found acting hard when we were young, mainly due to the difficulty in displaying emotions at will in scenes, and making it look natural. Hence we decided to solve this problem by using emotion detection to make a game that can help people who want to get better at acting.

What it does
Fast paced, simple game where you eliminate enemy health by displaying the correct emotion for the displayed amount of time, and lose health if you're wrong.

How we built it
Used an emotion detection model built on keras and tensorflow, used Tkinter for the GUI and Pygame for the game. The model was obtained online, however we did initially train our own regression classification model, which proved to be quite slow in its execution. We split the work based on the various libraries and pieced everything together in the end.

Challenges we ran into
Fixing duration related bugs in the code, and displaying the correct emotions while testing the game! Also, trying out emotion detection for the first time, we learnt a lot from modifying the model and incorporating it with our game, and adjusting the game duration and difficulty. Running Pygame, Tkinter and openCV turned out to be taxing, so optimization of code and resources had to be done to maximize program efficiency and minimize latency. Text was also hard to implement for dynamically changing values(emotions and countdown) did not refresh on screen.

Accomplishments that we're proud of
We were able to build a simple game that can actually help people who wish to act, using computer vision. We incorporated 3 libraries in Python: OpenCV, Tkinter, Pygame in a span of 24 hours from scratch. We also created our own regression model which we later replaced by a CNN obtained open source. The project is modular in nature and hence the work distribution was smooth amongst teammates, leading to fruitful collaboration and a great learning experience.

We're proud of what we've learnt from this hackathon, and hope to scale it up for professionals, and even use it for applications like interview training by detecting confidence levels, and even train external confidence.

What we learned
All listed above, never tried emotion detection using machine learning before.

What's next for StageCraft
This idea can be scaled up for other applications like interview testing, which is what we'll be pursuing next!

NOTE: WE USED EXISTING MODEL FOR EMOTION CLASSIFICATION FROM A GITHUB REPO I THINK THIS ONE https://github.com/omar178/Emotion-recognition/blob/master/models/cnn.py
