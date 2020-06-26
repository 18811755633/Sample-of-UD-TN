# Sample-of-UD-TN
UD-TN (Ultrasound Data-Thyroid Nodules) is a dataset of thyroid ultrasound images. 
Supported by Major Scientifc and Technological Projects for A New Generation of Artifcial Intelligence of Tianjin (Grant No. 18ZXZNSY00300), we
and Tianjin Medical University Cancer Institute and Hospital jointly built this
dataset. Specifcally, UD-TN contains 2000 ultrasound images of the thyroid,
of which 1400 are used for training and 600 images are used for testing. These
images are classifed into benign and malignant based on the results of fine needle
aspiration biopsy (FNAB).
There are 1012 benign images and 988 malignant images in UN-TN. At the same
time, the senior radiologists marked the size and location of the nodules in each
image. The specifc form is shown in Fig. 1. In addition, in order to facilitate
the evaluation of the model’s ability to predict small nodules, we selected 100
ultrasound images of nodules with a maximum diameter of less than 1 cm from
the testset to form a small nodule testset. 50 of them are benign and 50 are
malignant.

The folder “Sample of Traindata” contains 14 image samples for training, including 7 benign images and 7 malignant images.
The folder “Sample of Testdata” contains 6 image samples for testing, including 3 benign images and 3 malignant images.
The folder “Sample of Smalltest” contains 6 image samples of small noduels for testing, including 3 benign images and 3 malignant images.
