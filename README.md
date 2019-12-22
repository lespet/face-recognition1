The code in face3.py was based on documentation from https://pypi.org/project/face_recognition/ , tested and 
performing quite well face recogntion project. Requirements for installation are quite complex.
Face recogntion part works quite well in selected Amarcord scenes ( I took 30 scenes ) and few scenes from City of Women.
These were not random sceenes but most memorable for me.

I tried to utilize code from library  documentation and it worked quite well (from description view). 
Not much documentation exists how the algorithm was developed
but it works. Scenes for recognition are placed destdir = '/home/pete/face/scene1', found faces are in the cuts directory.

The faces can be processed further for emotional content.
Faces are named by original name of scene and top pixel.
Results show that faces are detected, but do not expect too much when the scene has 100s of small faces and very unstructured, irregular 
background as in Amarcord. Should be tested on 000s from other movies.


I tried to utilise already built models for emotional content recognition from articles and the links from the 
https://towardsdatascience.com/face-detection-recognition-and-emotion-detection-in-8-lines-of-code-b2ce32d4d5de.
Models are based on CNN, trained on tens of 000s faces.
But I could not load the developed model into keras, it crashes. So emotion recognition part does not work and was commented out.
I would look for other projects for emotion recognition.