# celebrity-face-detect
I have used Python, TensorFlow and OpenCV to create a Machine Learning Model a to identify celebrities. 
I first selected the sport celebrities i want to create a classifier for, then gathered the relative images. 
Then imported the required packages of numpy, OpenCV and matplotlib, for converting, visualizing and plotting puprposes in respeective order.
I visualized a few images, to just look over and apply the gray scale filter. Then I used harrcasdes to figure out face region in the selected image.
Then wrote a function that will return cropped facial images from the complete image, if the face detected has two eyes only.
Passed all the images under the specific classes, and then saved the cropped images into a cropped_celeb_name folder.
Then perfromed Feature Engineering, I used wavelet transform to properly understand the dimensions of each and every part of the face for better classification.
Then stacked the raw_cropped image on top of the wavlet_img.
Finally converetd the lsit of stacked images into an np.array.
Imported the necessary modules required for creating the model, first splitting the train data and test data.
Using GridCV to understand the proper parameters in all models.
Then using the best parameters to run the models on the testing data.
Plotting the confusion matrix to properly see where my model has gone wrong, and where i can make changes.
