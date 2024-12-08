# Machine-Learning-Assesment
Image Classification to diagnose wheat crop pest diseases that can be deployed and used by small holder farmers on web platform


#Business Understanding
Smallholder Commercial Wheat Farmers are in need a diagnostic tool to detect, diagnose and
treat wheat crop pests and diseases to prevent yield reduction. and the main goal of this project
is to develop an accessible,accurate and easy to use diagnostic tool that empowers smallholder
wheat farmers to detect,diagnose and treat pests and diseases early,therby minimizing and
improving productivity

#Data Understanding
This dataset is designed to empower researchers and developers in creating robust machine
learning models for classifying various wheat plant diseases. It offers a collection of highresolution images showcasing real-world wheat diseases without the use of artificial
augmentation techniques.

#Problem Statement
Smallholder wheat farmers face significant challenges in identifying and managing pests and
diseases due to limited access to timely and accurate diagnostic tools. This results in delayed
interventions, reduced crop yields, and economic losses. There is a need for an affordable, userfriendly solution that provides real-time diagnosis and actionable treatment recommendations
to help farmers mitigate these issues effectively

#Main Objectives
Early detection devlops a diagnostic tool that identifies wheat crop pests and diseases at an
early stage to prevent significant damage
Accurate diagnosis leverage image classification technology to ensure high accuracy in
identifying specific pests and diseases affecting wheat crops


Actionable treatment recommendations provides tailored, practical, and easy-to-implement
treatment suggestions to farmers.
Accessibility designs a user-friendly web platform that is affordable and usable in low-resource
settings, including areas with limited internet connectivity.
Farmer empowerment will help equip smallholder farmers with technology to make informed
decisions, reducing dependency on external experts.
Increased productivity may minimize yield losses by enabling timely interventions, leading to
improved crop performance and farmer incomes.
Sustainability promotes targeted pest and disease management to reduce the overuse of
chemicals, fostering environmentally sustainable farming practices


#Understanding the dataset
This dataset is designed to empower researchers and developers in creating robust machine
learning models for classifying various wheat plant diseases. It offers a collection of highresolution images showcasing real-world wheat diseases without the use of artificial
augmentation techniques.


#Exploring the dataset and coming up with visualizations
By exploring the dataset we gain insights into its structure, sample images, class distribution,
and image properties. This understanding helpes in making informed decisions when
preprocessing the data and training our model.



#Data Preprocessing
This step involves preparing the data for the model an also includes tasks
like resizing images, normalizing pixel values, data augmentation, and splitting the data into
training and validation

#Model Architecture
Building a Convolutional Neural Network (CNN) model. A simple model might consist of several
convolutional layers followed by pooling layers and a few dense layers.
Evaluate the model on the validation and test sets to assess its performance. Monitor metrics
such as accuracy, loss, precision, recall, and F1-score


#Conclusion
Based on the execution time which decreases each time a new model is executed and the
accuracy becomes better each time hence boosting performance.
The best model is the ResNET50V2, which has nalidation accuracy of 0.9281 and took the
shortest execution time of 1hr 30min 10 secs.
The least was Baseline model and the second improved model was complex architecutre.
Early Stoping model helped in minimizing overfitting hence boosting performance.

#Recomendations
Based on the evaluation results we recommend ResNET50V2 as the primary model of wheat
plant diseases.This model has exhibited the best overall performance,striking a balance
between high accuracy,precision, and low loss.Its intergration the specific wheat diseases and
imaging analysis systems can significantly enhance the speed and accuracy of the
diseases,ultimately leading to improved yeald outcomes and more efficient produce


