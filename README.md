## Facial-expression-recognizer
Facial expression recognition is a technology which uses biometric markers to detect emotions in human faces.   
The six basic universal expressions: -   
Happiness, Sadness, Anger, Surprise, Fear, and Disgust.
Because facial expressions convey nonverbal communication cues that play an important role in interpersonal relations.  
These cues complement speech by helping the listener to interpret the intended meaning of spoken words. 

## Use Cases - 
### 1.Market Research
Traditionally market research was done by conducting surveys to find out what consumers want and need, the methods involved employing people to observe reactions of customers while interacting with a brand or a product.   
Facial expression recognition can save the day by allowing companies to conduct market research and measure moment-by-moment facial expressions automatically, making it easy to aggregate the results.
### 2.Gaming Industry
Facial expression recognition can also be used in the video game testing phase.  
A focused group of users are asked to play a game for a given amount of time and their behavior and emotions are monitored.   
By using facial expression recognition, game developers can gain insights and draw conclusions about the emotions experienced during game play and incorporate that feedback in the making of the final product.
### 3.Behavioural Testing
Suppose you have built some product and want to understand the genuine feedback of your customer on it, then you can  incorporate facial expression recognition on your product which keeps tracking customer’s emotions.   
It makes it easy to capture a few expressions like sadness , happiness or surprise while they walk through your product. 

## Various Approaches to Improve Training
#### 1.Performing face detection and cropping face images in our training dataset.   
  Although we have closely cropped faces in our dataset, they are very noisy.    
  By filtering out all images which were not detected by face detection algorithm we can make our model more robust.
  
#### 2. Increase Number of phases and Decrease number of epochs per phase while training.
For example:   
You can train a model using a phase 1 with 6 epochs repeated by phase 2 with 4 epochs for 2 times.

#### 3. Try out a better version of EfficientNet.
There are even better versions of EfficientNet such as B3 to B7.  
We have used EfficientNetB2 just to keep it less computationally intensive.  
So that it can be executed even on Low hardware specification. 

















