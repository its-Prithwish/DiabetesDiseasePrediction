# DiabetesDiseasePrediction
<br>
Diabetes Mellitus is one of the common disease worldwide and keeps increasing everyday due to changing lifestyles, unhealthy food habits and over weight problems. To solve the problem I tried to develop a Diabetes prediction system that give near about 78% accuracy.
I downloaded a dataset from kaggle and used SVM (Support Vector Machine) on it for prediction.
First I imported all the necessary libraries like numpy, pandas, sklearnex.
Then from sklearnex.model_selection and sklearn.metrics I imported train_test_split and accuracy_score respectively.
Then I loaded the dataset using a pandas library know as read_csv.
0 represents that the person doesn't have diabetes and 1 represents the patient is diabetic.
<br>
Then I took the took the mean values of the dataset for 0 and 1 using groupby().mean()
Next I droped the outcome column and stored it to a variable named Y.
Then training and testing part was done by using train_test_split().
Next I imported svc from svm and stored it to a variable 'classifier'.
After that I predicted for traing and testing data both and got 78% and 77% accuracy respectively.

<br>
 Here's a snapshot of the final Output :

![Screenshot (131)](https://user-images.githubusercontent.com/87355004/224536098-e6f7572d-4aba-48a7-b546-0912bda2d4ef.png)

  
