---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.A. in Computer Science & Statistics, [Carleton College](https://www.carleton.edu/news/stories/carleton-moves-up-us-news-world-report-best-colleges-rankings/), 2023

Research experience
======
* June - September 2023: **Research Assistant**
  * *[UCLA RIPS REU](https://www.ipam.ucla.edu/programs/student-research-programs/research-in-industrial-projects-for-students-rips-2023-los-angeles/) - Los Angeles, CA*
  * Worked with the [Air Force Research Laboratory (AFRL)](https://www.afrl.af.mil/) to replace high-fidelity models that simulate the flow of supersonic air over a wedge with a faster, comparably accurate multi-fidelity model, resulting in 99\% percent faster runtime.
  * Combined two lower-fidelity models that utilized dimension reduction techniques (proper orthogonal and singular value decomposition) and numerically solved fluid dynamics equations into a more accurate surrogate model.
  * Reduced the runtime of AFRL's supersonic airflow modeling approach from 48 hours to 13 minutes.

* September 2022 - January 2023: **Research Assistant**
  * *Carleton College - Northfield, MN*
  * Implemented (1) a loss function that prioritizes fairness using a counterfactual fairness metric and (2) a counterfactual data augmentation method that mitigates bias in toxicity classification.
  * Utilized PyTorch to build, train, and evaluate a CNN for text classification from scratch. The CNN was trained with "word2vec" embeddings, then fine-tuned with a publicly available dataset of toxic comments.
  * The loss function improved fairness by up to 53\% and the data augmentation method  improved fairness by up to 70% compared to baseline models, and both methods maintained high accuracy. Our work shows the potential of counterfactual fairness as an effective approach for bias mitigation in NLP tasks.

* January - June 2023: **Research Assistant**
  * *Carleton College - Northfield, MN*
  * Analyzed the effectiveness of a set of statistics created in 2007 called "scagnostics" that measure statistical graphics and model fit.
  * Determined that scagnostics are up to 80% more effective at determining the fit of a model than classic statistics such as the variance and mean by implementing random forest, generalized additive, and support vector models.
  * Identified areas of weakness and quantified the robustness of the current set of scagnostics.
  * Generated robust training, testing, and validation datasets following data generation methods outlined in related literature.

* June - November 2021: **Research Assistant**
  * *Carleton College - Northfield, MN*
  * Developed an educational programming game using ReactJS and Typescript that studies how students learn coding concepts.
  * Constructed a building interface and connected it to a Flask database that stores various aspects of gameplay.

Professional experience
======
* August - 2023 - Present: **ML Engineer**
  * *[General Motors](https://www.gm.com/) - Austin, TX*
  * Designed and implemented an NLP pipeline to identify news articles that present risks to GM's supply chain. The pipeline includes a RoBERTa-based few-shot multi-class/multi-label (MCML) classifier, a NER model, and a sentiment analysis classifier.
  * Deployed the pipeline to production, where it is utilized by dozens of risk intelligence teams across the company, streamlining the identification of high-risk articles and almost completely removing the need for manual annotation and review.
  * Developed a RoBERTa-based topic modeling solution to identify emerging topics of interest for business teams, replacing a fine-tuned classification model that required regular manual updates. This reduced model maintenance by roughly 100 hours/week.
  * To enhance generalizability, I am developing separate NER and MCML models using prompt engineering with a 70B LLaMA model. This approach leverages LLMs to improve performance on low-resource entities and novel categories.
  
* May - August 2022: **Software Engineer Intern**
  * *[National Center for Atmospheric Research](https://ncar.ucar.edu/) - Boulder, CO*
  * Developed a new search engine for NCAR using Spring Boot and Solr that enables scientists to efficiently find scientific resources produced by each of NCAR’s seven research labs.
  * Ensured 100% accuracy for 20,000+ search results by implementing metadata validation using Spring Boot.
  * Improved the efficiency of metadata file deletion by up to 99%, allowing scientists to quickly delete outdated and incorrect files.

* August 2022 - August 2023: **Teaching Assistant**
  * *Carleton College, Department of Mathematics & Statistics - Northfield, MN*
  * Assisted up to ten students per day with data science, machine learning, and Bayesian statistics courses, primarily using R.
  * Collaborated with statistics professors and faculty to create and execute effective lesson plans.

* August 2020 - August 2023: **Career Counselor**
  * *Carleton College Career Center - Northfield, MN*
  * Coached up to ten students per day regarding cover letters, résumés, internships, jobs, and funding opportunities.
