+++
title = "RA Work"
+++

#### Text Mining with Professors Chaney, Boehm and Lashkari
<div style="text-align: justify">


I have worked with Professors Thomas Chaney (University of Southern California), Johannes Boehm (Sciences Po) and Danial Lashkari (Boston College)
on their very long run growth project over the summer of 2021 and have been occasionally 
voluntarily contributing to the project since. In this role, I designed and built a end-to-end Entity
Linking pipeline (i.e. a Natural Language Processing pipeline which identifies
relevant entities in unstructured text and links them to a unique value in a knowledge base).

The pipeline I built, implemented in spaCy, relies on direct string matching and a Named Entity 
Recognition model for mention detection (identifying relevant words). It then uses multiple linking
components to effectively do the candidate generation and disambiguation steps. In particular, there 
is no large training dataset for our target knowledge base, so I make use Wikidata external 
identifiers to avoid the (costly) creation of custom data.

Since the pipeline is implemented as a spaCy project, it is installable through pip.
It is therefore easy to integrate into larger data processing pipelines.
</div>

#### Media Research with Professor Cagé
<div style="text-align: justify">


I have been working as a research assistant to Professor Julia Cagé
(Sciences Po) between May 2020 and June 2021. In this role, I have developed
a method to estimate media outlets' ad revenues using administrative and distribution data
 and have applied this method to over 190 outlets over more than 10 years. I have also
worked with the Facebook and CrowdTangle APIs quite extensively to collect data on
social media performance of traditional media outlets. 

In parallel to this data work, I have
written several python programs to augment Twitter user data with sociodemographic information.
In particular, I implemented machine learning techniques to predict users' genders and
geographic origin. I also developed a string matching algorithm to identify job positions
in user descriptions.
</div>