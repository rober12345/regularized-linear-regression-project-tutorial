<!-- hide -->
# Regularized linear regression - Step by step guide
<!-- endhide -->

- Understand a new dataset.
- Process it by applying exploratory data analysis (EDA).
- Model the data using regularized linear regression.
- Analyze the results and optimize the model.

## 🌱 How to start this project

1. Create a new repository based on [machine learning project](https://github.com/4GeeksAcademy/machine-learning-python-template) by [clicking here](https://github.com/4GeeksAcademy/machine-learning-python-template/generate).
2. Open the newly created repository in Codespace using the [Codespace button extension](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository).
3. Once the Codespace VSCode has finished opening, start your project by following the instructions below.

## 🚛 How to deliver your linear regression model

Once you have finished solving the exercises, be sure to commit your changes, push them to your repository, and go to 4Geeks.com to upload the repository link.

## 📝 Instructions to build the linear regression model in python

### US county-level sociodemographic and health resource data (2018-2019)

Sociodemographic and health resource data have been collected by county in the United States and we want to find out if there is any relationship between health resources and sociodemographic data.

To do this, you need to set a target variable (health-related) to conduct the analysis.

#### Step 1: Loading the CSV into a python dataset

The dataset can be found in this project folder under the name `demographic_health_data.csv`. You can load it into the code directly from the link:

```text
https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/demographic_health_data.csv
```

Or download it and add it by hand in your repository. In this dataset you will find a large number of variables, which you will find defined [here](https://raw.githubusercontent.com/4GeeksAcademy/regularized-linear-regression-project-tutorial/main/data_dict.csv).

#### Step 2: Perform a full EDA

This second step is vital to ensure that we keep the variables that are strictly necessary and eliminate those that are not relevant or do not provide information. Use the example Notebook we worked on and adapt it to this use case.

Be sure to conveniently divide the data set into `train` and `test` as we have seen in previous lessons.

#### Step 3: Build a linear regression model in python

Start solving the problem by implementing a linear regression model and analyze the results. Then, using the same data and default attributes, build a Lasso model and compare the results with the baseline linear regression.

Analyze how $R^2$ evolves when the hyperparameter of the Lasso model changes (you can, for example, start testing from a value of 0.0 and work your way up to a value of 20). Draw these values in a line diagram.

#### Step 4: Optimize the previous linear regression model using python

After training the Lasso model, if the results are not satisfactory, optimize it using one of the techniques seen above.

> Note: We also incorporated the solution samples on `./solution.ipynb` that we strongly suggest you only use if you are stuck for more than 30 min or if you have already finished and want to compare it with your approach.
