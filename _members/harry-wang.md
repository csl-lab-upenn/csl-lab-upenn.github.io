---
name: Harry Wang
image: images/HarryWang.jpeg
role: masters
group: alum
job: Machine Learning Engineer, Pinterest
links:
  twitter: https://twitter.com/shantenuagarwal
  linkedin: https://www.linkedin.com/in/harry-w-680615126/
  github: https://github.com/harryw1248
  email: harrywang1248@gmail.com
  orcid: 0000-0003-0073-914X 
---

Harry’s research with Sharath and Lyle at Penn broadly involved developing and applying techniques in Machine Learning, Natural Language Processing, and Data Science to study problems related to Misinformation and Mental Health. 

A Weakly-Supervised Iterative Graph-Based Approach to Retrieve COVID-19 Misinformation Topics
We developed BERT-based Multi-directional Word Graph Search (BMDWGS) based on the BERT-based Word Graph Search (BWGS) algorithm to help retrieve COVID-19 Misinformation Topics by using BERT-embeddings to construct word graphs based on semantic similarity. We also utilize Latent Dirichlet Allocation (LDA) topic modeling for obtaining misinformation-related themes from the texts returned by our graph-based algorithms. Detecting misinformation amidst dynamically changing information landscapes is challenging. Identifying relevant keywords and posts is arduous due to the large amount of human effort required to inspect the content and sources of posts. We aim to reduce the resource cost of this process using our approach, which requires only a few seed texts and seed words, making it viable in low-data resource settings. This makes our approach easily automated and scalable. Our approach is also valuable in curating datasets to cover relevant themes, which helps with training downstream machine learning models.

Using Text-Message Data to better Predict and Quantify Mental Health Disorders, such as Depression, Anxiety, and Sadness
Using Linguistic Inquiry and Word Count (LIWC), NRC Emotion Lexicon, and previously established depression and stress dictionaries, we evaluated the degree to which language features predict symptoms of depression, generalized anxiety, or social anxiety. We used Hierarchical (Mixed-Effect) Linear Models, as well as Stagewise Machine Learning models to analyze the relationship between different LIWC, NRC word categories and mental health disorders. This allowed us to build easily interpretable models that complied with privacy regulations of not being able to view participants’ exact text messages. We expanded our study by analyzing the differences in language usage of depressed individuals when communicating with close contacts vs. non-close contacts. 

Discovering Meaningful Subgroups/Subpopulations and Analyzing Differences in Depression Model Performance on these groups
We developed and utilized a novel Regression-Based clustering algorithm to answer the question, “What constitutes meaningful subpopulations?” This goes beyond dividing our dataset by one singular feature such as age, race, income, education, etc. There could be sets of features that are shared between meaningful subgroups. We discovered these meaningful subgroups through Clustering, using both standard and custom-distance-measurement based approaches. After obtaining clusters, scientists and demographers can “tell stories” about each cluster. We analyzed the differences in performance of depression prediction models on each subpopulation. Additionally, we analyzed differences in clustering and model performance results before and after adding cellphone sensor behavioral data into our approach to explore the importance and impact of behavioral traits versus “inherent” demographic traits.
