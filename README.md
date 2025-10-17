# PPDRQ

Quantifying the realibility of the deep learning model focusing on Medical Imaging.

## Authors
Junaidul Islam1, Isack Farady2, Chia-Chen Kuo3, Fu-Yu Lin4, Chih-Yang Lin1
1 Department of Mechanical Engineering, National Central University, Taoyuan, Taiwan, 
2 Department of Electrical Engineering, Yuan Ze University, Taoyuan, Taiwan, 
3 National Center for High-performance Computing, National Applied Research Laboratories, Hsinchu, Taiwan,
4 Department of Neurology, China Medical University Hospital, Taichung, Taiwan

Corresponding author : andrewlin@ncu.edu.tw

## Table of Contents
- [About](#about)
- [Requirements](#requirements)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## About
In domains where safety is crucial, such as medical imaging, achieving a high degree of classification accuracy is inadequate unless it is complemented by predictions that are both reliable and interpretable. Traditional measures of uncertainty frequently yield global assessments that obscure localized fluctuations in model confidence, a factor that can be pivotal when differentiating between closely related clinical conditions. This paper presents Pairwise Probability Differential Reliability Quantification (PPDRQ), an innovative framework that assesses the reliability of predictions made by deep neural networks through the evaluation of pairwise discrepancies among class probability estimates. By incorporating PPDRQ into a custom loss function enhanced with a triplet loss to refine the feature space. The proposed approach incentivizes the network to generate outputs that are both more distinct and trustworthy. Comprehensive experiments conducted on MRI-based Alzheimer’s disease diagnosis indicate that models with PPDRQ exhibit enhanced reliability, improved interpretability, and superior performance, thereby offering significant insights for clinical decision-making.


## Requirements
- Python 3.8.*
- Scikit-learn
- pytorch 2.4.*
- Matplotlib
- Pandas
- Numpy 1.24.*

## Usage
Copy Paste code from jupyter notebook, easy to use and implementation


## Acknowledgements
This research was supported by the National Science and Technology Council (NSTC), Taiwan, under Grants NSTC 111-2923-E-008 -006 -MY3.