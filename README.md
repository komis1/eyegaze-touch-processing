# eyegaze-touch-processing
Jupyter Notebook (Python) to process openly released eyegaze and touch data 

Here you can find code to process data from Jiang et al.'s paper [1] titled "How We Type: Eye and Finger Movement Strategies in Mobile Typing". Although the paper promised the availability of data and related processing code, only the data is currently available from the authors' website (see https://userinterfaces.aalto.fi/how-we-type-mobile/)

The scripts are used to:
a) clean out abnormal values
b) transform gaze coordinates, since a large proportion falls outside the device bounds
c) implement an unsupervised-learning algorithm to detect attention shifts from the keyboard area, to the text editing area.

For convenience, sanitised version of the data is also provided (zip csv file) - this includes data after the following filters:
- gaze x shifted by 460px
- remove data with a negative timestamp
- remove gaze data for sentences which do not have corresponding typing data


[1] Jiang, X., Li, Y., Jokinen, J. P. P., Hirvola, V., Oulasvirta, A., & Ren, X. 2020.How We Type: Eye and Finger Movement Strategies in Mobile Typing.In Proceedings of the 2020 CHI Conference on Human Factors in Computing Systems (CHI ’20).
