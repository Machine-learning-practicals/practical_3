# Practical 3

Keywords: Unsupervised Learning, Mixture Models

For this practical, the goal is to predict people’s tastes in music. Specifically,
we need to predict the number of times (a non-negative integer) different users
listened to tracks of different artists over a span of time. We are given some basic selfreported
demographic information about many, but not all, of the users, such as sex, age,
and location. In addition, we also have the name of the artist and their MusicBrainz1 ID, if
available. There are about 233,000 users and 2,000 artists. The training set has over 4.1M
user/artist pairs and the test set is of a similar size. The objective is to predict how many
times a user will listen to a new artist.
