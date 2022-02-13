# Likhith_Portfolio
Data Science Portfolio

# Project 1 : Online Examination System using NLP
* It is a web application which is used by students to write both subjective and multiple-choice questions online.
* Usually descriptive questions are evaluated by the faculty but in this application answers are stored in the database and are evaluated using Natural Language Processing.
* NLTK library of python is used to code the algorithm.
* Stop Words(Articles,Prepositions etc) are removed from both the questions and answers to check whether the keywords are present in the answer or not.
* If the word is present in the answer then 1 is written in the respective cell or else 0 is written.
* Similarity between the answers written by the students and the answers that are stored in the database is calculated using the formula MA = (NY/NK)*MM
* Where MA : Marks scored by the student , NY : Number of keyword columns with value 1 , NK : Number of keywords in the question , MM : Maximum marks for each question.


![](/images/Exam.jpeg)
