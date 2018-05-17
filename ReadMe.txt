In this code, support vector machine is used to implement nuclear segmentation of breast cells. I use libsvm toolbox to generate a model with a training set of 32400 pixels in a 180x180 color image. Then use another picture to test this model.

The final result shows that accuracy is 82.6173% (26768/32400). That is to say, 26768 samples of the 32400 samples of the test set are correctly classified.

Because of the short time, both my training set and test set are small. In addition to this, I cannot find out why the parameters of the support vector machine are not displayed.At the moment I can only infer that it may be related to the version. Last but not least, I'm still exploring how to generate a picture from the SVM's results to more intuitively show the effect of the model.

Result:
Accuracy = 82.6173% (26768/32400) (classification)


Yubei
2018.5.17