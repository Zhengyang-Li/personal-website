---
title: Train service design in an urban rail transit line incorporating multiple
  service routes and multiple train compositions
publication_types:
  - "1"
  - "2"
authors:
  - Zhengyang-Li
  - Jun-Zhao
  - Qiyuan-Peng
publication_short: ""
abstract: This paper focuses on the train service design problem within a given
  period in an urban rail transit line, where multiple either full-length or
  short-turn service routes can be operated, and each service route can utilize
  one of several different train compositions. The problem lies on determining
  the turn-back stations, train composition and frequency of each service route
  operated on the line. Considering the interests of operators and passengers,
  we decompose the problem as two subproblems namely train service configuration
  and passenger assignment. The first subproblem is formulated as an integer
  linear programming model with the objective of minimizing operators’ cost.
  Given a train service scheme, the second subproblem is modelled as a
  capacitated continuous multi-commodity flow model to minimize passengers’
  waiting time cost and transfer cost. The optimal strategy is extended to
  determine the behaviour of passengers and capture the extra waiting time of
  passengers under capacity constraint. The two sub-models are weighted and
  integrated into a mixed integer nonlinear programming model, which is further
  transformed into a mixed integer linear programming model using a novel
  linearization method. By exploiting the special characteristics of the model,
  a tailored and easy to implement local search algorithm is developed to solve
  large-scale instances. Starting from the operator-optimum solution which can
  be easily obtained, the algorithm solves the two sub-models iteratively to
  search better solutions within a precalculated search range which is smaller
  than the complete feasible domain. Finally, different sizes of instances
  constructed from two urban rail transit lines are utilized to demonstrate the
  performance and practicability of the proposed approaches.
draft: false
featured: true
tags: []
slides: example
url_pdf: ""
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)"
  focal_point: ""
  preview_only: false
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: https://doi.org/10.1016/j.trc.2020.102959
publication: "Transportation Research Part C: Emerging Technologies"
projects:
  - example
date: 2021-01-25T00:00:00.000Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: ""
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
