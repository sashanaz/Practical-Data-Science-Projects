Name: Sasha Nazareth
Student ID: 3912063

Instructions to execute my file:

This file will run on Jupyter notebook. And you should download the 'ml-100k/u.data' and s3912063_Assignment3. Keep both the files in their respective locations where you can access them easily.

1. Load the packages- panda,warnings and numpy

2. Next step is to download and load the dataset ml-100k/u.data.

3. Split the dataset into training and testing data sets.

4. In utils and baseline recommendation section, that will be a reference to check whether the implementation we have adapted is better or not. 

5. Created a new DataFrame for the train_ds and test_ds as it would be easier and faster to run the code.

6. Next, calculated the item popularity using a for loop.

7. Computed the weight of items. 

8. To calculate the Pearson Correlation Coefficient , used nested for loops.

9. Added the weights into the Pearson Correlation Coefficient formula in the loop. 

10. Included epsilon and gamma values as they are important to prevent us from facing errors. Using epsilon avoids those non calculations while using a good value in gamma like 30 is much more reliable as if lesser than this it will reduce its significance.

11. numpy is used as numpy helps to fasten up the code processing.

12. For prediction, used epsilon and gamma for the same reasons.

13. K =20, in both predictions.

14. Using argsort to sort the values.

15. Calculating the MAE and RMSE values.

16. In the end, calculating the ComRv value for Top N rated items.

End code.
