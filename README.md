## Types of Chat Bot's:
In the world of machine learning and AI there are many different kinds of chat bots. Some chat bots are virtual assistants, others are just there to talk to, some are customer support agents and you've probably seen some of the ones used by businesses to answer questions. For this tutorial we will be creating a relatively simple chat bot that will be be used to answer frequently asked questions.

## Install Packages:
Before starting to work on our chatbot we need to download a few python packages. Please note as of writing this these packages will ONLY WORK IN PYTHON 3.6. Hopefully this will be fixed in the future.
We will simply use pip to install the following:
- numpy
- nltk
- tensorflow
- tflearn

Simply go to CMD and type: pip install "package name". Where you will replace "package_name" with all of the entries listed above.

## Training Data
Now it's time to understand what kind of data we will need to provide our chatbot with. Since this is a simple chatbot we don't need to download any massive datasets. We will just use data that we write ourselves. To follow along with the tutorial properly you will need to create a .JSON file that contains the same format as the one seen below. I've called my file "chatbot.json".

## Steps involved in the project:
- Loading our JSON Data
- Extracting Data
- Word Stemming
- Bag of Words
- Developing a Model	
- Training & Saving the Model
- Loading a Model
- Making Predictions	

#### *Steps to run the project are clearly mentioned in the .ipynb file*
#### Bakery.json
##### A new file bakery.json has been created so as to use the chatbot for any bakery:
- To use the bakery.json fie just change the name of the cell containing chatbot.json to bakery.json and use *The bakery* chatbot.
#### *Link to .json file:- [Click Here](https://drive.google.com/file/d/1XuVUIM2-DWA5IgxoSllJ7gx3kNHF6iV3/view?usp=sharing)*

