# Purchasing Intention Prediction
The project includes predicting whether or not a visitor will generate revenue.

## Set up
1. You can use the `requirements.txt` file to setup a virtual environment.
   Whether you are inside a virtual environment or otherwise, you the following command to install all dependencies:
   ```
   pip install -r requirements.txt
   ```
2. The dataset file is in the `data` folder.

## Run
1. Run the jupyter notebook using the following command:
   ```
   jupyter notebook
   ```
2. From the newly opened browser tab, select the `Purchasing Intention Prediction.ipynb` notebook and run it.

## Project Drescriptions

The Purchasing Intention Prediction Project is a research project that aims to predict the purchasing intention of online shoppers in real-time. Researchers have proposed and developed early purchase prediction frameworks using advanced machine learning models to investigate how early purchase intention in an ongoing session can be predicted. Since users could be anonymous, this could help to give real-time offers and discounts before the session ends.

One study proposes a real-time online shopper behavior analysis system consisting of two modules which simultaneously predicts the visitor’s shopping intent and Web site abandonment likelihood. The first module predicts the purchasing intention of the visitor using aggregated pageview data kept track during the visit along with some session and user information. The extracted features are fed to random forest (RF), support vector machines (SVMs), and multilayer perceptron (MLP) classifiers as input. The results show that MLP produces significantly higher accuracy and F1 Score than RF and SVM.

Another study uses only sequential clickstream data to train a long short-term memory-based recurrent neural network that generates a sigmoid output showing the probability estimate of visitor’s intention to leave the site without finalizing the transaction in a prediction horizon. The modules are used together to determine the visitors which have purchasing intention but are likely to leave the site in the prediction horizon and take actions accordingly to improve the Web site abandonment and purchase conversion rates.
These findings support the feasibility of accurate and scalable purchasing intention prediction for virtual shopping environment using clickstream and session information data

