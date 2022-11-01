
# Hybrid Recommendation System with Neural Network 

Built hybrid recommendation system by combining **Content-Based (Video Information), Collaborative Filtering (User Interaction)**, and **Knowledge-Based (Personal information)** for recommending videos and movies to the user.

![20d38e00-6634-11eb-9d1f-6a5232d0f84f](https://user-images.githubusercontent.com/68578215/199301101-063ad901-4328-4770-bb51-89f51d5c45ec.jpeg)


**Recommendation Systems:** Recommendation Systems are models that predict users’ preferences over multiple products. They are used in a variety of areas, like video and music services, e-commerce, and social media platforms.

The most common methods leverage product features (Content-Based), user similarity (Collaborative Filtering), personal information (Knowledge-Based). However, with the increasing popularity of Neural Networks, companies have started experimenting with new hybrid Recommendation Systems that combine them all.

## Project Flow

- Setup: import packages, read data, preprocessing
- Solving Cold Start problem
- Content-Based methods with tensorflow and numpy
- Traditional Collaborative Filtering and Neural Collaborative Filtering with tensorflow/keras
- Hybrid (context-aware) model with tensorflow/keras


## Cold Start Problem

When a user (or a product) is new, then there will be a  Cold Start problem. The system is unable to form any relation between users and products because it doesn’t have enough data.

In order to solve the problem, the primary technique is the Knowledge-Based approach: for example, asking for user’s preferences in order to create an initial profile, or using demographic information (i.e. high school shows for teenagers and cartoons for kids).

If there are only a few users, one could work with Content-Based methods. Then, when we have enough ratings (i.e. at least 10 products per user and more than 100 total users), more complex models can be applied.



