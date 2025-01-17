# CAT
Computerized Adaptive Testing Package, including the following models and strategies.

* Item Response Theory (IRT)
  * MaximumFisherInformation (MFI) strategy
  * Kullback-Leibler Information (KLI) strategy
  * Model-Agnostic Adaptive Testing (MAAT) strategy
  * Bounded Ability Estimation Adaptive Testing (BECAT) strategy 
  * Bilevel Optimization-Based Computerized Adaptive Testing (BOBCAT) strategy 
  * Neural Computerized Adaptive Testing (NCAT) strategy 

* Multidimensional Item Response Theory (MIRT)
  * D-Optimality (D-opt) strategy
  * Multivariate Kullback-Leibler Information (MKLI) strategy
  * Model-Agnostic Adaptive Testing (MAAT) strategy
  * Bilevel Optimization-Based Computerized Adaptive Testing (BOBCAT) strategy 
  * Neural Computerized Adaptive Testing (NCAT) strategy 
* Neural Cognitive Diagnosis (NCD)
  * Model-Agnostic Adaptive Testing (MAAT) strategy
  * Bounded Ability Estimation Adaptive Testing (BECAT) strategy 
  
BECAT strategy comes from paper A Bounded Ability Estimation for Computerized Adaptive Testing(https://nips.cc/virtual/2023/poster/70224)

## Installation

Git and install by `pip`

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

