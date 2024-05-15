# BBC News Classification

This Jupyter Notebook is designed to classify news articles from the BBC dataset into predefined categories using natural language processing techniques and machine learning models.

## Project Structure
The notebook contains several sections:

Data Loading: Load and display data from a CSV file.

Text Preprocessing: Clean and preprocess the text data.

Data Splitting: Split the data into training, validation, and testing sets.

Word Cloud Visualization: Generate a word cloud to visualize the most frequent words in the training set.

Feature Extraction: Convert text data into a numerical format using a bag-of-words model.

Model Training and Evaluation: Train a logistic regression model and evaluate its performance.

## Dependencies
This notebook requires the following Python libraries:

nltk
pandas
numpy
matplotlib
scikit-learn
wordcloud
PIL

## Setup and Installation
Ensure Python 3.x and Jupyter Notebook are installed on your system.

Install required Python packages:

```pip install numpy pandas matplotlib nltk scikit-learn wordcloud pillow jupyter```
Download and place the BBC dataset in the data/ directory, ensuring the file is named bbc_data.csv.

## Running the Notebook
Start Jupyter Notebook:

```jupyter notebook```
Navigate to the directory containing the notebook and open it.
Run the cells in sequence to perform the analysis.

## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request with your improvements.

## License
This project is distributed under the MIT License. See LICENSE for more information.

