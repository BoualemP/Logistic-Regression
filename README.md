# Logistic-Regression
First, We will build a logistic regression model to predict whether a student gets admitted into a university.

Suppose that an administrator of a university department want to determine each applicant’s chance of admission based on their results on two exams.

    We have historical data from previous applicants that you can use as a training set for logistic regression.
    For each training example, we have the applicant’s scores on two exams and the admissions decision.
    The task is to build a classification model that estimates an applicant’s probability of admission based on the scores from those two exams.

we'll start by loading the dataset for this task.

        X_train contains exam scores on two exams for a student
        y_train is the admission decision
            y_train = 1 if the student was admitted
            y_train = 0 if the student was not admitted

