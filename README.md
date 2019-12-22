The code in face3.py was based on documentation from https://pypi.org/project/face_recognition/ , tested and 
performing quite well face recogntion project. Requirements are quite complex.
Face recogntion part works quite well in selected Amarcord scenes ( I took 30 scenes ) and few scenes from City of Women.

I tried to utilize code from library  documentation and it worked quite well (from description view). 
Not much documentation exists how the algorithm was developed
but it works. Scenes for recognition are placed destdir = '/home/pete/face/scene1', found faces are in the cuts directory.

The faces can be processed further for emotional content.


I tried to utilise already built models for emotional content from articles and the links from the 
https://towardsdatascience.com/face-detection-recognition-and-emotion-detection-in-8-lines-of-code-b2ce32d4d5de.
Models are based on CNN, based on tens of 000s faces.
But I could not load the developed model into keras. So emotion recognition part does not work and was commented out.