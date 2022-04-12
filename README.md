# Sagemath GSoC Proposal

**Sub-Org Name:** <br>
SageMath <br>

## Personal
*Name*: Georgia Channing <br>
*Github*:  [georgiachanning](https://github.com/georgiachanning) <br>
*CV*: [Recent resume](https://github.com/georgiachanning/Resume/blob/master/gwcresume%20(1).pdf) <br>
*Email*: gchannin@vols.utk.edu <br>
*Timezone*: Eastern Daylight Time (UTC-4) <br>

*University Name*: University of Tennessee, Knoxville <br>
*Research Interests*: foundations of computer science, graph algorithms, bayesian optimization <br>
*Degree*: BSc 2022 -> PhD (to be completed circa 2027) <br>

## Background

***What are your technical skills, education, experience, etc. Especially make sure to explain with what level of mathematics you are comfortable with and on what level you would like to program.*** <br>
I have a Bachelor's degree from the University of Tennessee, Knoxville, though I previously studied at the Unviersity of Southern California and ETH Zürich. During the pandemic, I had to leave my position at ETH, and I returned to my state school. At the same time, I was hired full-time as a data scientist at the Center for Advanced Defense Studies (C4ADS), a data-driven thinktank in Washington, D.C.. During my studies, I have engaged in a fair amount of graduate coursework, including graduate-level Applied Combinatorics, Advanced Graph Algorithms and Optimization, Foundations of Computer Theory, Data Science for Big Data, and Applied Cryptography. I have also completed courses in Probability, Statistics, Discrete Math, and Linear Algebra. <br>

At this point, I am most comfortable programming in Python, though my Bachelor's degree was done entirely in C and C++. I am happy to code in either of these languages, and I would be excited to try to get the best of both worlds (abstraction and performance) by using a mix in my implementation. 

I am quite familiar with git and GitHub as I also work in Dr. Michela Taufer's lab on the implementation of neural architecture searches and Bayesian optimizations. I have also used Jira and other Scrum products extensively in my work at the Center for Advanced Defense Studies.
<br> <br>
***Who are you? What makes you the best person to work on this particular project? Your personal motivation?*** <br>
I hope to pursue a PhD in Algorithms, Combinatorics, and Optimization (ACO), and I believe that this project will be an opportunity for me to work on issues I am interested in while both being challenged and contributing to an open codebase. 

At the end of this school year (May), I will be leaving my current job as a Data Scientist before beginning a Staff Researcher position at Global COmputing Lab in the late summer. I want to be engaged on a technical project in that intermediate period, and I hope to bring new experience and knowledge back to my research in the fall. <br> <br>
***What platform and operating-system are you using on your computer? (Sage development is done best on Linux and OSX)*** <br>
I code on OSX, but I am also willing to use an AWS EC2 Linux instance if helpful. <br> <br>
***Are you or have you been engaged in other open-source projects?*** <br>
I am rather new to the open-source world, but I have worked on enhanced distance calculations and implementations for geopandas. I have also translated a C4ADS visualization library from R to Python. <br> <br>
***Do you code on your own pet projects?***<br>
Most of the coding I do outside of my job and school is coding for projects at the lab I work at. Frankly, I have been extremely busy the last two years so have had limited opportunity to work on coding projects outside of the ones I do for work, school, and research. <br> <br>
***Are you a Sage user, how long do you know Sage?*** <br>
I am a Sage user, but I have not used it extensively. I used SageMath while taking my graduate Advanced Graph Algorithms and Optimization course in 2019. My work since then has moved away from graph theory, but I would be very excited to refresh that knowledge and explore the field a bit more. <br> <br>


**Code Contribution:** <br>
Tickets reviewed: <br>
Not yet completed.

## Project
### Proposal Title
Edge connectivity and edge disjoint spanning trees in digraphs 
### Proposal Synopsis
The current method used for finding edge disjoint spanning trees in directed graphs (digraphs) relies on mixed integer linear programming and it may fail on some instances. The problem has been fixed for undirected graphs, implementing a combinatorial algorithm. The goal of this project is to implement combinatorial algorithms for finding edge disjoint spanning trees in digraphs. We will particularly consider the following algorithms: <br>

[Harold N. Gabow: A Matroid Approach to Finding Edge Connectivity and Packing Arborescences. J. Comput. Syst. Sci. 50(2): 259-273 (1995)](https://doi.org/10.1006/jcss.1995.1022) <br>

[Anand Bhalgat, Ramesh Hariharan, Telikepalli Kavitha and Debmalya Panigrahi: Fast edge splitting and Edmonds' arborescence construction for unweighted graphs. ACM-SIAM symposium on Discrete algorithms (SODA), pp 455-464, 2008](https://users.cs.duke.edu/~debmalya/papers/soda08-splitting.pdf)

## Schedule & Deliverables

### Project Preparation and Communication

#### Community Bonding (May 20-June 12)

During the community bonding period, I will study the SageMath code base, particularly the BLANK, and review the SageMath developer guidelines. To better understand and interact with the SageMath core development team, I will actively monitor and participate in the sage-devel and sage-coding-theory groups, though sage-coding-theory seems to be largely inactive. Additionally, I will communicate with my mentor to schedule frequent, recurring, and mutually convenient meetings throughout the summer. If there is a large time difference between my mentors and myself, I will adjust my schedule to ensure that our workdays overlap for at least a portion of each day. 

#### Phase 1: Literature Review and Preliminary Implementation (June 12-July 25)
##### Week 1-6
#### Phase 2: Efficiency Improvements and Testing (July 25-September 4)
##### Week 7-12
#### Phase 3: Final Code, Documentation, and Mentor Review Submissions (September 5-September 12)
##### Week 12-13


### Risk Management
#### Project Extension
In the case of early finish, I will attempt to implement the second combinatorial algorithm suggested for "edge connectivity and edge disjoint spanning trees in digraphs". SageMath will then have two implementations that users can choose from depending on their needs and efficiency requirements.







