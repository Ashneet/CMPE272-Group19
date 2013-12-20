README FILE

News Search for Mahout classified data facted search, by 
Ankita Kaul
Ashneet Kaur Lattar
Nisha Agarwal
Prerna Bhandari
[12/05/2013]

CONTENTS
I.	SOFTWARE REQUIREMENTS
II.     STEPS TO FOLLOW 

I. SOFTWARE REQUIREMENTS - 

1. JDK 7 
2. Ubuntu 12.0.4
3. Hadoop 1.2.1
4. Mahout 0.7
5. Tomcat 7
6. Solr 4.6.0
7. Drupal 7(Content Management Framework)

II. STEPS TO FOLLOW

1. Install ubuntu on your system.
2. Get JDK 7 on your system
3. Then perform Hadoop intallation 
4. Create single node cluster
5. Download and Install Mahout 0.7
6. Classify the dataset using Naive Bayes Classifier
7. To generate confusion matrix using Naive bayes classifier follow these steps( testing and training of data )
   i) mahout testnb\-i 20news-train-vectors\-m model\-l labelindex\-ow-o 20news-testing
   ii) mahout testnb\-i 20news-test-vectors\-m model\-l labelindex\-ow-o 20news-testing2 
8. Download and install Tomcat 7 
9. Further for performing faceted search install and configure Solr.

  
