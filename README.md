# MNIST Classification

Building a deep learning model for recognizing handwritten numbers using **Python**, **Tensorflow**, **Sklearn** and **Numpy**. 
This project is about using _non-negative matrix factorization_ for _weight initialization_ in autoencoders.

<br />

<p align="center">
  <img src="https://static.packt-cdn.com/products/9781789344158/graphics/assets/e8c5f6fa-9522-4fc2-b1a8-f10d4e451148.png" alt="desc" width="400" />
</p>

## Execute

Using jupyter notebook:

```shell
jupyter notebook
```

<br />

## What is this project about?

Autoencoders are a specific form of Neural Networks build by two parts. 
First part is used to encode the input data to a space with lower dimension and the second part decodes the abstracted data to reconstruct the input.

The networks is trained in a way that the reocnstructed data is very similar to the original input. 
This way we can make sure that we are transferring enough information to a small encoded space so that we are enable to reconstruct the entire image from it.

<br />

<p align="center">
  <img src="https://d1m75rqqgidzqn.cloudfront.net/wp-data/2020/04/29201743/Blog_info_29-04-2020-R-01-1024x438.png" width="400" alt="encoder" />
</p>

<br />

## MNIST Classification

The MNIST dataset is an acronym that stands for the Modified National Institute of Standards and Technology dataset. 
It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9.
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits 
that is commonly used for training various image processing systems. 
The database is also widely used for training and testing in the field of machine learning.

<br />

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFqulUlpB8FRxcskZtjySqNj_r71cjowz_mnZZG-yqnw&s" alt="mnist" width="300" />
</p>
