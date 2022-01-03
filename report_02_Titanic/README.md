# Report 2 - Titanic

The sinking of the [RMS Titanic](https://en.wikipedia.org/wiki/RMS_Titanic) is one of the most infamous shipwrecks in history.  On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

In this challenge, we ask you to complete **the analysis of what sorts of people were likely to survive**. In particular, we ask you to apply the tools of machine learning to predict which passengers survived the tragedy.



## Practice Skills

* Binary classification
* Python & SKLearn



## Data

The data ziped into `data.zip`, please first extract it. There are two groups:

* training set (train.csv)
* test set (test.csv)

The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the `ground truth`) for each passenger. Your model will be based on `features` like passengers' gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include `gender_submission.csv`, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.



### Data description

![data description1](images/data_description1.png)
![data description2](images/data_description2.png)



### Variable Notes

`pclass`: A proxy for socio-economic status (SES)

* 1st = Upper
* 2nd = Middle
* 3rd = Lower



## Requirements

* Design the classification model, implement the code
* Think methods to resolve the problem of missing data of some column
* How to convert the `pclass`, `embarked` fields to vector field
* Submit your result to [the website](https://www.kaggle.com/c/titanic) (如果不能访问这个网站，则想办法如何科学上网)
* Finish the report by using the template `report_template.ipynb`
* Submit code, report through `git`



## Links

* [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
