Greg Schafer - CSCE 478 - Dec 10, 2012 , Updated on Jan 2019

Project - Reinforcement Learning Bejeweled using Tensorflow

Environment
============

* Python 3.6.4
* Tensorflow1.7.1
* OpenCV
* PyGame

RUNNING THE CODE
================
Without GUI

    python DQN.py

To graphically show the learner playing Bejeweled, change demo flag in DQN.py:

    demo = True   

THANKS
======
* Yichi Xiao, @switchball, the main contributor of the tensorflow code https://github.com/switchball/AI-For-Bejeweled
* Greg Schafer for the code using PyBrain https://github.com/grschafer/BejeweledBot
* Al Sweigart for his [Bejeweled implementation in pygame][bejeweled] that      
allowed me to demo the program graphically and helped me understand what the    
learner was doing!                                                              
* Osmic for the [icons][gems] used in Al's game

[bejeweled]: http://inventwithpython.com/blog/2011/06/24/new-game-source-code-gemgem-a-bejeweled-clone/
[gems]: http://opengameart.org/content/gem-jewel-diamond-glass
