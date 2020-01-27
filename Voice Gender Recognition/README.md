# Voice Gender Recognition

a simple frequency domain analyser which recognizes if the voiced speech belongs to a male person or a female person.

How it works ?
--------------

The voiced speech of a typical adult male will have a fundamental frequency from 85 to 180 Hz, and that of a typical adult female from 165 to 255 Hz. Thus, we can use spectral properties of a given wav file to determine the voice gender.

Future Works
------------

in this project i've used the max frequency property to classify the voice. but for example this properties can be fed to a neural network classifier for better results. 
also this classifier assumes the audio file contains only human voice which is a tough assumption. in future works we can detect and extract the human voice from the mixed audio file which makes the classifier more robust and more resilient to ambient noise.