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

TO DO
======
1. Improve deep learning result
2. Revamp the code, all the tensorflow logic was copied from https://github.com/switchball/AI-For-Bejeweled which will take the screenshoot from Bejeweled game. Those codes are no longer in use.
3. Change the need of feeding icon image array into the tensorflow
4. Create a play script that will play the trained model
5. Put those flags e.g  (demo = True) into the command arguement

THANKS
======
* Yichi Xiao, @switchball, the main contributor of the tensorflow code https://github.com/switchball/AI-For-Bejeweled
* Greg Schafer for the code using PyBrain https://github.com/grschafer/BejeweledBot
* Al Sweigart for his [Bejeweled implementation in pygame][bejeweled]                       
* Osmic for the [icons][gems] used in Al's game

[bejeweled]: http://inventwithpython.com/blog/2011/06/24/new-game-source-code-gemgem-a-bejeweled-clone/
[gems]: http://opengameart.org/content/gem-jewel-diamond-glass
