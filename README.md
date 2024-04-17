# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Spring 2024

+ Team #
+ Projec title: Machine Learning Fairness Algorithms Evaluation: A Comparative Analysis of Learning Fair Representations and Fairness Constraints: Mechanisms for Fair Classification
+ Team members
	+ Tien Nguyen
	+ Guanbiao Li
	+ Licheng Wu
	+ Zhaoyang Li
+ Project summary: Bias in algorithmic decision-making systems, particularly within the criminal justice system, is a pressing concern. Risk assessment tools like COMPAS are increasingly used to predict recidivism, potentially influencing sentencing decisions. However, these algorithms can perpetuate societal biases, leading to discriminatory outcomes for certain groups. This project explores two promising approaches to achieving fairness in classification tasks:
- Learning Fair Representations (Zemel et al., 2013): This approach focuses on data representation. It aims to learn informative features from the data while simultaneously obfuscating sensitive attributes, like race, that could lead to bias.
0 Mitigating Disparate Treatment (Feldman et al., 2015): This approach moves beyond traditional fairness metrics like disparate treatment (where a protected group is systematically favored or disfavored) and disparate impact (where the model's outcomes disproportionately affect a protected group). It seeks to prevent unfair outcomes even when statistical parity exists between groups.
	
**Contribution statement**: [default] All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

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
