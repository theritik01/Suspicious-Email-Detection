<h1 align="center">Email Spam Detection</h1>

## <br>**➲ Project description**
Email spam detection system is used to detect email spam using Machine Learning technique called Natural Language Processing and Python, where we have a dataset contain a lot of emails by extract important words and then use naive classifier we can detect if this email is spam or not.

## <br>**➲ Prerequisites**
This is list of required packages and modules for the project to be installed :
* <a href="https://www.python.org/downloads/" target="_blank">Python3</a>
* Pandas 
* Numpy
* Scikit-learn
* NLTK

Install all required packages :
 ```sh
  pip install -r requirements.txt
  ```
## <br>**➲ The Dataset**
Human activites dataset contain about 5728 record which is a sample of an email<br>
and a target column "type" which describe the state of an email spam or not.<br>
<br>**Dataset features and target :**<br>
<img src="https://i.postimg.cc/X7QLysbq/data-set.png"><br><br>

## <br>**➲ Coding Sections**
In this part we will see the project code divided to sections as follows:
<br>

- Section 1 | Data Preprocessing :<br>
In this section we aim to do some operations on the dataset before training the model on it,
<br>processes like :
  - Load dataset
  - Check for duplicates and remove them 
  - Check for missing data for each column 
  - Cleaning data from punctuation and stopwords and then tokenizing it into words (tokens)
  - Convert the text into a matrix of token counts
  - Split the data into training and testing sets<br><br>

- Section 2 | Model Creation :<br>
The dataset is ready for training, so we create a K-nearest Neighbors "KNN" model using scikit-learn and thin fit it to the data.<br>

- Section 3 | Model Evaluation :<br>
Finally we evaluate the model by getting accuracy, classification report and confusion matrix.

## ➲ Installation
1. Clone the repo
   ```sh
   git clone https://github.com/theritik01/Suspicious-Email-Detection.git
   ```
2. Run the code from cmd
   ```sh
   python email_spam_detection.py
   ```

## <br>**➲ Output**
Now let's see the project output after running the code :

**Dataset head :**<br>
<img src="https://i.postimg.cc/X7QLysbq/data-set.png"><br><br>

**Dataset missing data count :**<br>
<img src="https://i.postimg.cc/dt1dgvbQ/missing-data.png"><br><br>

**Dataset after cleaning puncituations and tokenizing text :**<br>
<img src="https://i.postimg.cc/jdLwZcfL/dataset-after-cleaning.png"><br><br>

**Classification report, confusion matrix and accuracy :**<br>
<img src="https://i.postimg.cc/HnGYz017/classification-report.png"><br><br>
<img src="https://i.postimg.cc/Qd6jwZrD/final.png"><br>


