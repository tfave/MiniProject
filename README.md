# MiniProject
Textual entailment task - UiS data Mining project

This project is from a Kaggle competition already closed : https://www.kaggle.com/c/fake-news-pair-classification-challenge/data
This is a supervised task.

# Input
We will use at least these 2 datasets :

The first is from a Kaggle competition (already over).
Task: Fake News Classification
Given the title of a fake news article A and the title of a coming news article B, participants are asked to classify B into one of the three categories.
agreed: B talks about the same fake news as A
disagreed: B refutes the fake news in A
unrelated: B is unrelated to A

The second data set is described as follow :

In this paper we introduce a new publicly available dataset for verification against textual sources, FEVER: Fact Extraction and VERification. 
It consists of 185,445 claims generated by altering sentences extracted from Wikipedia and subsequently verified without knowledge of the sentence 
they were derived from. The claims are classified as Supported, Refuted or NotEnoughInfo by annotators achieving 0.6841 in Fleiss κ. For the first two 
classes, the annotators also recorded the sentence(s) forming the necessary evidence for their judgment. To characterize the challenge of the dataset 
presented, we develop a pipeline approach and compare it to suitably designed oracles. The best accuracy we achieve on labeling a claim accompanied 
by the correct evidence is 31.87%, while if we ignore the evidence we achieve 50.91%. Thus we believe that FEVER is a challenging testbed that will 
help stimulate progress on claim verification against textual sources.
Link to download the dataset : https://s3-eu-west-1.amazonaws.com/fever.public/fever2-fixers-dev.jsonl

#Expected output
The output will be the same format as the input used for training, a file with text entailment.

# Potential challenges
Build the right Neural Network model. Deal with acccuracy.

Use of deep learning ?
Not enough knowledge on the topic at the time of writing the readme.

# Roles in the project
To be determined

