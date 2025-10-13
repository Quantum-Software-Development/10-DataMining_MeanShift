`<br>

**\[[🇧🇷 Português](README.pt_BR.md)\] \[**[🇺🇸 English](README.md)**\]**

<br><br>



#  <p align="center"> 10- [Data Mining]() /  [Main Shift]()



<!-- ======================================= Start DEFAULT HEADER ===========================================  -->

<br><br>


[**Institution:**]() Pontifical Catholic University of São Paulo (PUC-SP)  
[**School:**]() Faculty of Interdisciplinary Studies  
[**Program:**]() Humanistic AI and Data Science
[**Semester:**]() 2nd Semester 2025  
Professor:  [***Professor Doctor in Mathematics Daniel Rodrigues da Silva***](https://www.linkedin.com/in/daniel-rodrigues-048654a5/)

<br><br>

#### <p align="center"> [![Sponsor Quantum Software Development](https://img.shields.io/badge/Sponsor-Quantum%20Software%20Development-brightgreen?logo=GitHub)](https://github.com/sponsors/Quantum-Software-Development)


<br><br>

<!--Confidentiality statement -->

#

<br><br><br>

> [!IMPORTANT]
> 
> ⚠️ Heads Up
>
> * Projects and deliverables may be made [publicly available]() whenever possible.
> * The course emphasizes [**practical, hands-on experience**]() with real datasets to simulate professional consulting scenarios in the fields of **Data Analysis and Data Mining** for partner organizations and institutions affiliated with the university.
> * All activities comply with the [**academic and ethical guidelines of PUC-SP**]().
> * Any content not authorized for public disclosure will remain [**confidential**]() and securely stored in [private repositories]().  
>


<br><br>

#

<!--END-->




<br><br><br><br>



<!-- PUC HEADER GIF
<p align="center">
  <img src="https://github.com/user-attachments/assets/0d6324da-9468-455e-b8d1-2cce8bb63b06" />
-->


<!-- video presentation -->


##### 🎶 Prelude Suite no.1 (J. S. Bach) - [Sound Design Remix]()

https://github.com/user-attachments/assets/4ccd316b-74a1-4bae-9bc7-1c705be80498

####  📺 For better resolution, watch the video on [YouTube.](https://youtu.be/_ytC6S4oDbM)


<br><br>


> [!TIP]
> 
>  This repository is a review of the Statistics course from the undergraduate program Humanities, AI and Data Science at PUC-SP.
>
> ### ☞ **Access Data Mining [Main Repository](https://github.com/Quantum-Software-Development/1-Main_DataMining_Repository)**
> 
>  If you’d like to explore the full materials from the 1st year (not only the review), you can visit the complete repository [here](https://github.com/FabianaCampanari/PracticalStats-PUCSP-2024).
>
>



<!-- =======================================END DEFAULT HEADER ===========================================  -->


<br><br><br><br>


## Table of Contents

- [Introduction](#introduction)
- [What is Mean Shift?](#what-is-mean-shift)
- [Average Displacement Explained](#average-displacement-explained)
- [Implementation Overview](#implementation-overview)
- [Applications and Market Uses](#applications-and-market-uses)
- [Comparison with K-Means](#comparison-with-k-means)
- [Use Cases](#use-cases)
- [Video Application: Object Tracking and Face Recognition](#video-application-object-tracking-and-face-recognition)
- [Image: Mean Shift Flow](#image-mean-shift-flow)


<br><br>

## [Introduction]()

<br>

This repository contains a detailed study and implementation of the Mean Shift clustering algorithm focusing on its average displacement mechanism. Mean Shift is an unsupervised learning algorithm widely used for discovering clusters in a dataset, especially when the number of clusters is unknown a priori. The algorithm finds high-density regions by iteratively shifting points towards the densest areas in the feature space.


<br><br>


## [What is Mean Shiftv ?]()

Mean Shift is a non-parametric, iterative procedure that seeks the modes or peaks in the probability density function of the data. Unlike other clustering algorithms that require specifying the number of clusters (such as K-Means), Mean Shift identifies clusters based on data distribution density, making it flexible to arbitrary cluster shapes and robust against outliers.


<br><br>

## [Average Displacement Explained]()

The core concept of Mean Shift revolves around "average displacement" — iteratively computing the center of mass (mean) of data points within a window (kernel) around each candidate point and shifting the point to this new average position.

<br>



[The algorithm can be summarized in steps]():

<br>


1. [**Initialization:**]() Consider each data point as a potential cluster center.

2. [**Density Estimation:**]() For each point, define a window (kernel) with a bandwidth radius and calculate the mean of points within this window.

3. [**Shift:**]() Move the point to the calculated mean position, effectively shifting it towards higher data density.

4. [**Convergence:**]() Repeat the steps of estimating and shifting until the movement (displacement) between iterations falls below a threshold, indicating convergence at a local density maximum.


<br><br>


#### [Mathematically](), given a point \$x \$, the mean shift vector \$m(x)\$ at iteration \$t\$ is:

<br><br>


$$
\Huge
m(x^{(t)}) = \frac{\sum_{x_i \in N(x^{(t)})} K(x_i - x^{(t)}) x_i}{\sum_{x_i \in N(x^{(t)})} K(x_i - x^{(t)})} - x^{(t)}
$$

<br><br>

#### [Where](): \$N(x^{(t)})\$ is the neighborhood within bandwidth, and \$K\$ is the kernel function weighting points by proximity. The new position is then:

<br><br>

$$
\Huge
x^{(t+1)} = x^{(t)} + m(x^{(t)})
$$

<br><br>











































<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>
<br><br>


<!-- ========================== [Bibliographr ====================  -->

<br><br>


## [Bibliography]()

[1](). **Castro, L. N. & Ferrari, D. G.** (2016). *Introduction to Data Mining: Basic Concepts, Algorithms, and Applications*. Saraiva.

[2](). **Ferreira, A. C. P. L. et al.** (2024). *Artificial Intelligence – A Machine Learning Approach*. 2nd Ed. LTC.

[3](). **Larson & Farber** (2015). *Applied Statistics*. Pearson.


<br>

### [Complementary Bibliography]()

- THOMAS, C. *Data Mining*. IntechOpen, 2018.  
- HUTTER, F.; KOTTHOFF, L.; VANSCHOREN, J. *Automated Machine Learning: Methods, Systems, Challenges*. Springer Nature, 2019.  
- NETTO, A.; MACIEL, F. *Python para Data Science e Machine Learning Descomplicado*. Alta Books, 2021.  
- RUSSELL, S. J.; NORVIG, P. *Artificial Intelligence: A Modern Approach*. GEN LTC, 2022.  
- SUD, K.; ERDOGMUS, P.; KADRY, S. *Introduction to Data Science and Machine Learning*. IntechOpen, 2020.




<br><br>

      
<!-- ======================================= Bibliography Portugues ===========================================  -->

<!--

## [Bibliography]()


[1](). **Castro, L. N. & Ferrari, D. G.** (2016). *Introdução à mineração de dados: conceitos básicos, algoritmos e aplicações*. Saraiva.

[2](). **Ferreira, A. C. P. L. et al.** (2024). *Inteligência Artificial - Uma Abordagem de Aprendizado de Máquina*. 2nd Ed. LTC.

[3](). **Larson & Farber** (2015). *Estatística Aplicada*. Pearson.


<br><br>
-->

<!-- ======================================= Start Footer ===========================================  -->


<br><br>


## 💌 [Let the data flow... Ping Me !](mailto:fabicampanari@proton.me)

<br><br>



#### <p align="center">  🛸๋ My Contacts [Hub](https://linktr.ee/fabianacampanari)


<br>

### <p align="center"> <img src="https://github.com/user-attachments/assets/517fc573-7607-4c5d-82a7-38383cc0537d" />




<br><br><br>

<p align="center">  ────────────── 🔭⋆ ──────────────


<p align="center"> ➣➢➤ <a href="#top">Back to Top </a>

<!--
<p align="center">  ────────────── ✦ ──────────────
-->



<!-- Programmers and artists are the only professionals whose hobby is their profession."

" I love people who are committed to transforming the world "

" I'm big fan of those who are making waves in the world! "

##### <p align="center">( Rafael Lain ) </p>   -->

#

###### <p align="center"> Copyright 2025 Quantum Software Development. Code released under the [MIT License license.](https://github.com/Quantum-Software-Development/Math/blob/3bf8270ca09d3848f2bf22f9ac89368e52a2fb66/LICENSE)













