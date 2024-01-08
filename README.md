# Banking-Customer-Churn-Prediction-By-ANN

<h2>Hii Guys!!</h2>
<p>I have tried to create an Artificial Neural Network on kaggle by taking the dataset of the credit card customer churn prediction. </p>
<ol>
  <li>Firstly we to check the null values and duplicate values</li>
  <li>Now as the data set contains categorical values so we have to convert it into the numerical values by using the one hot encoder</li>
  <li>Remove the features that that are not contributing towards the complexity of model</li>
</ol>

<h2>Train the model</h2>
<ul>
  <li>
    convert all the values in the specified range
  </li>
  <li>Import <b>keras</b> from tensorflow </li>
  <li>Decide the number of hidden layes and the number of nodes</li>
</ul>

<p>As per my model I have decided the value of epoch = 50 and created 1 hidden layer,the intial layer consist of 5 bias and hidden layer consist of 3 bias as show in the diagram</p>
<img alt='model_demo' src="Screenshot 2024-01-08 153811.png" style="border: 10px solid black">
<p>My consist some sort of overfitting you can solve that by adding the regulariztion </p>
