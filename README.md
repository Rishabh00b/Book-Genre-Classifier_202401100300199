# Book-Genre-Classifier_202401100300199

Book Genre Classifier
Project Overview:
This project involves building a machine learning model to predict the genre of books based on three key features: author popularity score, book length, and the number of keywords associated with the book.
Using a Random Forest Classifier, the model is trained to categorize books into different genres.

Key Features:

Author Score: Popularity score based on the author's recognition or influence.

Book Length: Number of pages or words in the book.

Keywords: Count of relevant keywords tied to the book’s content.

Approach:

Data Preprocessing:

Data cleaning (handling missing values).

Feature selection for relevant attributes.

Label encoding for the target variable (book genre).

Model Building:

Split the data into training and testing sets.

Train a Random Forest Classifier to learn patterns in the data.

Model Evaluation:

Evaluate the model using classification metrics (accuracy, precision, recall, etc.).

Visualize feature importance to understand the most influential features in predicting the genre.

Generate a confusion matrix to assess the model’s performance across different genres.

Technologies Used:

Python

Pandas, NumPy (Data Manipulation)

Scikit-learn (Machine Learning)

Matplotlib, Seaborn (Data Visualization)

Getting Started:

Clone the repository:
git clone https://github.com/rishabh00b/book-genre-classifier_202401100300199.git

Install the required dependencies:
pip install -r requirements.txt

Upload your dataset to the project folder and run the provided Jupyter notebook to train the model and make predictions.

Future Improvements:

Experiment with different machine learning models (e.g., Support Vector Machines, Gradient Boosting).

Include additional features like publication year, author biography, etc.

Deploy the model as a web app using Flask or Streamlit.

