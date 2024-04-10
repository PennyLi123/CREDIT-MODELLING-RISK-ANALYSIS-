# Credit-Scoring-Analysis-Python


# Problem Statement

Built a Credit Scoring Model, enabling banks to make data-driven lending decisions.


# Dataset

Find it in the attachment:
https://github.com/PennyLi123/Credit-Scoring-Analysis-Python/blob/main/1.Scorecard.csv

 
This data contains 3000 records with 30 columns, including (Customer) ID (sensitive data), 28 independent variables and 1 dependent variable-Target.

Target represent the 2 types of loans: good loans (0) and bad loans (1).


<img width="415" alt="image" src="https://user-images.githubusercontent.com/74843963/192163473-18898a23-bd2d-4005-aab4-fed2843b5c49.png">


# Tools Used

* `Jupyter Notebook` is used as IDE.

* Developed cloud backend utilizing `AWS S3`.  Applied statistical methodology to formulate the lending strategy in `Excel`.
<img width="415" alt="image" src="https://github.com/PennyLi123/Credit-Scoring-Analysis-Python/blob/main/4.AWS%20S3.png">

* `Pandas` and `NumPy` are used for Data Manipulation & Pre-processing and Mathematical functions respectively.

* Visualized findings via `Matplotlib` and `Seaborn`.
(1) Visualized missing values in the dataset using the `sns.heatmap` function from the `Seaborn` library in `Python`.

❗️插入图片：5.heatmap_missing data
<img width="415" alt="image" src="https://github.com/PennyLi123/Credit-Scoring-Analysis-Python/blob/main/5.heatmap_missing%20data.png">

(2) Visualized the count of good loans (0) and bad loans (1) using a `countplot` chart from the `Seaborn`.
❗️插入图片：6.countplot_good loan & bad loan
<img width="215" alt="image" src="https://github.com/PennyLi123/Credit-Scoring-Analysis-Python/blob/main/6.countplot_good%20loan%20%26%20bad%20loan.png">

(3)Created a `boxplot` using `Seaborn`. It visualized the distribution of numerical variables across the entire dataset, horizontally ('orient='h''), with colors defined by the 'rainbow' palette.
❗️插入图片：7.boxplot_distribution of numerical variables
<img width="215" alt="image" src="https://github.com/PennyLi123/Credit-Scoring-Analysis-Python/blob/main/7.boxplot_distribution%20of%20numerical%20variables.png">



* Utilized the credit scoring model via logistic regression classifier in Python.  For more details, find in 2.Credit Scoring Modelling.ipynb

* Applied decile methodology to formulate the lending strategy in Excel.
[3.Scoredcard model prediction & analysis.xlsx](https://github.com/PennyLi123/Credit-Scoring-Analysis-Python/blob/main/3.Scoredcard%20model%20prediction%20%26%20analysis.xlsx)



# Conclusions
![image](https://user-images.githubusercontent.com/74843963/192164431-5557cad4-0fe6-45fb-9d7f-8b7272fc8497.png)






