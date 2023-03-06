# **AI Lab for Wireless Communication**
This repository contains the projects and assignments for the course AI Lab for Wireless Communication. This course is designed to explore the applications of artificial intelligence and machine learning in wireless communication systems.

## **Projects**
The following is a list of projects included in this repository:

- ### [Introduction to AI Algorithms for Channel Decoding](./Introduction%20Uncoded%20System/)
    ##### 2023-02-13
    Introduction to the lab, its tools and programming environment.

- ### [Traditional Channel Decoding Algorithms](./Syndrome%20Decoding%20%20Maximum%20Likelihood%20Decoding/)
    ##### 2023-02-20
    Exploring two common decoding algorithms: **syndrome decoding** and **maximum likelihood decoding**. Syndrome decoding is a method for error correction that involves calculating the syndrome of the received codeword and using it to correct any errors. Maximum likelihood decoding is a more advanced decoding algorithm that uses statistical inference to determine the most likely transmitted codeword.

- ### [Channel Decoding as Classification: Support Vector Machine](./Support%20Vector%20Machine/)
    ##### 2023-03-06
    Support Vector Machines (SVMs) are a type of machine learning algorithm that can be used for classification. In the context of channel decoding, the goal is to classify the received signal into one of the $2^4 = 16$ possible information messages. One approach is to use the one-versus-one method, which involves training the SVM ${{16}\choose{2}}$ times on each pair of possible classes.

## **Requirements**
To run the code included in this repository, the following software and tools are required:

- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib
- scikit-learn
