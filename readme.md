## Heart Disease Prediction using Machine Learning

According to World Health Organization statistics, cardiovascular disease is the leading cause of death in the world. CVDs were responsible for 32% of all global deaths in 2019, as estimated by the World Health Organization. Heart attacks and strokes were responsible for 85% of these deaths. Low- and middle-income countries account for more than three quarters of all CVD deaths.

We have created a web application and a prediction model based on machine learning using which a patient can fill in basic details like age, gender, Chest Pain Types, Cholesterol Level, etc. Based on these data, the model is able to predict heart disease. We have used various machine learning algorithms like Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, and KNN for prediction.User is also able to print the report for tracking the disease.

## Installation of required software and Libraries
1. Install the Anaconda Python Package
2. Open Anaconda Prompt and Move to the downloaded project directory (Heart Disease Prediction) using the cd command

	Example:
	>> cd Path_of_Project_Directory
	
3. Create the virtual environment using the below command
	>>conda create -n hdp python==3.11.7
4. Activate the virtual environment using the command
	>>conda activate hdp
5. Now install the required Libraries using the below command
	>>pip install -r requirements.txt


## Steps to train the model after Installation of required software and Libraries
1. Open Anaconda Prompt and Move to the downloaded project directory (Heart Disease Prediction) using the cd command

	Example:
	>> cd Path_of_Project_Directory
	
2. Activate the virtual environment using the command
	>>conda activate hdp
	
	Note: hdp is the environment created at the time of installing the software and Libraries
	
3. Next to train the model open the Jupyter Notebook using the below command
	>>jupyter notebook
4. Open the Heart-Disease-Prediction.ipynb and run all cells
5. Once the training is completed the trained model models.pkl will be stored in the current working directory


## Steps to run the Flask App after training the model 
1. Open Anaconda Prompt and Move to the downloaded project directory (Heart Disease Prediction) using the cd command

	Example:
	>> cd Path_of_Project_Directory
	
2. Activate the virtual environment using the command
	>>conda activate hdp
	
	Note: hdp is the environment created at the time of installing the software and Libraries
	
3. Run the Flask App using the below command
	>>python app.py
	
	
## Tech Stack

**Language:** Python,Javascript,CSS,HTML
**Algorithms:** Logistic Regression,SVM,Decision Tree,Random Forest,KNN
**Framework:** Flask
**Tools:** VSCode,jupyter notebook
**Libraries:** NumPy,Pandas,Matplotlib

Happy Learning

Team VTUPulse.com