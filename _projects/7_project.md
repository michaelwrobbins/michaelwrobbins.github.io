---
layout: page
title: <tt>microsynth</tt>
description:
img: 
importance: 7
category: Software
related_publications: true
---

<div style="font-size: 150%;"><code>Synthetic Control Methods with Micro- And Meso-Level Data</code></div><br>

The R package <code>microsynth</code> {% cite micro25 %} was developed for implementation of the synthetic control methodology for comparative case studies involving disaggregated (i.e., micro- or meso-level) data. The methodology implemented within microsynth is designed to assess the efficacy of a treatment or intervention within a well-defined geographic region that is itself a composite of several smaller regions (where data are available at the more granular level for comparison regions as well). The effect of the intervention on one or more time-varying outcomes is evaluated by determining a synthetic control region that resembles the treatment region across pre-intervention values of the outcome(s) and time-invariant covariates and that is a weighted composite of many untreated comparison regions. The microsynth procedure includes functionality that enables its user to (1) calculate weights for synthetic control, (2) tabulate results for statistical inferences, and (3) create time series plots of outcomes for treatment and synthetic control.<br>

The methodology employed in <code>microsynth</code> was originally presented in an article published in the <em>Journal of the American Statistical Association</em> {% cite jasa17 %}. The algorithm was recently updated to incorporate several improvements, including more robust omnibus testing {% cite jqc25 %}.<br>

<strong>Links:</strong>
<ul>
  <li><a href="https://cran.r-project.org/web/packages/microsynth/index.html">Download</a> (CRAN)</li>
  <li><a href="https://cran.r-project.org/web/packages/microsynth/microsynth.pdf">Package Documentation</a></li>
  <li><a href="https://cran.r-project.org/web/packages/microsynth/vignettes/introduction.html">Tutorial</a></li>
  <li><a href="https://doi.org/10.18637/jss.v097.i02"><em>Journal of Statistical Software</em> article</a></li>
  <li><a href="https://github.com/ssdavenport/microsynth">GitHub repository</a></li>
</ul>

<strong>Collaborators:</strong>
<ul>
  <li><a href="https://scholar.google.com/citations?user=CzqLKmgAAAAJ">Steve Davenport</a>, Uber</li>
  <li><a href="https://www.rand.org/about/people/g/ghosh-dastidar_bonnie.html">Bonnie Ghosh-Dastidar</a>, RAND Corporation</li>
  <li><a href="https://www.rand.org/about/people/k/kilmer_beau.html">Beau Kilmer</a>, RAND Corporation</li>
  <li><a href="https://scholar.google.com/citations?user=2PrvEnQAAAAJ">Roland Neil</a>, RAND Corporation</li>
  <li><a href="https://csgjusticecenter.org/people/jessica-saunders/">Jessica Saunders</a>, The Council of State Governments Justice Center</li>
</ul>
<br>
