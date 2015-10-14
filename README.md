DSCI6008: Special Topics in Data Science
===============================================================
**Instructors:**  
* [Alessandro Gagliardi](mailto:alessandro@galvanize.com)  
* [Nir Kaldero](mailto:nir@galvanize.com)  
* [Mike Tamir](mailto:mtamir@galvanize.com)  

**Class Location:** 44 Tehama St, 3rd Floor, Room 206
**Lab Time:** 2-4 weekdays  
**Class Time:** 4:00 to 5:20 PM M,T,Th,F  
**Office Hours:** Wednesday by Appointment    

- [Description of the Course](#description-of-the-course)
- [Structure of the Class](#structure-of-the-class)
- [Resources](#resources)
- [Grading](#grading)
- [Requirements](#course-requirements)
- [Schedule](#tentative-schedule)

Description of the Course
--------------------------------------------------------------  
**IBM WATSON & COGNITIVE COMPUTING** – This course will introduce you to the technologies behind IBM's Question Answering system known as Watson. We will see how the techniques and technologies employed by data scientists can be used to develop what IBM is calling "cognitive computing" representing a paradigm shift in how we use computers as significant as when programming languages were developed. By the end of this course, you will be able to employ the technologies behind Watson for your own (cognitive) computing task. 

### Prerequisites

* DSCI6003: Machine Learning and Data Analysis  
* DSCI6004: Natural Language Processing  
* DSCI6007: Distributed and Scalable Data Engineering  

Standards
--------------------------------------------------------------  
**By the end of this course, you will be able to:**

* Discuss the potential impact of cognitive computing on our world.
* Explain how Watson compares to other QA systems.
* Employ the development cycle used by IBM in the development of Watson.
* Reproduce the logic employed by the NLP stack in Watson.
* Utilize knowledge bases like [YAGO](http://www.mpi-inf.mpg.de/departments/databases-and-information-systems/research/yago-naga/yago/).
* Develop an application using [UIMA](https://uima.apache.org/).
* Develop a Type Coercian system for Question Answering.
* Build a Cognitive Application using Watson.
* Explain the process of extending a QA system like Watson to another domain.
* Employ Distributional Semantics and semi-supervised learning.

Structure of the Class
--------------------------------------------------------------  
This course will employ a ["flipped" classroom](http://en.wikipedia.org/wiki/Flipped_classroom) model. What that means is that lectures will take place *outside* of class, via the MOOC course developed by Drs. Alfio Gliozzo, Siddharth Patwardhan, Eric Brown, and Lilian Wu. Classroom time will be devoted to resolving questions that have arisen and, primarily, for doing project work. 

Typical preparation outside of class:  

1. Watch videos, read chapters, and complete workbooks
2. Ask questions and raise issues in Slack channel
3. Review Exercises

A typical class will follow this structure:  

1. Complete On Your Own (OYO) activity
2. Review and discussion of lecture materials
3. iRAT (individual Readiness Assessment Test)
4. tRAT (team Readiness Assessment Test)
5. Review RAT solutions
6. Ask clarifying questions about exercises
7. Exercises and Discussion

There will be a __final presentation__ to practice all the topics covered during the course. The final project and presentation will be individual.

#### RATs
The readiness assessment tests (RATs) are intended to ensure that students comprehended the material consumed between classes. Students unsure of their comprehension should bring questions to be addressed before the individual RAT. After each student has answered all the questions on the RAT individually, the class will split into teams of 3 or 4, who will then review their answers and attempt to reach consensus. Misunderstandings are often better addressed by peers. It is important that all members of each team understand the solution provided by their team. Finally, the answers to the questions will be gone over by the class, hopefully resolving any final misunderstandings before proceeding with the projects.

#### Exercises
The RATs are meant to assess the first three levels of [Bloom's Taxonomy](http://en.wikipedia.org/wiki/Bloom's_taxonomy#Cognitive), namely knowledge, comprehension, and analysis. The exercises are meant to develop the latter three levels: analysis, synthesis, and evaluation.

Grading
----------------------
Students will be graded according to their mastery of curriculum standards. Mastery is rated on a scale from 0 to 4:

0) Unknown <br>
1) Beginning <br>
2) Developing <br>
3) Accomplished <br>
4) Exemplary <br>

Every student is expected to achieve at least a 3 on all standards. We will be using Galvanize's Mastery Tracker which can be found at [students.galvanize.com](https://students.galvanize.com).

Resources
--------------------------------------------------------------  
The primary resource for this class will be the [Cognitive Computing MOOC](https://www-304.ibm.com/services/weblectures/dlv/protected/GateProt.wss?handler=LoginSSL&action=requestlogin&customer=watsonwww&offering=wtsn&curriculum=wtm1_cur&next_offering=wtm1) offered through the [IBM Watson Academy](https://www-304.ibm.com/services/weblectures/watsonacademy). Other resources including [YouTube Videos](https://www.youtube.com/playlist?list=PLT8KEDgXsE6R0prxxCEDLxxELbdKyE8qO) and [papers](http://researcher.watson.ibm.com/researcher/view_group_pubs.php?grp=2099) will be assigned during the course.

Course Requirements
--------------------------------------------------------------  
### Attendance
Students are required to attend every class. It is very important you attend each class. If you cannot, please let us know as early as possible. 

### Exercises  
Participation in and completion of exercises is a requirement for this course. Each unit includes exercises to provide practice applying techniques discussed in class and to reveal deficiencies in understanding in preparation for skills tests.  

## Academic Integrity
As per the University's [Academic Integrity Policy and Procedures](http://www.newhaven.edu/334887.pdf):
> The University expects that all students, graduate and undergraduate, will learn in an environment where they work independently in the pursuit of knowledge, conduct themselves in an honest and ethical manner and respect the intellectual work of others. Each member of the University community has a responsibility to be familiar with the definitions contained in, and adhere to, the Academic Integrity Policy. Students are expected to be honest in their academic work. 

Violations of the Academic Integrity Policy include (but are not limited to):

1. **Cheating** -- *i.e.* Don't read off of your neighbors exams
2. **Collusion** -- Group work is encouraged *exept on evaluative exams*. When working together (on exercises, *etc.*) acknowledgement of collaboration is required.
3. **Plagiarism** -- Reusing code presented in labs and lectures is expected, but copying someone else's solution to a problem is a form of plagiarism (even if you change the formatting or variable names).

Students who are dishonest in any class assignment or exam will receive an "F" in this course.

Tentative Schedule
--------------------------------------------------------------  
1. [Introduction to IBM Watson](week1/week1.md)
    1. The Jeopardy! Challenge
    2. Characteristics of Cognitive Computing
    3. The challenge of winning Jeopardy!
    4. Watson Architecture Overview
2. DeepQA Architecture
    1. Deep Question Answering Architecture
    2. Semantic Integration and Machine Learning
    3. Natural Language Processing
    4. UIMA at IBM Watson
3. Unstructured Information Management Architecture
    1. UIMA Overview & SDK Setup
    2. Annotators and Analysis Engines
    3. Collection Processing Engine
    4. Application Development
4. Structured Knowledge in IBM Watson
    1. The Use of Structured Knowledge in Watson
    2. Type Coercion
    3. Temporal and Spatial Reasoning and Evidence Diffusion
    4. Adapting Watson to Other Domains
5. Domain Adaptation Methodology
    1. Building Your Watson Cognitive Application
    2. Content Adaptation
    3. Training Adaptation
    4. Functional Adaptation
6. __NO CLASS —__ 🌽__Holiday__🌽
7. Distributional Semantics
    1. Linguistic Background and Latent Semantic Analysis
    2. Distributional Similarity and Taxonomy Induction
    3. JoBimText & Relation Extraction
    4. The Watson Knowledge Graph
8. Special Topics TBD by instructors and students
9. Final Presentations
