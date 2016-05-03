The Cal State LA Hydrogen research and fueling facility was established in the year 2014.The station is capable of producing hydrogen using renewable resources and the process involved is called as electrolysis. It is the first station to sell hydrogen fuel by kilogram into the public. In this project we have taken the data set containing the fueling details of hydrogen fuel generated in the facility and the various factors that affect the fueling process are analyzed and the prediction model is created. In this project we have used Microsoft Azure Machine learning studio to create a model for prediction, Apache spark code for analysis and creation of the spark model and Decision forest regression algorithm for prediction.

### **System Requirements**##
Number of worker nodes-2

Specification of each node

Number of Cores-8

RAM-14GB

Discs-16


## **Getting Started with model creation at Microsoft azure machine learning studio**

## Step 1
**_Login to Azure Account_**

1. Sign in to Azure Machine Learning Studio

##Step 2
**_Creation of Model_**

1. Create a new experiment as shown in the figure below:- 

 [Fig 1:Creation of new experiment](https://github.com/manvichandra/hydrogen-gas-power-plant/blob/master/Images/Experiment.JPG)
 
2.Add the data set to be analysed as shown in figure bellow:-

   [Fig 2:Adding the dataset](https://github.com/manvichandra/hydrogen-gas-power-plant/blob/master/Images/dataset.JPG)
   
3.Create a model as shown in the figure :-

  [Fig 2:Creation of the model](https://github.com/manvichandra/hydrogen-gas-power-plant/blob/master/Images/Model.JPG)
  
  
## **Getting started with Apache Spark**
 
## **Step 1**

1. Login to your Ibm Bluemix Account and look for IBM Analytics for Apache Spark .

2. Create a new notebook.

3.Upload the raw data file to Bluemix Object Storage.

4.Separating the labeled column.

5.Creation of RDD.

6.Splitting the data into training and test sets.

7.Training the dataset using Decision forest regression algorithm.

8.Evaluation of the result.

_**In order to see the output for the Hydrogen Dataset follow the step below:-**_

## **Step 2**

1. Create a new notebook. Click New, and then select Python .

2. Import the "hydrogenproject.ipynb" attached in the code folder and press the Run button to execute.

    [Fig 3:Pyspark file](https://github.com/manvichandra/hydrogen-gas-power-plant/blob/master/code/hydrogenproject.ipynb)
    
3. Result is shown in the figure below:-
   [Fig 4:Results](https://github.com/manvichandra/hydrogen-gas-power-plant/blob/master/Images/Result.JPG)
   
##**Special Thanks**
- (https://developer.github.com/  "GitHub for  API and style")

- Microsoft Azure Machine Learning Studio

## **Licence**

Developed By:  
- Manvi Chandra


