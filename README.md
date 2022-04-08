# Sagemath GSoC Proposal

**Sub-Org Name:** <br>
SageMath <br>

### Student Information
*Name*: Georgia Channing <br>
*Github*:  [georgiachanning](https://github.com/georgiachanning) <br>
*CV*: [Recent resume](https://github.com/georgiachanning/Resume/blob/master/gwcresume%20(1).pdf) <br>
*Email*: gchannin@vols.utk.edu <br>
*Timezone*: Eastern Daylight Time (UTC-4) <br>

### University Information 
*University Name*: University of Tennessee, Knoxville <br>
*Research Interests*: foundations of computer science, algorithms, bayesian optimization <br>
*Degree*: BSc 2022 -> PhD (to be completed circa 2027) <br>

**Code Contribution:** <br>
Tickets reviewed: <br>

## Proposal Information
### Proposal Title
Edge connectivity and edge disjoint spanning trees in digraphs 
### Proposal Synopsis
The current method used for finding edge disjoint spanning trees in directed graphs (digraphs) relies on mixed integer linear programming and it may fail on some instances. The problem has been fixed for undirected graphs, implementing a combinatorial algorithm. The goal of this project is to implement combinatorial algorithms for finding edge disjoint spanning trees in digraphs. We will particularly consider the following algorithms: <br>

[Harold N. Gabow: A Matroid Approach to Finding Edge Connectivity and Packing Arborescences. J. Comput. Syst. Sci. 50(2): 259-273 (1995)] (https://doi.org/10.1006/jcss.1995.1022) <br>

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







