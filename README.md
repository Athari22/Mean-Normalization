# Mean Normalization 
This project is a learning project from the [udacity](https://www.udacity.com/course/programming-for-data-science-nanodegree--nd104) for the Programming for Data Science with Python Nanodegree Program.

# Description
In machine learning we use large amounts of data to train our models. Some machine learning algorithms may require that the data is normalized in order to work correctly. The idea of normalization, also known as feature scaling, is to ensure that all the data is on a similar scale, i.e. that all the data takes on a similar range of values. For example, we might have a dataset that has values between 0 and 5,000. By normalizing the data we can make the range of values be between 0 and 1.

In this lab, you will be performing a different kind of feature scaling known as mean normalization. Mean normalization will scale the data, but instead of making the values be between 0 and 1, it will distribute the values evenly in some small interval around zero. For example, if we have a dataset that has values between 0 and 5,000, after mean normalization the range of values will be distributed in some small range around 0, for example between -3 to 3. Because the range of values are distributed evenly around zero, this guarantees that the average (mean) of all elements will be zero. Therefore, when you perform mean normalization your data will not only be scaled but it will also have an average of zero.

