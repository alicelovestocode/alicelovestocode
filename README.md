***
<h1 align="center">
&nbsp;
alicelovestocode
</h1>
<p align="center">
My name is Alice (she/her) and I am an aspiring Computational Pathologist / Neuroscientist who codes in her free time.
</p>

***

## Biography

I have a strong academic background in the computer sciences, specialising in applications in medicine. My current research interests are in the diagnosis and prognosis of pulmonary diseases including lung cancers and pneumonia, and recently COVID-19, using machine learning and deep learning techniques on audio datasets. This research also encompasses the use of novel audio data pre-processing tools that I have developed, as well as the study of audio feature generation and selection. After being awarded a scholarship in June 2021, I was introduced to confidence machine learning via the conformal prediction framework.

Conformal prediction provides valid measures of confidence in a diagnosis, which is crucial for medical decision-making since it allows the estimation of the risk of an erroneous clinical decision for an individual patient. Furthermore, the risk of clinical errors may be controlled by an acceptable level of confidence for a given clinical decision and therefore the risk of misdiagnosis is known to both clinician and patient. Conformal predictors are region predictors, meaning that if not enough information is available to make a definitive diagnosis, then the algorithm would make a number of possible (multiple) diagnoses rather than an incorrect one. This would then lead to a scenario in which the patient would require further tests to narrow down the diagnosis. Conformal prediction could be used to screen patients for a disease, reducing bottlenecks in hospitals where many people may be on a waiting list for a diagnostic test. In the context of the COVID-19 pandemic, imagine that we could use conformal prediction to screen patients in the comfort of their own homes, using smartphone-recorded cough data, and only allowing multiple-diagnosis patients access to a PCR test performed by a clinician. Diagnosis would be safer, cheaper, and less of a strain on NHS services.

Specifically, I use inductive conformal prediction. Disease datasets often suffer from the class imbalance problem, so I apply Mondrian inductive conformal prediction, which is class-conditional and takes the imbalance of a dataset into account. The aspects of conformal prediction that I have an interest in are the use of model-agnostic nonconformity error functions and their effects on various underlying machine learning models, the effectiveness of normalized nonconformity functions for classification problems, the use of hybrid nonconformity error functions, and lastly, the use of conformal predictor ensembles (aggregated conformal predictors) and those in conjunction with cross-validation – cross-conformal predictors and Mondrian cross-conformal predictors.

## Skillset

Here is my current WIP skillset. I like to code in Python, Julia, and R using Jupyter Notebooks through Microsoft's Visual Studio Code.

If you have any suggestions please contact me using the email provided on my profile. It would be much appreciated!

| Languages            | Skill Level | Note                                                                                          |
| -------------------- | ----------- | --------------------------------------------------------------------------------------------- |
| **Python**           | Proficient  | Strongest language, being coding in Python since 2016.                                        |
| **Julia**            | Improving   | Working through some tutorials and making a few demo projects.                                |
| **R**                | Improving   | Used before, but I would like to understand the language a bit better.                        |
| **LaTeX**            | Proficient  | Written papers using Overleaf, or through converting Jupyter notebooks to LaTeX               |

I thought I would provide a list of packages I use frequently in Python, and my experience level with each one.

| Python Packages      | Skill Level | Note                                                                                          |
| -------------------- | ----------- | --------------------------------------------------------------------------------------------- |
| **scikit-learn**     | Proficient  | Industry standard for machine learning. I use this daily.                                     |
| **imbalanced-learn** | Improving   | Oversampling/undersampling/SMOTE for imbalanced data. Looking to make full use of this.       |
| **mlxtend**          | Improving   | Machine learning extensions. Mostly for ensemble classifiers, looking to use for more.        |
| **mlens**            | Improving   | A collection of ensemble macghine learning algorithms. Looking to make full use of this.      |
| **xgboost**          | Improving   | Extreme gradient boosting. Mostly for random forest but looking to use for more.              |
| **lightgbm**         | Improving   | Light gradient boosting. Looking to use an alternative to xgboost when necessary.             |
| **catboost**         | Improving   | Categorical gradient boosting. Mostly for decision trees, looking to use where possible.      |
| **nilearn**          | Improving   | Cool library for neuroimaging analysis that I am looking to check out sometime.               |
| **nonconformist**    | Proficient  | The best implementation of conformal prediction out there. Used in a number of studies.       |
| **libsvm**           | Improving   | Looking to try out cool alternatives to scikit-learn for SVMs.                                |
| **kmodes**           | Improving   | An implementation of k-modes not in scikit-learn. Learning as an alternative to k-means.      |
| **numpy**            | Proficient  | Industry standard for linear algebra and matrix mathematics. I use this daily.                |
| **scipy**            | Proficient  | My goto for common mathematical functions. Used often.                                        |
| **pandas**           | Proficient  | Industry standard for data manipulation. I use this daily.                                    |
| **plotly**           | Proficient  | Data visualization is my favourite part of a study. I love pretty graphs.                     |
| **seaborn**          | Proficient  | Use this just as much as plotly for basically the same reasons.                               |
| **librosa**          | Proficient  | A musical package for audio data. Used for in a number of studies.                            |
| **ghostml**          | Improving   | GHOST or Generalized Threshold Shifting Procedure, a novel way to handle imbalanced data.     |
| **keras**            | Improving   | The scikit of neural networks, a wrapper for the OP tensorflow framework. Looking to master.  |
| **pytorch**          | Improving   | An alternative to keras/tensorflow for neural networks, by Facebook.  Will give it a try.     |
| **opencv-python**    | Improving   | Computer vision library. A new research area that I'm looking to explore in more detail.      |

## Projects & Licensing

A number of my projects are studies which are currently closed source due to licensing limbo or because they are not at a stage where I wish to publish them.

It should be noted that most of my studies datasets are either sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.php) or from GitHub repositories (see my starred repos) and are licensed appropriately. 

I provide any code that I have created for my studies under the MIT license. I respectfully ask that credit be given where it's due.
