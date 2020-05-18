# Judging a book by its cover

## Project Overview

In this work, we employed 3 machine learning techniques to study the relationship between book covers and their popularities. We first trained a classification model using a Convolutional Neural Network (CNN) to predict the popularity level given a resized and randomly cropped 120 * 120 image input of the book cover. Second, we implemented an interpretation algorithm called Local Interpretable Model-Agnostic Explanations (LIME) to extract patches in the image to explain the prediction result. Finally, we explore Generative Adversarial Network (GAN) to generate the most popular cover by machine itself. We found that our classification model suffers from overfitting, and thus, we in general fail to conclude a clear relationship between book cover and popularity. However, given a specific instance, LIME extracted reasonable features to explain the result. And finally, our GAN is able to provide some general tips of what popular book covers have. 

## Project Walkthrough



