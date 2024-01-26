## Q1 Research Question (RQ)
### Q1.1 Proposal description
- This research investigates the impact of generative AI technologies in the gig economy, using Fiverr's AI-based and non-AI-based illustration services as a case study to explore whether AI integration leads to changes in discrimination against service providers. It builds on existing discrimination studies, focusing on new AI-centric occupations and their relation to biases in race, gender, and other demographics. The study employs a methodology of scraping data from Fiverr, collecting information about gig titles, ratings, comments, and worker profiles. A key aspect involves labeling the perceived race and gender of gig workers using supervised machine learning techniques applied to their profile icons. The analysis will use statistical methods such as correlation analysis, multiple regression, and ANOVA to examine relationships between variables like race, gender, and AI usage, and their impact on gig ratings. This approach aims to understand how AI is reshaping employment and whether it exacerbates or mitigates workplace discrimination. The findings are expected to contribute to the development of more inclusive AI systems and inform policies for equitable treatment in digital work environments, ultimately exploring whether AI-centric occupations are leading to a more equitable workplace or hiding old biases.

### Q1.2 research question 1
- How might the incorporation of artificial intelligence into gig economy platforms influence the prevalence of discrimination faced by service providers - will it serve to mitigate discrimination, or might it amplify it?
 - **Inequality and discrimination in the online labor market: A scoping review**: [link to the paper](https://journals-sagepub-com.proxy.uchicago.edu/share/VEPU5GK3GMYTAPG4HBXJ?target=10.1177/14614448221151200)
 - **Bias in Online Freelance Marketplaces: Evidence from TaskRabbit and Fiverr**: [link to the paper](https://dl.acm.org/doi/10.1145/2998181.2998327)
 - **Racial Discrimination in the Sharing Economy: Evidence from a Field Experiment**: [link to the paper](https://www.aeaweb.org/articles?id=10.1257/app.20160213)

## Q2 Formulate as ML task
### Q2.1 Is it supervised or unsupervised learning?
A2.1 supervised

### Q2.2 If it's supervised learning, is it a classification (binary or multi-class) or regression task?
A2.2 multi-class classification

## Q3 Data
### Q3.1 Have you explored the data sources we provided on Canvas?
A3.1 yes

### Q3.2 Do you plan to use existing dataset or collect data by yourself?
A3.2 exsiting

### Q3.3 If you plan to use existing dataset, have you find any appropriate dataset?
A3.3 yes

### Q3.4 If it's supervised learning task, do you have label for the dataset?
A3.4 yes

## Q4 Any additional information you would like to provide?
I found several datasets for my project. However, I'm wondering how to choose between them - any criteria about that?

- https://susanqq.github.io/UTKFace/
- https://biometrics.cse.msu.edu/Publications/Databases/MSU_LFW+/
- https://github.com/joojs/fairface
- ***update: I've chosen FairFace as my image dataset!***
