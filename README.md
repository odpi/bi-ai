_This SIG was name BI & Data Science SIG. Due to shifting of the industry trend from Data Science which is more academic to AI, we change the name to BI & AI SIG on 2018-05-02_

# Mission
* Increase the interoperability for the BI vendors on Hadoop
* Propose an objective benchmark to evaluate the effectiveness of BI Tools on Hadoop
* Promote practical guidelines on how to run AI model on Hadoop

# How to reach us
* Subscribe our mailing list for this SIG: https://lists.odpi.org/g/odpi-project-bi-ai
* Request access to Google Doc https://drive.google.com/open?id=1fjFG-UqjMxnzmXUgWGM8mok-NSPF_g4ARIuhw8iXyIc of which we will use to collaborate for our first deliverable.
* Most communication will be done by email and will minimize conference call meeting due to busy schedule of the members and hard to come up with a common time across different time zones

# Meeting Notes
* [2020-06-12 Meeting Recording](https://web.microsoftstream.com/video/31164ade-eb26-4654-a173-66a68413022b)
* [ODPi BI & Data Science SIG 2nd Deliverable Discussion 2018-01-31](meetings/ODPi-BI-&-Data-Science-SIG-2nd-Deliverable-Discussion-Minutes-2018-01-31.md)
* [2017-03-15 Meeting Minutes](meetings/BI-&-Data-Science-SIG-Meeting-Minutes-2017-03-15-4:30PM-EST.md)
* [Kickoff Meeting 2017-02-20](meetings/BI-&-Data-Science-SIG-Meeting-Minutes-2017-02-20-2PM-EST.md)
* [Communication Archive](https://lists.odpi.org/g/odpi-project-bi-ai/topics)

# Introduction
Technology around Business Intelligence (BI) has been developed since 1990s. Most of the BI tools was built because of the sprout of Relation Database Management System (RDBMS). After many years of development and evolution, BI is now a pretty mature area that most modern corporations embrace.

As Hadoop becomes more and more popular, organizations start to invest on this new technology in the hope of gaining more business value. Though there are a lot of fundamental differences between traditional RDBMS and Hadoop, they also have a lot of similarities. Moreover, it’s almost impossible for existing BI vendors to ignore RDBMS to dive completely into Hadoop. Hence considering both in the roadmap is inevitable.

Therefore this SIG is help for bridging the gap so that BI Tool can sit harmoniously on top of Hadoop and RDBMS, yet providing the same, or even more, business insight to the BI users who has also Hadoop in the backend. From BI Vendor perspective, this SIG should help to find out an effective way for connecting and querying Hadoop without reinvent the wheel. From BI user perspective, this SIG should help to provide an objective guideline for evaluating the effective of a BI solution, and/or other related “middleman” technologies such as Apache Hive, Apache Drill, Presto, Apache Impala, Apache Phoenix… etc

Finally, AI models can now run on Hadoop much more cost effective than years ago. This results in fostering the convergence of traditional BI and AI disciplines (Machine Learning, Deep Learning... etc). Hence, this SIG will also explore how this phenomenon is going to impact the Hadoop standard.

# SIG membership
* Cupid Chan, 4C Decision (SIG Champion)
* Roman Shaposhnik, Linux Foundation
* Alan Gates, Hortonworks
* Ganesh Raju, Linaro
* Raj Desai, IBM
* Tanping Wang, IBM
* Tim Thorpe, IBM
* Nitin Lamba, Ampool
* Frank McQuillan, Pivotal
* Moon Soo Lee, ZEPL
* Jared Dean, SAS
* Bikas Saha, Hortonworks
* Chris Larsen, Qlik
* David Freriks, Qlik
* Hugo Sheng, Qlik
* Ben Reyes, MicroStrategy
* David Abbott, iFusion Analytics
* Jeff Bailey, SAS
* Gerard Valerio, Tableau

# Deliverable
* Standardize a guideline for vendor so that they know how to put up a data science notebook
* Strengths and Weaknesses comparison
* Recommendation of when to use what
* So far, we have only 2 tools for comparison: Jupyter and Zeppelin
