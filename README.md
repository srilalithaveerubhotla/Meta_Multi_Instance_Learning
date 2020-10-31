# Meta_Multi_Instance_Learning

### Implemented Multi Instance learning on NLP Task 
## [Reffered Link](https://colab.research.google.com/github/zphang/zphang.github.io/blob/master/files/notebooks/Multi_task_Training_with_Transformers_NLP.ipynb#scrollTo=IWKTZxcjFPnS)

### Data set has 3 different tasks 
#### 1. STS-B: A two-sentece textual similarity scoring task. (Prediction is a real number between 1 and 5)
#### 2. RTE: A two-sentence natural language entailment task. (Prediction is one of two classes)
#### 3. Commonsense QA: A multiple-choice question-answering task. (Each example consists of 5 seperate text inputs, prediction is which one of the 5 choices is correct) 


### Implemented Meta Learning using Reptile in Keras 
##[Reffered Link](https://keras.io/examples/vision/reptile/)

### This code uses Omniglot dataset 
#### Omniglot dataset consists of 1,623 characters taken from 50 different alphabets, with 20 examples for each character. The 20 samples for each character were drawn online via Amazon's Mechanical Turk. For the few-shot learning task, k samples (or "shots") are drawn randomly from n randomly-chosen classes. These n numerical values are used to create a new set of temporary labels to use to test the model's ability to learn a new task given few examples. In other words, if you are training on 5 classes, your new class labels will be either 0, 1, 2, 3, or 4. Omniglot is a great dataset for this task since there are many different classes to draw from, with a reasonable number of samples for each class.
