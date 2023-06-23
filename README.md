# Comment-Toxicity-Detection
## A Comment Toxicity Model with Deep Learning and Python. LSTM model used 
## About Project:
This project is broadly divided into two sections: the Resume Parser and then the Classifier .This project is aimed at building a multi-label classification model using the principles of Deep Learning and NLP to effectively classify users into job categories given their resume.
For the Resume Parser, the raw text will be extracted from resumes and blocks would be isolated along with the separation of entities. 
The model classifies an input resume into categories of IT jobs, a resume can belong to multiple categories.Since this is a multi-label classification problem we will pre-process the text using NER(Name Entity recognition) and use different model architectures like DNN,CNN,LSTM and Bert CLassifier to predict the final class. 

## Business Use case:
*   Our deep learning project can be used by users to find the job description as per their resume.
*   What kind of job might be the most appropriate and where the seekeers could find them is the base problem we are trying to solve. 
*   It can be used by companies with heavy work-loads to pass the candidate resumes through our application to check what all IT roles a certain resume fits into.
*   Creates an executive or management summary that recruiters may use to evaluate candidates by reading. It enables you to quickly arrange the resumes of the candidates. 
*   It takes less time to assess and pick the most relevant talent who is a good fit for your business.


## Model
### LSTM Neural Network

## TechStack Used(Python Libraries):
* BeautifulSoup4
* Flask
* Keras_Preprocessing
* Nltk
* Pandas
* Pdfminer
* Spacy
* Tensorflow
* Werkzeug

## Instructions to run

Loss over epochs

![Loss](https://github.com/ligandro/Comment-Toxicity-Detection/assets/97714265/035a3a25-3f48-4d63-84e4-58a90c0b08ae)

Gradio interface

![Screenshot 2023-06-23 at 9 31 40 PM](https://github.com/ligandro/Comment-Toxicity-Detection/assets/97714265/698a3e15-f45e-43b3-837e-6a70321510d8)
