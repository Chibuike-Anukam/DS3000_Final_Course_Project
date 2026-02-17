# Parking-Spot Finder - Updated! 

This is not an entirely new project, but a continuation of my Real-Time Parking Spot Finder project [https://github.com/Chibuike-Anukam/Real-Time-Parking-Spot-Finder.git](url). 
To recap anyone who isn't familiar with the Real-Time Parking Spot Finder project, it started as a hackathon at my university. We had to create a real-time parking spot detection application that
incorporated computer vision. It also had to use an AI model that was trained on a dataset to predict (via object detection) which parking spots were vacant or occupied, and inform the user through a web-based 
interface. My team wasn't able to complete it, mostly because we had no idea what we were doing. But I wanted to see it through. Fortunately, in the first semester of my third year of university, I took a course 
on machine learning, which included how to train AI models. For the final course project, we had to train a model to solve a real-world problem. I saw this as an opportunity to finish the hackathon task, and with 
the help of my groupmates, we were able to get a near-perfect model. 
The report summarizing our findings is also in this repo as well.

## Pros: 
The model had 99.9% accuracy when we tested it on images from the test set to evaluate its performance

## Cons: 
This extremely high accuracy was likely due to the similarities between the images in the train, validation, and test sets. 
After the 100 epochs of training that we did, the model had memorized the data (our training loss was about 0.2) and was overfitting. 
As a result, when we tested it with sample images, it had no problem since the image was very similar to the ones it was trained on. 

## Next Steps: 
We would need to retrain the model on a more diverse dataset. The one that the organizers of the hackathon provided had images with the same lighting and from similar camera angles. 
With a diverse dataset, it would be harder for our model to memorize the dataset and thus better generalize so that it could, hopefully, perform well on a variety of different parking lots in various conditions.   

Initially, I wanted to actually deploy this project. My goal was to first partner with local businesses and public places and set up cameras in their parking lots. If the small-scale version works, scale up 
by working with the municipality (city leaders) to have this system installed city-wide. But I realized that would require me to get access to security cameras, and I wasn't sure my city leaders would agree. 
So, unfortunately, I decided to stop this project. 
But not all is lost! I used the learning experience from this project to help me with another AI-model training project, which I will add to my GITHUB soon. 
This was just one step on my journey in AI. Although I may not be a data scientist or software engineer, I still want to learn how to utilize AI to solve real-world problems. 
I will stand by my belief: AI IS A TOOL! We need to stop using it as an easy way out and use it enhance all aspects of our lives, from learning to building solutions.
AI was made for us. To be used by us. And not to replace us.  
