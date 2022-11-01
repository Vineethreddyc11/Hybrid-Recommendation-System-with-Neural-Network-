
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


## Content-Based

This type of recommendation works by comparing video attributes to suggest similar videos that share those same attributes. The technical term for this recommendation is cosine similarity in this case. Think of the video’s attributes like duration, sound, and text. These features can be used to recommend videos that share similar attribute values.

-**Example:**

`duration — 30 seconds long`

`hashtags — #coaster #rollercoaster #themepark #disneyworld`

## Collaborative-Filtering

This type of recommendation works by comparing you to others. So, if you are new to the app and start liking or rating a video highly (in another use case), you will start to see recommended videos. Those videos are the videos that other people like, who also liked the same past videos of you. This type of recommendation is technically referred to as alternating least squares — and matrix factorization.

-**Example:** If person A likes and comments on videos 1, 2, 3, 4, and 5, and person B likes and comments on videos, 1, 2, and 3, they will tend to like videos 4 and 5. Another way to visualize this example is the following (X being the recommended video similar to 4 and 5 from above).




