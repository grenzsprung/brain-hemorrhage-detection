# Translational Bioinformatics @ Columbia University
## Fall 2019
## Final Project: Detecting Intracranial Hemorrhage with Deep CNNs

### ![](figs/ID_0a00bdf23.jpg)



**Team**: 

Matteo Di Bernardo & Tim R. Schleicher


**Project summary**: 

Traumatic brain injuries can result in internal bleeding within the brain, often classified by health professionals as intracranial hemorrhage (ICH), a process that can cause permanent brain damage and is responsible for almost 30% of yearly injury deaths in the United States. In order to initiate ICH treatment, which often involves invasive surgery when cases are life threatening, experienced radiologists are required to quickly identify the presence of ICH and its subtype via computed tomography (CT) scans. This has becomean increasingly difficult endeavor in the face of limited availability of radiologists, efforts to reduce costs in the healthcare system, and most importantly, the little time available for a time-consuming analysis needed to save the life of the patient. 

The boom of machine learning techniques, specifically image classifier algorithms, presents an unprecedented opportunity to support specialists in quick and life-saving decision-making as they seek to determine whether an ICH is occurring, and if so, where in the brain it is located. To address the potential for algorithms of this nature to detect ICH, the Radiological Society of North America has published a dataset of over 25,000 labeled CT exams for a [Kaggle Competition](https://www.kaggle.com/c/rsna-intracranial-hemorrhage-detection) that aims to solicit teams to devise machine learning algorithms in order to detect ICH.

We developed and implemented several Artifical Neural Networks as image classifiers for the identification of ICHs. This includes a Simple Neural Network, a deep Convolutional Neural Network and a ResNet50. The algorithms evaluated and discussed. Please see this [presentation](https://github.com/grenzsprung/brain-hemorrhage-detection/blob/master/presentation/191211%20BINFG4006%20-%20Final%20Presentation%20-%20DiBernardo_Schleicher%20-%20final.pdf) for a detailed outline of our project and its findings. Our humble research seeks to facilitate better and faster diagnosis of ICH at lower costs and has the potential to contribute to changing the lives of patients with a complication where a few additional minutes could mean the difference between life and death.


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is organized as follows:

```
proj/
├── data/
├── presentation/
└── figs/
```

