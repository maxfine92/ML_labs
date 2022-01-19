# ML_labs
Several labs for "Modern control theory and artificial intelligence systems" course.

1. Text similarity.
You are given a set of sentences  from Wiki. Each of them has a "cat theme" in one of three senses:
• cats (animals)
• UNIX utility cat for listing the contents of files
• versions of the OS X operating system named after the cat family
Your task is to find two sentences that are closest in meaning to the one in the very first line. As a measure of similarity in meaning, we will use the cosine distance. 

2. We will find an approximation of a function by a polynomial by solving a system of linear equations. 
![image](https://user-images.githubusercontent.com/67582707/150068835-890947c1-b123-4735-a4bd-eb11e7b215f1.png)

3. Lab 3 has three tasks (from simple to hard):
a) Weights-heights dependency determination
![image](https://user-images.githubusercontent.com/67582707/150068980-8a902829-5401-405f-972e-1d04aa78170f.png)

b) Determination the dependencies between the company earnings and the marketing strategy it makes.
You will find MSE using stochastic gradient descent.
![image](https://user-images.githubusercontent.com/67582707/150069235-7ccd85eb-43c2-4180-bda4-535aa4499e90.png)

c) Determination the dependency between the bikes rent and various conditions (weather, holidays, etc.).
You will determine the linear dependent features:
![image](https://user-images.githubusercontent.com/67582707/150069452-de64fa30-337f-4346-b905-b1ecfe59a044.png)
and learn the difference between Lasso and Ridge regression:
![image](https://user-images.githubusercontent.com/67582707/150070277-598d90e1-7e38-4b5c-bd26-f6a07eaeb0e0.png)

4. The goal of the assignment is to implement the simplest classifier - the nearest neighbor method, and to compare the performance of the 1NN you implemented with RandomForestClassifier from sklearn on 1000 trees. 

5. Banners clusterization.
Let's imagine that the international cruise agency "Carnival Cruise Line" decided to advertise itself with the help of banners and turned to you for this. To test whether such banners are of great use, only 20 of them will be placed around the world. You need to choose 20  locations for placement so that the benefit is great and the agency continues to cooperate with you. 
Here we will use mean shift method:

![Alt text](https://github.com/maxfine92/ML_labs/tree/main/5.%20Кластеризация%20баннеров/mean_shift_2.gif)


6. In Credit scoring task we will learn how the mathematical statistics work (hypothesis testing particularly).
E.g., the dependency of credit default on the age of the clients:
![image](https://user-images.githubusercontent.com/67582707/150073072-6ae5c191-6619-44b1-9134-ee7fcd8e2348.png)





