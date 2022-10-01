---
layout: page
title: About Me
description: Who I am, in more detail.
background: '/img/bg-about2.jpg'
---

```I'm a computer engineering student in my final year of studies. I am majoring in machine learning and data science (SCIA) at EPITA.```


---

## SKILLS
- Python (numpy, pandas, scikit-learn, scikit-image, Tensorflow, Keras, nltk, gensim, etc.)
- C, C++, Cuda
- Java, C#
- Scala, Spark, Kafka
- SQL, Neo4j
- Django, Jekyll, HTML, CSS, etc.
- Linux, Windows
- Git
- Basic TDD
- Matlab/octave
- Latex, Office (Word, Excel, PowerPoint, etc.)

---

## EXPERIENCE


####  Software Engineer at **SoundHound** <span style="float: right; ">Nov 2021-Present</span>
I currently work at [SoundHound](https://www.soundhound.com) as a C++ Software Engineer in Natural Language and Intent Understanding on the SoundHound assistant.
I build, improve and maintain domains people can use in their cars to, among other things, open a window, play music and make a phone call.
I use C++ (and occasionally Lua), and Object Oriented Programming paradigms to produce clean and efficient code allowing user to receive efficient, accurate and quick responses.


####  Data Science Consultant Intern at **enioka Consulting** <span style="float: right; ">Feb. 2021-Aug. 2021</span>
During my internship at [enioka Consulting](https://consulting.enioka.com/), I worked on optimizing the drying process at an asphalt
plant using Machine Learning techniques for a client of [enioka](https://consulting.enioka.com/)’s.
I started by **fetching the data** the client collects in their plants from a MongoDB database, **cleaning** it and **building a dataset**. I also took some time
to **understand the context of the project**: the asphalt drying process and the physical phenomena happening during it. This part is key if I am to build a model that truly reflects the situation. Then,
I started doing some **Data Exploration and Analysis**, to further understand
the process as well as the data-process relationship. During that step and among
other things, I was able to **isolate and handle the outliers** in my dataset. I was also
able to **detect the correlations** that exist between the different features which later
allowed me to select the best ones. In parallel, I was doing some **feature engineering** to create new features for important variables not in the dataset such as
energy efficiency. After that, I moved on to **building a model**, **training**, and
**validating** it. I repeated that process multiple times to **test different algorithms** and **select the one meeting the performance threshold** (I had previously
set) the best. Then, I worked on **optimizing** the selected model. And finally
I **evaluated** it (on a test dataset) and its ability to solve the optimization problem.


I also worked on two other consulting projects for another client, France’s leading pickup point network. The first one consisted of
**consulting** on the subjects of **Data Architecture and Governance**. The client,
adopting a data driven approach, needed to migrate towards a more sustainable
architecture that is better adapted to their data needs. They also needed advice
on how to organize and manage their data teams.
The second one consisted of
**consulting in Data Science** and dealt with another part of the life cycle of a machine learning project : **retraining and optimization** (after deployment). [enioka
consulting](https://consulting.enioka.com/) had done a Machine Learning project for the client, that predicts resiliating parcel pickup and dropoff points, in 2019. After retraining with the 2020
data, the model performed worse. I was tasked with investigating the drop in
performance and testing new approaches to achieve better results. I worked on increasing the confidence in drop off/pickup Point Cancellation Detection model, by rethinking the context and
changing the training approach. The number of phone calls the could make was lower than the number of point resiliation we were predicting which meant that by limiting myself to phone call capacity of the client (or a bit more), I could sacrifice overall precision and prioritize recall. In other words, I didn't need to detect absolutely all resiliating points (precision), I only needed to detect a limited amount (the amount equal to the number of phone calls the client can make) but with very high confidence (recall). This meant that the client was able to make more meaningful phone calls and thus better capitalize on the practice.

Technologies used: Python (scikit-learn, pandas, numpy, matplotlib, etc.), MongoDB.


#### Intern at **enioka Haute Couture** <span style="float: right; ">Sept. 2019-Dec. 2019</span>
During my internship at [enioka Haute Couture](https://haute-couture.enioka.com/), I was the sole intern working on [ComDaAn](https://framagit.org/ervin/ComDaAn).
[ComDaAn](https://framagit.org/ervin/ComDaAn) previously used git repositories to visualize the corresponding community's activity, size, network and member centrality.

My work* consisted of **adding mailing lists and GitLab issues as additional data sources** and the option for an issue response analysis.
I also worked on **multiprocessing** the time consuming operations and on **integrating LOWESS regressions** for the curves in the project.
Finally, I **reworked the code to follow an OOP logic**, **renovated the project's API** to better suit the needs of its target users and added a **test suite**.

Being the only intern working on the project, I benefited from a **fair amount of autonomy** regarding project management and decision making.

Technologies used: Python (pandas, numpy, networkx, bokeh, etc.)

*More information on my work on the project can be found in my blog post: [Tooling For Community Data Analytics](http://chzn.fr/blog/tooling-for-community-data-analytics) which is about the state of the project after my changes.


---

## EDUCATION

#### EPITA <span style="float: right; ">Sept. 2018- July 2021</span>
**Diplôme d’ingénieur**  
[EPITA](https://www.epita.fr/) or  École Pour l'Informatique et les Techniques Avancées is a french computer engineering school. I joined it in 2018 and **graduated in 2021**.
I was an **active member in multiple associations** that promote acceptance, openness and multiculturalism.


#### ESIB <span style="float: right; ">Sept. 2015- July 2018</span>
**Bac+3**
[ESIB](https://esib.usj.edu.lb/) or École Supérieur des Ingénieurs de Beyrouth is an engineering school in Lebanon. I joined it in 2015 for my **"classes préparatoires"** which are mandatory pre-engineering classes in the french system that span over two years. I have also done **a year of computer engineering** in ESIB before deciding to move to France and tranfer to EPITA.  


#### Soeurs des Saints-Coeurs Sioufi  <span style="float: right; ">Sept. 2000-June 2015</span>
**From kindergarten to High School**
Soeurs des Saints-Coeurs Siouf or SSCC Sioufi for short is a french school in Lebanon. It is where I've gotten my primary, complementary and secondary education.
I've completed a **Baccalauréat Scientifique** with a specialty in mathematics, and got a **Mention Bien** at the official exams.

---

## PROJECTS
#### ComDaAn - Data Analytics <span style="float: right; ">Sept. 2019-Dec. 2019</span>  
[ComDaAn](https://framagit.org/ervin/ComDaAn) is a suite of tools for analyzing the data produced by FOSS communities. It relies mainly on the pandas, numpy, networkx and bokeh libraries.

#### **Analysis of weak signals in medical reports**  <span style="float: right; ">2020-2021</span>
In a group of five, for our end of studies project, we worked with French GP practices to create a slotution to **cluster french medical reports** and **extract the theme** of each cluster. Using their data, we were to come up with different approaches to solve the problem and evaluate them; we were to present the practices with either an efficient solution or the conclusion that an unsupervised approach isn't adapted to the data and issue at hand.
a

We used a **multitude of NLP** tools to determine the most efficient approach such as, but not limited to:
- Text processing: stemming and lemmatization;
- Embeddings: TF-IDF, Doc2Vec and Word2Vec;
- Algorithms: LDA, DBSCAN, Agglomerative Clustering and Kmeans.


Technologies: Python, pandas, numpy, nltk, gensim, scikit-learn, etc.

### NYPD - Parking violations <span style="float: right; ">2020</span>  
In a group of five, we were to handle the **analysis and storage** of millions of NYPD parking tickets. We also simulated drones sending alerts to handle them in **real time in a stream** and display them on a **website** we created.

Technologies: Scala, Spark, Kafka, SQL.

### WMH Segmentation challenge <span style="float: right; ">2021</span>  
In a group of five, we were to use deep learning approaches to **segment White Matter Hyperintensities**. We implemented the **2D U-Net model** in the [Fully Convolutional Network Ensembles
for White Matter Hyperintensities Segmentation in MR Images](https://arxiv.org/pdf/1802.05203.pdf) paper (ranked second) and **evaluated its performance** with and without data preproprecing. We also **adapted it to a 3D input** using convultions at the begining of the network to see how it would affect results.

Technologies: Python, Tensorflow/Keras.

#### **Spell Checker**  <span style="float: right; ">2020</span>
For a Text Mining and Natural Language class, we implemented, in a group of three, a spell checker **based on a Trie** data structure and using the **Damerau–Levenshtein distance**.
The search for the results had to happen under **time and memory constraints** which meant memory mapping and management had to be handled deftly.

Technologies: C++, Python for validation testing, Memory profiling tools, etc.


#### **Azure ChatBot** <span style="float: right; ">2020</span>
Using the various **Congnitive Services on Azure**, in a group of 5 we built a **conversational chatbot** with built-in **Speech-to-Text** and **Text-to-Speech** features.
It used the NASA FAQs to build a knowledge base to answer questions about space and the climate.
When the bot couldn't find an answer to a question asked in its knowledge base, it would search for it on the internet.

Tools: The Azure cloud platform with a focus on Azure Cognitive Services (QnAMaker, Azure Bot Service, Azure Speech Service, Azure Search, etc.)

### **TC - Tiger Compiler** <span style="float: right; ">2019</span>  
TC is a project done in a group of 4 students.
It is a **full front end compiler** with a **lexical, syntactic and semantic analysis** of the Tiger language (a purely pedagogical programming language).
The lexer and parser for the compiler were written using Flex and Bison and the AST, binder and type-checker in C++.

Technologies: C++, Flex/Bison.

---

## Extracurricular

- EMT in the Lebanese Red Cross.<span style="float: right; ">2017-2018</span>
- Model UN delegate and then advisor in the GCLAUMUN.<span style="float: right; ">2014-2018</span>
