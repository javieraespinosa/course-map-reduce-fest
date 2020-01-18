---
widget: "blank" 
headless: true 
title: Challenges
weight: 50
---

{{% alert note %}}
Instructions for installing Hadoop:
* [Ubuntu](2013/04/installing-hadoop-ubuntu.pdf)
* [Mac](http://blog.tundramonkey.com/2013/02/24/setting-up-hadoop-on-osx-mountain-lion) ([initial config](http://borrelli.org/2012/05/03/hadoop-initial-configuration/)) 
{{% /alert %}} 

* **CH-1: Declarative approach for map-reduce**
	* First steps on counting: counting Facebook contacts using Pig [[pdf](2013/04/challenge-1.pdf)]

<!-- break -->

* **CH-2: Counting words and other summarization challenges**
	* Counting with some optimizations using combiners: understanding some principles of the map reduce model [[pdf](2013/04/hoop-ex-1.pdf)]
	* Hints on the first question [[pdf](2013/04/running-the-wordcount-example.pdf)]
	
<!-- break -->	
	
* **CH-3: More intensive summarization**
	* Median and standard deviation [[pdf](2013/04/ch-3a-summarisation.pdf)]
	* Inverted index summarizations [[pdf](2013/04/ch-3a-invertedindex.pdf)]
	
<!-- break -->
	
* **CH-4 Filtering patterns:** _Everyone has to program challenge 4b and each and then each remaining challenge can be addressed by at most two groups. Hurry choosing your challenge and notify it!_
	* Filtering [[pdf](2013/05/ch-4a-distributedgrep.pdf)]
	* Bloom [[pdf](2013/05/ch-4b-bloomfiltering.pdf)]
	* Top ten [[pdf](2013/05/ch-4c-toptenusersreputation.pdf)]
	* Distinct [[pdf](2013/05/ch-4d-distinctuserids.pdf)]
	
<!-- break -->
	
* **CH-5: Data organization patterns:** _Choose one of the following challenges. Each one can be assigned only to one person/group. __For your chosen challenge propose an alternative practical example where the pattern that you implemented can apply__._  
	* Structured to hierarchical [[pdf](2013/05/ch-5a-postcommentbuilding.pdf)]
	* Partitioning [[pdf](2013/05/ch-5b-partitioningusers.pdf)]
	* Binning [[pdf](2013/05/ch-5c-binninghadooptags.pdf)]
	* Total order sorting [[pdf](2013/05/ch-5d-sortusers.pdf)]
	* Shuffling [[pdf](2013/05/ch-5e-anonymizingcomments.pdf)]
	
<!-- break -->
	
* **CH-6: Join patterns:** _Choose one of the following challenges. Each one except number 1 can be assigned only to one person/group. __For your chosen challenge propose an alternative practical example where the pattern that you implemented can apply__._
	* Reduce side join classic and with bloom filter [[pdf](2013/04/CH-6a-UserCommentJoin.pdf)]
	* Replicated join [[pdf](2013/04/CH-6b-ReplicatedUserComment.pdf)]
	* Composite join [[pdf](2013/04/CH-6c-CompositeUserComment.pdf)]
	* Cartesian product [[pdf](2013/04/CH-6d-CommentComparison.pdf)]
	
	
