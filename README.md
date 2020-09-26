![ulupong](ulupong.png?raw=true "ulupong")

<h1><center>Udacity: Starbucks Portfolio Excercise</center></h1>

### Table of Contents
1. [Project Motivation](#pm)
2. [Data](#data)
3. [Project Goal](#goal)
3. [Notes](#notes)
5. [Install](#install)
6. [Contents](#contents)
7. [Instructions](#instructions)
8. [Acknowledgements](#ack)

#### Project Motivation<a name="pm"></a>
This repository contains project codes required to complete the Starbuck Portfolio Excercis of Udacity's Data Scientist nano degree program.

#### Data <a name="data"></a>
The dataset provided in this portfolio exercise was originally used as a take-home assignment provided by Starbucks for their job candidates. The data for this exercise consists of about 120,000 data points split in a 2:1 ratio among training and test files. Each data point includes one column indicating whether or not an individual was sent a promotion for the product, and one column indicating whether or not that individual eventually purchased that product. Each individual also has seven additional features associated with them, which are provided abstractly as V1-V7. Two CSV files holds the data, `Test.csv` and `training.csv`.

#### What is this excercise trying to achieve?<a name="goal"></a>
  In the experiment simulated by the data, an advertising promotion was tested to see if it would bring more customers to purchase a specific product priced at $10. Since it costs the company 0.15 to send out each promotion, it would be best to limit that promotion only to those that are most receptive to the promotion. Strabucks promotion strategy will be evaluated on 2 key metrics:
  1. Incremental Response Rate (IRR)
  1. Net Incremental Revenue (NIR)
 
Starbucks data scientist achieved an IRR of 1.88% and a NIR of $189.45, when this data was first presented. These numbers will serve as the benchmarks to beat. The final deliverable of the project is a bring my solution to the problem.<br>

#### Notes<a name="notes"></a>
XGBoostClassifier was the classifier selected to model the excercise. The model produced a very good accuracy, precision, recall, f1-scores.
The IRR and NIR results of my implementation resulted with a good enough score; 1.2% and a lost of $4.05.
I was not able to beat Starbucks implementation, and they actually lost a little money.<br>
Let me go to Starbucks now and buy a Venti, so they could recoup theri losses.


#### Install<a name="install"></a>
This project requires Python and the following Python libraries installed:

- numPy
- pandas
- matplotlib
- seaborn
- scikit-learn
- imblearn
 -xgboost

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already have most of the above packages.

#### Content<a name="contents"></a>
The archive submission includes the following files and directory:<br>
1. Implementation of the Udacity Starbucks Portfolio Excercise `stabucks_u1up0ng.ipynb`<br>
2. Two Starbuck provided data 'Test.csv' and `training.csv`<br>
3. Python file provided by Udacity to calculate IRR and NIR, `test_results.'py`<br>
4. `_pycache_` folder holding `test_results.cpython-37.pyc`
5. This `README.md` file
6. My icon `ulupong.png`

### Instructions<a name="instructions"></a>
1. Run the `starbucks_u1up0ng.ipynb` file, and read results.



#### Acknowledgements<a name="ack"></a>
This project lives at [Udacity](https://classroom.udacity.com/nanodegrees/nd025-ent/parts/347da0f8-5670-4bbf-8587-b02b7c0fe111/modules/54d0cedc-dd84-4cfb-9a22-f665a062102c/lessons/f3191984-c26c-4927-9ec4-a55ffd40b9c5/concepts/e202df31-f5a7-4077-908b-117ce1a6b57d)<br>
Big thanks to [joshxinjie](https://medium.com/datadriveninvestor/simple-machine-learning-techniques-to-improve-your-marketing-strategy-demystifying-uplift-models-dc4fb3f927a2) Lee a great write-up on Uplift Models, that help me greatly understand what needs to be done.

**u1up0ng 2020/09/26**