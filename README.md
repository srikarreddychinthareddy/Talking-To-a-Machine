# Talking-to-a-Machine
This project was done by reference from the Research paper named below
                                Are You Talking to a Machine?
                Dataset and Methods for Multilingual Image Question Answering
                   by         
                     Haoyuan Gao1  ,  Junhua Mao2 , Jie Zhou1 Zhiheng Huang1 Lei Wang1,
                    Wei Xu1 , Baidu Research  ,   University of California, Los Angeles

                        INPUT                   |                   OUTPUT
                                                |
                We may give an image,           |            Trained model answers 
                and a question in text          |               the question in text.
DATA COLLECTION 

We used Flicker8k datset for the images and obtained question and answer pairs ,the  annotations are collected using Baidu’s online crowdsourc-ing server4 . 
To make the labeled question-answer pairs diversified, the annotators are free to giveany type of questions, as long as these questions are related to the
 content of the image. The ques-tion should be answered by the visual content and commonsense (e.g., we are not expecting to getquestions such as 
 “What is the name of the person in the image?”). The annotators need to give ananswer to the question themselves.


Variuous Stages include are 

==>  Data Cleaning
==>  Feature extraction
==>  Bulding model
==>  Training the model
==>  Testing or Prediction

Detailed explaination can be found in the Presentation "PPT" attched with the source code.
