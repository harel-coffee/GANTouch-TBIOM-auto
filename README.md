This repository contains the code for the paper [GANTouch: An Attack-Resilient Framework for Touch-based Continuous Authentication System]() authored by [Mohit Agrawal](https://sites.google.com/view/mohit-agrawal/home), [Pragyan Mehrotra](https://www.linkedin.com/in/pragyan-m/), [Rajesh Kumar](https://sites.google.com/view/kumar7) and [Rajiv Ratn Shah](https://www.iiitd.edu.in/~rajivratn/). The code has been tested on Pytorch 1.3.1, Sklearn 0.22.2 and Python 3.6.8.

## Abstract
Previous studies have shown that commonly studied (vanilla) implementations of touch-based continuous authentication systems (V-TCAS) are susceptible to active adversarial attempts. This study presents a novel Generative Adversarial Network assisted TCAS (G-TCAS) framework and compares it to the V-TCAS under three active adversarial environments viz. Zero-effort, Population, and Random-vector. The Zero-effort environment was implemented in two variations viz. Zero-effort (same-dataset) and Zero-effort (cross-dataset). The first involved a Zero-effort attack from the same dataset, while the second used three different datasets. G-TCAS showed more resilience than V-TCAS under the Population and Random-vector, the more damaging adversarial scenarios than the Zero-effort. On average, the increase in the false accept rates (FARs) for V-TCAS was much higher (27.5\% and 21.5\%) than G-TCAS (14\% and 12.5\%) for Population and Random-vector attacks, respectively. Moreover, we performed a fairness analysis of TCAS for different genders and found TCAS to be fair across genders. The findings suggest that we should evaluate TCAS under rigorous adversarial environments and affirm the usefulness of GANs in the TCAS pipeline. 

## Getting Started 
Please install all the required dependendencies by running the following command:
```
pip install -r requirement.txt
```

## Experiments
All the experiments can be found in the files. 

## Contact
If you face any problem in running this code, you can contact us at {pragyan18168, rajivratn}@iiitd.ac.in, mohit.nittrichy@gmail.com and rkumar@haverford.edu

## License
Copyright (c) 2021 Mohit Agrawal, Pragyan Mehrotra, Rajesh Kumar, Rajiv Ratn Shah.

For license information, see LICENSE or http://mit-license.org
