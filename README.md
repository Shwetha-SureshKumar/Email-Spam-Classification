In our dataset, We have Label & EmailText.
Linear Regression : Since, its a qualitative(Label & EmailText) classification - Can't use Linear Regression
Logistic Regression : Qualitative input(EmailText) requires CountVectorizer[
                                            Count each word and represent as {Hello:2, This:1} from "Hello All!, This is Shwetha"
                                            ] - Logistic Regression with CountVectorizer gives scor eof 97.93%
SVM : With CountVectorizer gives score of 98.2%
