# Labelled Hacker Dataset

The datasets contain social media posts hacker forums and hacker communication through the web. These posts are related to technical and personal references to computing, security, internet services, and technology. A minority proportion refer to malicious activities in software products or have mentioned security problems in software (flaws, vulnerabilities, proof of concept (PoC) ) or have offered exploitation tools for different software vulnerabilities.

In preparation of our data, we performed a **labelling task** in which computer science domain experts determine whether posts relate to software-vulnerability-related communication or not. The labels are:

- **Yes**: for posts that appears as malicious posts of vulnerabilities in software assets.  
- **No**: for posts not related to hacker activity or are out of the scope of our research  (Data  breach,  copyrighted  software  cracked,  stolen  accounts  and credit card accounts).  
- **Undecided**: for posts that the labeller does not have enough information or confidence to mark as Yes or No

These datasets were used to perform experiments with machine learning models aimed to detect hacker communication regarding software vulnerabilities. More on that can be read in the paper below:

1. [Eavesdropping hackers: Detecting software vulnerability communication on social media using text mining](http://www.thinkmind.org/download.php?articleid=cyber_2019_3_30_80058)



## Description

| Source | No. of Instances | % Pos | % Neg | % Undec | Avg. words | 
| --- | --- | --- | --- | --- | --- |
| Hacker Forum | 1,682 | 7 | 90 | 3 | 50
| Twitter |      1,927 | 12 | 85 | 3 | 13
| Marketplace |  1,921 | 12 | 84 | 4 | 169
| Hacker Forum | 1,966 | 11| 87 | 2 | 78
| Hacker Forum | 1,974 | 4 | 95 | 1 | 68

**Source** - From where the messages on the dataset were collected.

**No. of Instances** - The number of messages each dataset contains

**% Pos** - Percentage of positive instances

**% Neg** - Percentage of negative instances

**% Undec** - Percentage of Undecided instances

**% Avg. words** - The average number of words of a message in each dataset

# Citation

If you have used the above resource, please acknowledge the authors by citing:

**Queiroz, A.L., Mckeever, S., Keegan, B.: Eavesdropping hackers: Detecting software vulnerability communication on  social  media using text  mining. In: The Fourth International Conference on Cyber Technologies and Cyber-Systems. pp. 41-48 (2019)**

    @inproceedings{queiroz_eavesdropping,
	title = {Eavesdropping hackers: Detecting software vulnerability communication on  social media using text mining},
	isbn =  {978-1-61208-743-6},
	booktitle = {The Fourth International Conference on Cyber-Technologies and Cyber-Systems},
	author = {Queiroz, Andrei Lima and Mckeever, Susan and Keegan, Brian},
	year = {2019},
	keywords = {cyber security threat intelligence; software vulnerability; machine learning; text mining; social media, hacker communication},
	pages = {41--48}
	}
