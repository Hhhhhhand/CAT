# CAT
**<font size=5>Computerized Adaptive Testing Package, including the following models and strategies.</font>**
If you like our project, please give us a star ⭐ on GitHub.
<br>

## ❗ What is CAT About?
**Computerized Adaptive Testing (CAT)** stands as one of the earliest and most successful integrations of educational practices and computing technology.  
CAT is a dynamic and interactive process between a student and a testing system. The CAT system is split into two main components that take turns: At each test step, the Cognitive Diagnosis Model (CDM), as the user model, first uses the student’s previous  responses to estimate their current proficiency, based on cognitive science or psychometrics. Then, the Selection Algorithm picks the next question from the bank according to certain criteria.
This two-step process repeats until a predefined stopping rule is met, and the final estimated proficiency (i.e., diagnostic report) of individual students will be fed back to themselves as the outcome of this assessment or for facilitating future learning. 

## 📕 Relevant Theories
### 🔍Cognitive Diagnosis Models(CDM)
#### Item Response Theory (IRT)
Item Response Theory (IRT) is a statistical model used to assess individual abilities and traits. students’ proficiencies and question difficulties are handled as overall attributes reflected in students’ historical response data. These attributes can be single or multidimensional and are estimated through latent parameter estimation techniques.   One of the most widely used models in IRT is Three-Parameter Logistic Model(3PL-IRT).

#### Neural Cognitive Diagnosis (NCD)
Neural Cognitive Diagnosis (NCD) is a cutting-edge framework designed to tackle the challenges inherent in cognitive diagnosis, in response to the complex and non-linear interactions between students and exercises. In NCD models , we project students and exercises to factor vectors and incorporates neural networks to learn the complex exercising interactions. 

### ✏️Selection Algorithm

* **<font size=4>Item Response Theory (IRT)**</font>
  * MaximumFisherInformation (MFI) strategy
  * Kullback-Leibler Information (KLI) strategy
  * Model-Agnostic Adaptive Testing (MAAT) strategy
  * Bounded Ability Estimation Adaptive Testing (BECAT) strategy 
  * Bilevel Optimization-Based Computerized Adaptive Testing (BOBCAT) strategy 
  * Neural Computerized Adaptive Testing (NCAT) strategy 

* **<font size=4>Multidimensional Item Response Theory (MIRT)</font>**
  * D-Optimality (D-opt) strategy
  * Multivariate Kullback-Leibler Information (MKLI) strategy
  * Model-Agnostic Adaptive Testing (MAAT) strategy
  * Bilevel Optimization-Based Computerized Adaptive Testing (BOBCAT) strategy 
  * Neural Computerized Adaptive Testing (NCAT) strategy 
* **<font size=4>Neural Cognitive Diagnosis (NCD)</font>**
  * Model-Agnostic Adaptive Testing (MAAT) strategy
  * Bounded Ability Estimation Adaptive Testing (BECAT) strategy 
  
BECAT strategy comes from paper A Bounded Ability Estimation for Computerized Adaptive Testing(https://nips.cc/virtual/2023/poster/70224)

## ⚡ Installation
To make use of our work, you should do these below:

**Git and install by `pip`**

```
pip install -e .
```


## Quick Start

See the examples in `scripts` directory.

## utils

### Visualization

By default, we use `tensorboard` to help visualize the reward of each iteration, see demos in `scripts` and use

```
tensorboard --logdir /path/to/logs
```

to see the visualization result.
