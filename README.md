# eyegaze-touch-processing
Python scripts to process openly released eyegaze and touch data 

Here you can find code to process data from Jiang et al.'s paper [1] titled "How We Type: Eye and Finger Movement Strategies in Mobile Typing". Although the paper promised the availability of data and related processing code, only the data is currently available from the authors' website (see https://userinterfaces.aalto.fi/how-we-type-mobile/)

The scripts are used to:
a) clean out abnormal values
b) transform gaze coordinates, since a large proportion falls outside the device bounds
c) implement an unsupervised-learning algorithm to detect attention shifts from the keyboard area, to the text editing area.
