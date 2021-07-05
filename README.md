# Related Paper

**Paper title:**  A Comprehensive Study on Security Bug Characteristics

**Abstract:** Security bugs can catastrophically impact our increasingly digital lives. 

Designing effective tools for detecting and fixing software security bugs requires a deep understanding of security bug characteristics. In this paper, we conducted a comprehensive research on security bugs and proposed classification criteria for the four characteristics of category, root cause, consequence, and location. In addition, we selected 1076 bug reports from five projects (i.e., Apache Tomcat, Apache HTTP Server, Mozilla Firefox, Linux Kernel and Eclipse) in the NVD for investigation, and classified the above four characteristics and severity. Finally, we investigated the correlation between characteristics according to the classification results, and obtained some findings: 1) Memory operation is the most common security bug. 2) The primary root causes of security bugs are CON (Configuration Error), INP (Input Validation Error), and MEM (Memory Error); 3) The severity of more than 40\% of security bugs is high; 4) Security bugs caused by INP mainly occur on web; 5) Security bugs caused by LOG (Logic Resource Error) usually lead to DoS (Denial of Service). We discussed these findings through data analysis, which can also help developers better understand the characteristics of security bugs and further stimulate many related research needs.

# Introduction of dataset
In Security Bug Data Analysis Summary Table, we analyze 1076 security bugs between 2015 and 2019 in the NVD from five projects, i.e., Apache Tomcat, Apache HTTP Server, Mozilla Firefox, Linux Kernel and Eclipse. For the basic information of security bugs, we recorded the project, version, CVE ID and published date of each bug in the table. Then, we analyzed and classified all security bugs in four aspects, namely category, root cause, consequence, and location, and obtained their severity from NVD. In addition, if there is a patch-related website(Fixing link) in the reference links in the security bug report, we record it in the table too.

# Construction purpose

The reasons for constructing the dataset are as follows:

a)  Based on the analysis and classification results of the data, conduct empirical research on the characteristics of security bugs. 

b)  The construction of this dataset is conducive for developers to gain an in-depth and intuitive understanding of security bugs from different aspects. 

c)  The data set can help researchers to conduct in-depth research on  security bugs, such as mining the associations of various aspects of security bugs, etc.



