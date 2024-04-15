<h1> TRAFFIC-SIGN DETECTION</h1><br>
<h3> Libraries used in python:</h3><br>
<p>
  1. Pandas<br>
  2. Numpy<br>
  3.Maplotlib<br>
  4.Tensorflow<br>
  5. Keras<br>
  6. cv2<br>
</p>
<h3> What this project does?</h3>
<p> In the given data set there are 58 labels that include various speed limits and also traffic-signs<br>
    So the given cnn model trains the data in such a way that it identifies the sign<br>
    But the images for each label are in different sizes which calls the need for resize function<br>
    And for easier image detection I have defined the grayscale function. 
                                                                                            
</p>
<h3>
  My Model Architecture:<br>
  <p>
  1. 2 convolutional layers followed by a max pooling layer with filter size=60<br>
  2. 2 convolutional layers followed by a max pooling layer with filter size=30<br>
  3. Then i have added a flatten layer followed by a dense layer with 500 filters<br>
  4. I have used adam optimizer with leanring rate=0.001 and categorical cross_entropy as my loss 
  </p>
</h3>
<p>
  Then I inputted the test data using the os directory command and then used the model to test it on the data
</p>
