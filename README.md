MATHEMATICAL FOUNDATION – MINI PROJECT
1. We know that speech signal is one dimensional vector. Different vector transformations can be applied on the speech signal to enhance its quality. Explore the following vector transformations on the speech signal.
1. Record your voice signal for 30 seconds (speak slow and record) and play it in python.
2. Print the shape of the signal. Is it a 1D vector ?
3. Plot the signal. Can u able to roughly tell how many words/sentences spoken?
4. Take only the first 15 seconds of your speech signal 
5. Down sample the speech vector by 2 (Pick one sample for every two sample)
6. Upsample the speech vector by 2 (Introduce one sample newly between every two sample)
7. Apply the following transformations on the speech signal and try to hear to
	a. 3*Speech signal
	b. 0.5*Speech signal
	c. exp(0.5*speech signal)
	d. ln(speech signal)
	e. Cos (Speech Signal)
	f. Speech signal + normal_random_noise of same length of speech signal

2. We know that image is a 2D data, which is nothing but a matrix. Apply different matrix transformations on the following image.
 
1.	Is the cameraman coat have any packets in it ? Apply different transformations on this image to visually prove the answer for this question.
2.	Create the negative version of this image
3.	Rotate the image by an angles 45deg, 90 deg.
4.	Horizontally flip the image
5.	Zoom out the image using any matrix interpolation (up-sampling)
3. Lung_Feat.csv is a dataset of features extracted from the lung nodules(tumors). Refer the below article to understand about these features and its extraction process from CT scan.  https://www.scielo.br/j/babt/a/GCTFby9bSBLsynRm44hZYNB/?lang=en
This data consist of 24 columns, in which the first 23 columns are defining the tumor shape and texture characteristics. Apply the dimensionality reduction technique to derive the new fewer feature components to represent the original tumor characteristics without losing more than 5 percent of information. Also list the top 5 features in the first five principle components. 
