---
layout: page
title: Missing Data
description: 
img: 
importance: 2
category: Topics
related_publications: true
---

My postdoctoral work involved the creation of an algorithm for imputation of missing data in a large agricultural survey (i.e., the USDA's Agricultural Resource Management Survey). This work presented unique challenges due to the size and distributional structure of the dataset, and yielded several publications {% cite ajae11 jasa13 arer14 jos14 %}. The resulting algorithm contained several novel characteristics to facilitate theoretically valid and computationally efficient imputation with complex data, including copula modeling via transformation using empirical distributions, creative use of the SWEEP operator to improve efficiency, and construction of a joint model via a sequence of selected conditional models.

Motivated by specific issues encountered when performing imputation in a large Department of Defense survey while at RAND, I later generalized the above procedure to produce the GERBIL algorithm {% cite jssm24 %}, which is available in the R package <code>gerbil</code> {% cite gerbil23 %}. By using a latent multivariate Gaussian model with probit-type assumptions for non-continuous variables, this method can create imputations in data of a general form (with continuous, binary, unordered categorical and ordinal variables) while using joint modeling in a highly computationally efficient manner and enables flexibility when constructing the imputation model. It is shown to outperform other state-of-the-art procedures in terms of both quality of imputations and computational burden. 

Variance estimation in the presence of imputed data typically relies on algebraic expressions and the validity of multiple imputation combining rules. To improve the utility of imputed data in a more broad array of settings, I recently developed the theory that underpins the use of resampling procedures such as a bootstrap or jackknife with imputed data {% cite biomet25 %}. This work illustrates the vast computation burden required for resampling procedures with imputed data, which emphasizes the value in efficient algorithms such as <code>gerbil</code>. 
<br>

<strong>Collaborators:</strong>
<ul>
  <li><a href="https://www.rand.org/about/people/b/burgette_lane_f.html">Lane Burgette</a>, RAND Corporation</li>
  <li><a href="https://statistics.sciences.ncsu.edu/people/sghosh2/">Sujit Ghosh</a>, NC State University</li>
  <li><a href="https://experts.okstate.edu/jhabige">Joshua Habiger</a>, Oklahoma State University</li>
  <li><a href="https://sites.google.com/site/tkirkwhite/">Kirk Whited</a>, Census Bureau</li>
</ul>
<br>
