we have 218823 test images
        401059 train images

! unbalanced target
0    400666
1       393

Combine images with labels

iterate through images
assign each image to specific row from metadata

'Strongly-labelled tiles' are those whose labels were derived through histopathology assessment. 'Weak-labelled tiles' are those who were not biopsied and were considered 'benign' by a doctor.

TODO
* create dataloader
* train simple model and test it
* increase amount of malignant records
        * augmentation
        * data from another dataset