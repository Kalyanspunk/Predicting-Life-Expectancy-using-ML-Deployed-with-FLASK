
# Life Expectancy Prediction using Linear Regression and Deployed using Flask

This project is a machine learning-based web application that predicts life expectancy using linear regression. The application uses data from the World Health Organization (WHO) to train a linear regression model that can predict life expectancy based on various factors such as income, education, and healthcare.



## Installation

To install the necessary dependencies for this project, run the following command:

```bash
  pip install -r requirements.txt

```
This will install Flask and scikit-learn, which are required for running the application.
## Usage
To run the application, navigate to the project directory and run the following command:
```javascript
python app.py

```
This will start the Flask server and make the application accessible at 'http://localhost:5000/'.

To use the application, enter values for the various factors that contribute to life expectancy, such as income and education, into the input fields on the webpage. Then click the "Predict" button to see the predicted life expectancy for the given values.

## Dataset
The dataset used for training the linear regression model was obtained from the WHO and is available on Kaggle. The dataset contains information on various factors that contribute to life expectancy, such as income, education, healthcare, and more.
## Future Work
Some potential improvements to this project could include:

• Adding more data sources to improve the accuracy of the model

• Using more advanced machine learning techniques, such as neural networks or decision trees, to improve the accuracy of the predictions

• Adding visualizations to the web application to make it more user-friendly
## Contributing

Contributions to this project are welcome! If you find a bug or have a suggestion for improvement, please open an issue or submit a pull request.



## Screenshots
The output of your project will be the predicted life expectancy for a given set of input factors such as income, education, healthcare, etc.


![App Screenshot](https://raw.githubusercontent.com/Kalyanspunk/Predicting-Life-Expectancy-using-ML-Deployed-with-FLASK/main/ml%20model%20using%20flask/screenshots/predicted.png)

For example, if a user enters the following input values into your web application:

• Income: $50,000\
• Education: 12 years\
• Healthcare: 5.0

Your machine learning model will use these input values to make a prediction for the life expectancy of an individual with these characteristics. The output might be something like:

• Predicted Life Expectancy: 78.5 years

The output will depend on the input values entered by the user and the accuracy of your machine learning model. The more accurate your model, the more reliable and useful the output will be.
