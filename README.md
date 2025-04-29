# AD688-Employability-sp25A1-Group6
Website: https://cyxnbnbnb.github.io/ad688-employability-sp25A1-group6/


EDA
First, the box plot "Salary Comparison: Remote vs. On-Site Jobs" shows salaries for On-Site, Hybrid, and Remote jobs. Remote jobs have a slightly higher median salary. On-Site jobs have the widest salary range and the most outliers, meaning pay can change a lot. Hybrid jobs have more stable salaries. This tells us Remote and Hybrid jobs are not paid less — they may even offer better pay.
Next, the "Average Salary by State" map shows big differences across the U.S. States like California, Washington, and Colorado have higher salaries, probably because of strong tech industries and high living costs. States like Mississippi and Alabama have lower salaries. New Jersey and Massachusetts also offer good pay because of finance, healthcare, and education jobs.
The bar chart "Top 10 Industries with Highest Salaries" shows the industries that pay the most. The top fields are Cybersecurity, AI, Data Privacy, and Green Jobs. Many jobs mix these areas and pay over $140,000, with some close to $155,000. This shows tech, security, and sustainability skills are in high demand.
Finally, the second box plot compares AI and non-AI industries. AI jobs have higher median salaries and better starting pay. Their salary range is also higher overall, while non-AI jobs have more extreme top earners. This shows AI skills usually bring better pay, but you can find very high salaries in both areas.

First, we used K-Means clustering with TF-IDF features to group job descriptions into four clusters. Then we made word clouds to see the top keywords in each group.
Cluster 0 is the biggest one. It shows common job words like “experience,” “data,” “business,” and “job.”
Cluster 1 is about cloud systems. Words like “cloud,” “oracle（/ˈɔrəkl）,”  appear a lot.
Cluster 2 focuses on SAP consulting, with words like “SAP,” “consultant,” and “hana.”
Cluster 3 is related to data analytics, with keywords like “data,” “analytics,” and “SQL.”
These word clouds help us quickly understand what each group is mainly about.
Next, we trained a Naive Bayes model to predict which cluster a job belongs to. The model reached 86% accuracy (ˈækjərəsi;) on over 14,000 job posts.
Cluster 1 had the best result — 91% precision and recall.
Cluster 2, even though it’s smaller, also had strong results — 90%.
Cluster 0 had slightly lower scores — 82% precision and 87% recall.
Cluster 3 was okay but a bit lower, maybe because some words are similar to Cluster 0.
Overall, the model did a good job and showed that different job types really do use different words.
Finally, we checked which words show up the most in all job descriptions. The top word was “data”, with over 10,000 mentions. That’s much more than the next word, “experience”, which appeared around 6,000 times. Other top words were “business,” “SAP,” and “job.” After the top few, the numbers drop fast.
This tells us that data and business skills are super common and important in job ads today.