# Logistic Regression Case Study ([CS109_2015](https://github.com/cs109/2015lab5))

![python](http://ForTheBadge.com/images/badges/made-with-python.svg)
![jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)

<p align="center">
	<img src="https://miro.medium.com/v2/resize:fit:828/format:webp/0*p3B6NfsIRMGvXkK9.jpg" alt="400" width="600"/>
</p>

Image taken from this [source](https://medium.com/analytics-vidhya/logistic-regression-46a0f3cdecef). A great [Medium](https://medium.com/) article on Logistic Regression byt the way.

This case study delves into the math behind logistic regression in a Python environment. We've adapted this case study from [Lab 5 in the CS109](https://github.com/cs109/2015lab5) course. Please feel free to check out the original lab, both for more exercises, as well as solutions.

In this notebook, we turn our attention to **classification**. Classification tries to predict, which of a small set of classes, an observation belongs to. Mathematically, the aim is to find $y$, a **label** based on knowing a feature vector $\x$. For instance, consider predicting sex from seeing a person's face, something we do fairly well as humans. To have a machine do this well, we would typically feed the machine a bunch of images of people which have been labelled "male" or "female" (the training set), and have it learn the sex of the person in the image from the labels and the *features* used to determine sex. Then, given a new photo, the trained algorithm returns us the sex of the person in the photo.

