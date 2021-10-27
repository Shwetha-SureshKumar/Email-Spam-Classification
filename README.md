In our dataset, We have Label & EmailText.
Linear Regression : Since, its a qualitative(Label & EmailText) classification - Can't use Linear Regression
Logistic Regression : Qualitative input(EmailText) requires CountVectorizer[
                                            Count each word and represent as {Hello:2, This:1} from "Hello All!, This is Shwetha"
                                            ] - Logistic Regression with CountVectorizer gives scor eof 97.93%
SVM : With CountVectorizer gives score higher than Logistic Regression

***
It is usually suggested to use linear kernels if the number of features is larger than the number of observations in the dataset (otherwise RBF might be a better choice).
When working with a large amount of data using RBF, speed might become a constraint to take into account.
