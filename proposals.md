# Capstone 2
---
## Proposals
1. Train a model to predict if a face is computer generated or a real person.
2. Train a model to predict an emotion based on a photo.
3. Train a model to predict what language text is in a photo.
4. Train a model to predict if a job description is for a Data Science role or Data Engineer role based on its content.

---
## Real or Fake
### Description
Nvidia has been using a GAN(generative adversarial network) to produce realistic faces of people that never existed.
The purpose of this experiment is to see if a model can be trained to predict if a face was generated or real, and 
if it can identify fake images more often than a human counterpart.

### Approach
This project will start with a neural network to train on real and fake faces, but may adjust according to EDA. Known
data sets will be collected or generated of real and fake images to train and test on with a holdout test dataset for 
the final result

### Interaction
The late stage goal of this project is to allow a person to challenge themselves on the same dataset and compare the 
results against the trained model. This will be accompanied by a markdown notebook detailing steps, EDA, and development
or discoveries. 

### Data Sources
https://thispersondoesnotexist.com
Datasets from similar GAN projects like:
- https://github.com/NVlabs/stylegan2
- https://github.com/lucidrains/stylegan2-pytorch

---
## Emotions
### Description
This model will be built to predict the emotion or no emotion displayed in a photo. It should be able to classify basic 
emotions like happy, sad, angry, or none.

### Approach
This project will start with a neural network to train on classified stock photos of emotions. The model method might
change based on early or late EDA to maximize success rate. A quick comparison of model performance is an end goal. 

### Interaction
The late stage goal would be an interface for a user to upload their photo, or predict in real time through a device's 
camera to have the model predict the current emotion displayed. Steps, progress, and ultimate results will be 
documented in a mark down notebook and slides to present the project in detail and quickly respectively. 

### Data Sources
Stock photos and possible API's such as:
- Emotient
- Affectiva
- EmoVu
- Nviso
- Kairos
- Project Oxford by Microsoft
- Etc.

---
## What language?
### Description
Real time processing of translating languages has already been developed, but the current versions are far from perfect.
This project aims to start the process by identifying the written language in a photo with an expanding goal to cover as
many written languages as possible. 

### Approach
This project will use NLP and a neural network to train and identify what language is present in an image. Data will be 
collected from existing sources or compiled from generic images of articles, books, or even street and shop signs.

### Interaction
The late stage goal of this project is to either take a photo of writing or use a camera to process in real time what 
language is seen. Steps, progress, and ultimate results will be documented in a mark down notebook and slides to present
the project in detail and quickly respectively.

### Data Sources
Images including text from all over the world. Python's langdetect, textblob, and langrid will be investigated for 
classification

---
## Data Job predictor
### Description
Data Scientists entry level positions typically go down either the path of Data Science or Data Engineering. One is 
focused more on the analysis of data, and the other focuses on the programming of the underlying structures for the data
and models. Based on job posting description, this model will try to predict if the posting is for a Data Science role
or Data Engineer role.

### Approach
This project will use NLP to process job descriptions collected from job search websites and try to identify key language
to determine the role of the job without using the job title. Steps, progress, and ultimate results will be documented in a mark down notebook and slides to present
the project in detail and quickly respectively.

### Interaction
A late stage goal for this project is to collect key buzz words in job descriptions that should be included depending if
the job seeker is looking for a Data Science role or Data Engineering. 

### Data Sources
Job descriptions will be gathered from LinkedIn, Monster, Glassdoor, and other job posting websites.
