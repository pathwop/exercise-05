# Exercise 5

This exercise is about the Titanic passengers from last time, used for machine learning purposes with Weka.

## Step 1

Please clone this repository onto your local computer. On the command line, you would enter: `git clone https://github.com/idh-cologne-tools-ressourcen-infra/exercise-05`, and create a new branch using your UzK username as a name.

## Step 2
Install Weka from [here](https://www.cs.waikato.ac.nz/ml/weka/). The download comes with a  pre-packaged Java virtual machine, which should make the installation straightforward. 

## Step 3
The file `data/titanic.arff` contains a data set in the ARFF format used by Weka. It's essentially the same file as you produced in the last exercise. Feel free to inspect it.

Load the file in the Weka explorer and try to find the best method to predict the survivors!

Hints:

- Not all features are useful predictors for the target class. You can remove them using a filter (on the Preprocess tab).
- Some classifiers generate information on their inner workings, i.e., which features have been used. 
- Some classifiers allow setting options via the white field next to the "Choose" button. Some options influence training speed via multithreading, others change prediction performance, and some help with the debugging.


## Step 4


If you're happy with a result (or have spent enough time with Weka), copy the classifiers output into a plain text file called `evaluation.txt` and place it in the root folder of the repository. Commit the file to the repository as usual.