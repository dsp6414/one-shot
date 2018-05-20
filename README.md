# one-shot using Siamese Networks
##### in pytorch 0.4.0
## Dataset
the data is taken from  AT&T faces dataset.
http://www.cl.cam.ac.uk/research/dtg/attarchive/facedatabase.html

The dataset contains images of 40 subjects from various angles
The size of each image is 92x112, 8-bit grey levels. 
The images are organised in 40 directories (one for each subject) named as:
    sX
where X indicates the subject number (between 1 and 40). In each directory
there are 10 different images of the selected subject named as:
    Y.pgm
where Y indicates which image for the specific subject (between 1 and 10).

this architecture is given an input pair , along with the label (similar/dissimilar). and them it gives result in form of Dw value. A high value of Dw indicates higher dissimilarity. as shown in result folder.
for more details the ppt file is also attached.

