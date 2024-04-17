# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2024

+ Team 2

+ Projec title: Machine Learning Fairness Algorithms Evaluation: A Comparative Analysis of Learning Fair Representations(A1) and Fairness Constraints: Mechanisms for Fair Classification(A2)

+ Team members
	+ Tien Nguyen
	+ Guanbiao Li
	+ Licheng Wu
	+ Zhaoyang Li

+ Project summary: Bias in algorithmic decision-making systems, particularly within the criminal justice system, is a pressing concern. Risk assessment tools like COMPAS are increasingly used to predict recidivism, potentially influencing sentencing decisions. However, these algorithms can perpetuate societal biases, leading to discriminatory outcomes for certain groups. This project explores two promising approaches to achieving fairness in classification tasks:

- Learning Fair Representations (Zemel et al., 2013): This approach focuses on data representation. It aims to learn informative features from the data while simultaneously obfuscating sensitive attributes, like race, that could lead to bias.
- Fairness Constraints: Mechanisms for Fair Classification - Mitigating Disparate Treatment (Feldman et al., 2015): This approach moves beyond traditional fairness metrics like disparate treatment (where a protected group is systematically favored or disfavored) and disparate impact (where the model's outcomes disproportionately affect a protected group). It seeks to prevent unfair outcomes even when statistical parity exists between groups.

- Project Conclusion: Given the higher accuracy and better calibration, Algorithm 1 (Learning Fair Representation) is preferred over Algorithm 2(Fairness Constraints: Mechanisms for Fair Classification). The advantage of learning fair representations is mainly in their ability to generalize and be applied across various tasks and models, potentially simplifying the machine learning pipeline. This approach requires careful design to ensure that the representation does not encode bias in subtle ways.

**Contribution statement**: All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement.

Tien Nguyen: Researched and implemented the A1 and A3 algorithm-Maximizing Fairness under Accuracy Constraints on the Bank dataset and the Compas dataset. Edited readme file, uploaded and organized files in our GitHub repo.

Guanbiao Li: Researched and helped to write the initial version of A1 and A2 algorithm. Implemented the algorithm and helped to debug. Edited readme file, uploaded and organized files in GitHub repo.

Licheng Wu: Assisted in the implement of the initial version of A1 (LFR) algorithm, improved the final LFR algorithm, organized & edited Github files, researched on LFR & assisted in PPT.

Zhaoyang Li: Researched A1 and A3 algorithms, as well as implemented A3 algorithm on COMPAS dataset. Edited Powerpoint and presented our research/code.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
