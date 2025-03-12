# nosql-challenge

This challenge puts in the role of helping jounalists at a food magazine evaluate rating data to help them decide where to focus future articles.

There are 3 parts in this challenge:

Part 1 focuses on the database and Jupyter Notebook set up. We start by importing data and setting up the the collection in the database. Then set up that collection to a variable to prepare the collection for use.

In part 2, we update the database by adding a new halal restaurant to the collection. We learned that the magzine is not interestedin establishments in Dover, so we removed any documents that included establishments in Dover Local Authority. Some of the number values that were stored as string have been converted to numbers.

Part 3 is where we conducted the exploratory analysis. We answered question given by the magazine to help find locations they want to visit. We found that there were 41 establishments with hygiene score equal to 20. That means that those 41 establishments have have terrible hygiene since the higher the score means the worse it is in that area in this case. And then there was 33 establishments in London that have a Rating Value of 4 or greater. Which means that there 33 are in London that have very good ratings, because the scale is from 1-5. Where 5 means the best and 1 is the worst rating for this case. The top 5 establishments with Rating Value of 5 that are nearest to "Penang Flavours" can be found in the analysis Jupyter notebook. And finally there are 16,827 establishments across 55 Local Authority areas that have a hygience score of 0. To see what are the top 10 Local Authority with the most establishments that have a hygiene score of 0, please look in the analysis notebook.


This code for this challenge was coded by me with the help of past activities, Xpert Learning Assistant, and ChatGPT.
