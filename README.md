# Engagement_Attention_Detector

## Contributors
 Jai Jindal
 Shikhar Jain
 Lakshaya Agarwal
 Varun Kataria

## Inspiration
As students, we frequently find ourselves delivering online presentations, and wanting to gauge the quality and engagement of the same. Apart from this, as learners, we find ourselves losing focus during lectures. Despite knowing our shortcomings, it's inevitable that we run into them. Thus we chose to create an Attention and Engagement Monitor, using Deep Learning. Needless to say, this would definitely boost productivity by improving the attentiveness and effectiveness of content, not only for students, but across large scale companies as well.

## What it does
The project utilizes two tools in order to boost productivity by tracking and enhancing engagement and attention in the online setting. The first is the facial emotion recognition software. We designed a program that detects the user’s expression by creating a model using a convolutional neural network with Tensorflow, Keras, and Numpy in Python. The output is then displayed in real time on the device’s webcam using OpenCV modules. Secondly, we incorporated an eye tracker program that follows the line of sight of the user to check whether they are paying attention to their screen, with the help of OpenCv and DLib modules. The two functionalities are brought together using Streamlit for the frontend.

## How we built it
First, we obtained the required data using the ‘fer2013.csv’ dataset on Kaggle, consisting of over 34,000 values in pixel data format. Using Numpy functions, we normalized the data and divided it into training and testing classes. We then used supervised machine learning to perform classification of facial expressions by implementing a convolutional neural network. We trained the machine learning model with our fitted data.

Subsequently, we used Opencv to access the integrated camera in the PCs to process the facial movements of individuals while the Tensorflow model we created classified them into the actual facial expressions of the person. By compiling this data for the entire audience we can assess the overall reaction to each and every part of the presentation, lecture, or meeting.

Additionally, we have used an eye tracking algorithm to classify whether or not a person is looking directly at the screen. To implement this, we utilized the DLib module while referring to an open source program for a small part of the implementation. Through this, we can get an idea of the attentiveness of the individual. By compiling this data for the entire audience, we obtain the overall interest in the presentation.

By combining these two using streamlit as the front end, we display statistics on the individual's engagement and attentiveness. These can then be individually catered for the corresponding parties and purposes.

## Uses and What's next for Engagement and Attention Detector using Deep Learning
We plan to implement this software in corporations as well as education. In universities/self-paced courses, the feedback from the data will be given to the student for self-improvement. By viewing this data, students can revisit the parts where they lost interest and hence improve learning and productivity.

In schools, the data about the overall lecture will be provided to teachers. Additionally, the data about some of the most inattentive students will also be attached so that special needs, if any, can be detected and addressed even in the remote learning scenario. Teachers can also use this data to improve upon the quality of the lecture for a particular topic where his/her students lost interest.

In corporations, the data will be provided to the presenters/meeting hosts to assess the quality of presentations and pitches by viewing the overall reaction of the audience. They can use this to avoid presenting the same monotonous briefing to others. Instead they can enhance these presentations to throw emphasis on relevant portions and ultimately increase efficiency. Further, the application can be used to check employee’s productivity during meetings. This product can be scaled up by integrating it into existing platforms for virtual meetings such as MS teams, Zoom, Google Meet etc.

## Challenges we ran into
Learning new skills and applying them in a short period of time in order to implement our idea was quite challenging. We kept running into numerous errors, and had to debug each section of the code every step of the way. Lastly, implementing different module functionalities together into one project posed technical difficulties which took a while to work past.

## Accomplishments that we're proud of
We believe that this project will be a positive step toward revolutionizing remote work by providing comprehensive data to companies / individuals regarding their attention span during long meetings / presentations/ lectures. It will allow companies to become learning organizations that can save precious man hours and boost productivity by eliminating parts of their meetings that garner no interest from the audience. We are proud of the coding and technical skills we acquired while trying to finish this project. Additionally, we gained a lot of experience to work under time constraints. With the short time we had we learned time management and efficient teamwork.

## What we learned
We learned about the psychology of the human mind. As this was complex yet crucial to our project, guess work could not take us too far. We explored the realm of machine learning,a tool so powerful yet so easy to use, which left us in awe with the sheer potential it displayed. We were simply amazed by the pace at which this technology has been evolving.
