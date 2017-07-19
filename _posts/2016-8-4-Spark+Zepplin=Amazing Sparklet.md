---
layout: post
title: Apache Spark + Apache Zeppelin = Amazing Sparklet
---

Its been a few months, since I started crawling on Spark. From hacks to install Spark on Windows 32 bit environment, to configuring a IDE - Eclipse, to running codes on the console. It has been a good learning experience.

Zeppelin, as described on the project page -  "A web-based notebook that enables interactive data analytics. You can make beautiful data-driven, interactive and collaborative documents with SQL, Scala and more".

This post is more about the advantages Zeppelin (Incubating in Apache) brings to Spark. Notebooks have been gathering a lot of traction made famous by the Jupyter iPython notebooks. However Jupyter does not easily support other interpreters except Python.
Zeppelin is trying to address that problem and is in the sweet spot of a notebook for Spark , and hence Scala, Python (pySpark), SQL (Spark SQL) become a native. It has has interpretors available for R which makes this an amazing combination to explore and experiement.


Sparklet (beta), is one such product by Mund Consulting which has a product for Windowx x64 and eliminates all the hasseles for making Spark work on Windows. This is by far the easiest and simplest way to get on Spark if you are running a Windows.To note that, this is good only for exploring, experimenting and prototyping.


![alt text](/images/zeppelin.PNG "Zeppelin Interpreter")

I ran a benchmark Decision Tree model to predict churn using a open dataset from the mapR distribution. (Details in the Github Repo Soon)
And boom.. The notebook runs the code and reports the results inline (similar to Jupyter) eliminating the hasseles of working on the console, or setting up an eclipse ide  involving configurations which take some serious time and effort to set up.

Going forward, this is one of my best tools to prototype and quickly try some new functionalities on Spark. All the current explorations on Spark is now being done on Sparklet.

Sparklet - <http://www.mund-consulting.com/Products/Sparklet.aspx> . As on August 8th, its running a 1.6 version of Spark. Looking forward that they update to latest 2.0 to bring in the DF API's in the newer releases.


