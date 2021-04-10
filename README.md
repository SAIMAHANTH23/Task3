**Name:** Sai Mahanth Rallapalli

**College:** Indian Institute Of Engineering Science and Technogy, Shibpur

**Language:** Python3

**Software Used:** Jupyter Notebook

**Main idea:**

The major idea is to predict the category using description. Output is given according to a trained model which
is trained using the concepts of deep neural network (several layers are used).

**Approach:**

We have read the data and created the dataframe using pandas. Now I have dropped the columns which are not required then there were several inconsistencies in the data and also the stopword, Hence I removed the stop word (like is, and) using NTLK corpus and the other inconsistencies were removed using replace function in python. Also used several packages to clean the data.

Now as given in problem statement i have taken only the primary category and for doing that I have written function. Assigning of numbers to unique words is done and function regarding the same is also written.As we know we need to train and test the model, we import train_test_split from sklearn and now we write a function for datacleaning of the input data.

Now we assign x_train, y_train, x_test and y_test and the encoding is done in which word tokenizing is done and we also use the inbuilt function one_hot (assignment of numbers to words) as shown in code.

We use the sequential model from training and testing of data, so in the sequential model the most important thing is padding, we pad the data which is stored in the form of lists and now comes the most important thing which is making the sequential model. For sequential model we use 5 layers which are LSTM (long short memory) for sequence prediction and is most important layer, then we use embedding layer for input, dense layer which is used to take data from previous layers neurons and we use 2 dropout layer to drop the number of neutrons and make model

Now test by taking a random input statement and test, model.predict.class gives the output and model.predict gives us the probability. The accuracy of the model is very poor though I tested taking many epochs due to my current mid terms exams I could only give less time for the assignment will think abou it once my exams finishes.
