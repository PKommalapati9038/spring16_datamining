PROJECT TITLE
ORGANIZING USER SRARCH HISTORY

# OVERVIEW
Users are incraesingly pursuing complex task-oriented goals on the Web, Such as making tarvel arrangements, managing finances or planning purchases. To this end, they usually braek down the tasks into a few co-dependent steps and issue multiple queries around these steps repeatedly over long periods of time.

# DATA
 Sources and wesites we reffered:
  http://java.sun.com
  http://www.sourcefordgde.com
  http://www.networkcomputing.com/
  http://www.roseindia.com/
  http://www.java2s.com/
References :
  J. Tee van, E. Adar, R. Jones, and M. A. S. Potts, “Information  reretrieval".
  A. Spink, M. Park, B. J. Jansen, and J. Pedersen, “Multitasking during Web search sessions ".
 

# RESEARCH QUESTIONS
It finds how signals from search logs such as query reformulations and clicks can be used together to determine the relevance among query groups.
  1.We motivate and propose a method to perform query grouping in a dynamic fashion.
  2.Our goal is to ensure good performance while avoiding disruption of existing user-defined query groups.


# ALGORITHMS
1.Page Rank Algorithms:
  PageRank is a probability distribution used to represent the likelihood that a person randomly clicking on links will arrive at any   particular page. PageRank can be calculated for collections of documents of any size. It is assumed in several research papers that   the distribution is evenly divided among all documents in the collection at the beginning of the computational process. The PageRank   computations require several passes, called "iterations", through the collection to adjust approximate PageRank values to more        closely reflect the theoretical true value.
2.Query Group creation with EM algorithm
  This algorithm is used to find the maximum likelihood estiamtes of parameters, and it performs two steps.
	E-Step : Creates function for exceptions using current estimates.
	M-Step : Computes the parameters maximizing the excepted log likelihood found on the 	E-step.

# MODULES AND ANALYSIS

  1. Query Group
       - A relevance measure that is robust enough to identify similar query groups beyond the approaches that simply rely on the              textual content of queries or time interval between them. 
  2. Search history
       -Each query group is a collection of queries by the same user that are relevant to each other around a common informational            need.
  3. Query Relevance and Search logs
       - 1.queries that frequently appear together as reformulations.
         2.queries that have induced the users to click on similar sets of pages. 
  4. Dynamic Query Grouping
       -One approach to the identification of query groups is to first treat every query in a user’s history as a singleton query             group, and then merge these singleton query groups in an iterative fashion.


# CODE AND APPLICATION
Languages used in our project :
    Front End                 :   HTML, Java, JSP,AJAX
    Scripts                   :   JavaScript.
    Server side Script        :   Java Server Pages.
    Database Connectivity     :   Mysql

# PROJECT MANAGEMENT

1.ANITHA RANI SURAM
  ROLE: Team Leader
  SKILL: Coding, Leadership, Communication, Scheduling.
2. PRAVEEN CHOWDARY KOMMALAPATI
  ROLE: Team member
  SKILL: Coding,Communication, Critical thinking.
3. SUDHIR PALLIKONDA
  ROLE: Team member
  SKILL: Coding, Communication, Management.

## DELIVERABLES AND CHECKPOINTS

Last Upadte : 8th March 2016
