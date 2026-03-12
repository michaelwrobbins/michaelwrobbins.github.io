---
layout: page
title: Nonprobability Methods
description:
img:
importance: 4
category: Topics
related_publications: true
---

Early in my tenure at RAND, I helped to develop methods for blending probability and nonprobability data. High quality sources of data for surveys (i.e., probability samples) often do not yield large enough samples when a remote segment of a population is targeted, and researchers often attempt to supplement those through nonprobability convenience samples. I originally explored these approaches for application to a survey of caregivers of veterans of the US Armed Forces who served following September 11, 2001--using a convenience sample of caregivers taken from the Wounded Warrior project {% cite jssm21 %}.

Motivated by the potential utility of nonprobability data, I was awarded a competitive NSF grant (Award #1837959, $991,127) to explore methods for producing generalizable inferences from highly non-representative big data sources (e.g., social media). The proposed case study involved using data from Twitter (i.e., tweets) to gauge public opinion on political candidates in real time during an election cycle. The difficulty of generalizing users of Twitter to a broader population is rooted in the fact that little is known about them---basic demographic characteristics that are usually used to develop survey weights (such as gender, age, race, education, etc.) are unknown for Twitter users. The proposed work involved designing and administering a survey to both a probability sample of the US population (collected through the NORC AmeriSpeak Panel) and a convenience sample of Twitter users (collected using a targeted advertising campaign on Twitter). The survey collected basic demographics along with political beliefs and social media usage patterns for the respondents.

First, the research team, which I assembled and led, applied the prior methods {% cite jssm21 %} to illustrate that it is possible to adjust the Twitter convenience sample to be representative of the broader population of US adults {% cite poq25 %}. We then used information available for all twitter users (i.e., their user profile and tweets) to develop proxies for their demographic and related characteristics. These proxies are developed by using regularized regression with survey characteristics as outcomes and 100,000+ indicators derived from the user profiles and tweets as predictors and are shown to closely replicate the intended characteristics. The Twitter sample when weighted to generalize to the broader population can be used to derive population benchmarks for these proxy variables. We then collected a "universe" of tens of thousands of Twitter users and employed sentiment analysis to quantify the degree of approval or disapproval expressed in their tweets towards presidential candidates in the 2020 election cycle. Fine-tuned large language models were shown to be highly effective at capturing benchmark sentiment scores {% cite pa25 %}. Using the population benchmarks of the proxy variables, the Twitter universe was weighted to generalize to the US adult population, enabling us to develop a Twitter-based estimate of political approval scores that is argued to be representative of the US adult population and can be tracked over time throughout an election cycle. We illustrated that this score (calculated using the weighted universe) mimics contemporaneous public opinion polling but is more responsive to major events such as presidential debates and the Capitol Hill riots of January 6, 2021.<br>

<strong>Collaborators:</strong>
<ul>
  <li><a href="https://www.rand.org/about/people/g/ghosh-dastidar_bonnie.html">Bonnie Ghosh-Dastidar</a>, RAND Corporation</li>
  <li><a href="https://scholar.google.com/citations?user=grBYjVUAAAAJ&hl=en">Max Griswold</a>, King County DCHS</li>
  <li><a href="https://www.rand.org/about/people/p/pollard_michael_s.html">Michael Pollard</a>, RAND Corporation</li>
  <li><a href="https://www.rajeevramchand.com/">Rajeev Ramchand</a>, RAND Corporation</li>
</ul>
<br>

