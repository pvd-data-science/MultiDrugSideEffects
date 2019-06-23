# MultiDrugSideEffects
Identify potential side effects of taking multiple prescriptions. 

Summary: 
Repeat analysis published in a recent  paper by Stanford that predicted potential side effects of drug combinations. 
	• First objective will be to “learn by doing” using their methodology, then add something new like different algorithms, features, or different technologies.
	• Second objective will be to identify potential negative side effects for the various long term medication I personally take.

Contribution:
    • Maybe I’ll be able to make some incremental contribution to the topic. 
 
Approach:
	• Use data and Python code published by researchers. http://snap.stanford.edu/decagon.
	• See if additional demographic info may be available on patients reporting side effects to add features. 
	• Experiment with alternative technologies and/or algorithms to see if I can achieve higher accuracy or faster processing etc.

Challenges:
    • They May have had access to better technologies than I’ll be able to use.
 

Effort 01  
Objective: Identify a viable project to work on, while simultaneously attaining some new relevant knowledge.
	1. A project candidate.
		○ I recall hearing a professor on a data science podcast talking about a PhD student that produced a pretty significant finding regarding potentially negative and serious side effects of certain combinations of prescription medications using publicly available data. 
		○ Apparently there are over 5000 prescription medications on the market, and for the most part little is known about potential side effects resulting from their interactions. It's not feasible for drug manufacturers to test every combination as they bring new drugs to market.  We learn about them as the general public consumes them in various combinations and suffers side effects.
		○ I like the topic because the general public can relate to the concern about potential interactions when they, including myself, take multiple medications on a daily basis.  
			§ I'd like to know specifically if anything was discovered about combinations of the half dozen medications I take.  
			§ If the scope of the data needs to be scaled back to reduce computing requirements, I can restrict the data to those of interest to me. However, I would also need to include other drugs with similar characteristics too.  The point of the research is to predict unknown side effects for Drug X by associating or classifying it with drugs having known side effects.  
			§ Spoiler: I already saw in an article written about this research that two of my medications have a potentially serious muscular reaction.  Luckily I can't remember which ones they are, so maybe it won't be too much of a spoiler.
	2.  The education component.
		○ On recommendation of the group, I've decided to continue the Andrew Ng's Machine Learning course on Coursera that I got part way through a couple of years ago.
		○ Also recommended was the book Introduction To Statistical Learning by Trevor Hastie et al, who also authored Elements Of Statistical Learning.  The Introduction book is a primer for Elements, which I'll read next.  


Effort 02
Objective: Find the drug research, and make some skills progress. 
	1. Project.
		○ I hit the jackpot by finding a publicly available Stanford University research paper that has a GitHub repository containing the paper, preprocessed data, and Python code used.  I'm not sure if it's exactly the same researchers I heard about on the podcast, but I'll take it. 
		○ I think the plan will be to try to reproduce their results as a first step.
		○ I downloaded and extracted the various files from GitHub. 
			§ https://github.com/marinkaz/decagon 
		○ They also have a web site with a high level description of their research and methodology.
			§ http://snap.stanford.edu/decagon/
	2. Education
		○ Completed the first couple of modules of ML
		○ Made it to the first R lab in Ch 2 of ITSL. 
			§ The authors make their digital book available on their web site.
				□ www.StatLearning.com 
			§ They also created an accompanying video series, similar to the Coursera course, that's linked from their web site. 
				□ https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/
		

Effort 03
	1. Project 
		○ Began reading the research paper. 
			§ Looked for exact methodology and a list of software and hardware used.  
			§ I didn't find the low hanging fruit I had hoped for.  The paper used a considerable amount specific lingo that will take some serious time to digest, and is often cryptic referring readers to other research papers for details.  It's definitely not a textbook intended for the uninitiated.
			§ Being an impatient coder who generally prefers looking at code rather than documentation, I'm wondering if having the code reviewed by people familiar with Python might be the path of least resistance. 
			§ I've learned that they used a Graphical Neural Network running on Tensor Flow to associate drugs having similar properties, similar to what LinkedIn and Facebook to develop our social network and make friend suggestions. 
		○ Got setup to use GitHub for PVD-Data-Science repositories. 
			§ Setup Bash and SSH key.
			§ I don't appreciate the joy of command line interfaces like Bash, and I'll still need a code editor, so I'm going to climb up the learning curve the new IDE from Microsoft maned Visual Studio Code.  It has a built-in Git manager and lots of bells and whistles like intelliSense for R and Python etc.  
	2. Education - no progress


Effort 04
	1. Project
		○ It was recommended that I find a Docker image with a recent version of Tensor Flow and Python etc.  I went to the Docker site, but there were several images to choose from.  Need to get further clarification. 
		○ Another suggestion is the Google CoLab site.  If that works out, I won't need to load anything on my laptop.  Now I need to get a better handle on the code.
		○ While uploading the project to the group's GitHub, I found the guidance I was looking for in the researcher's GitHub Readme file.  Go figure.  
			§ I take it from their lack of specificity on the Tensor Flow container that it's not important beyond being a recent version if I want to try that route.
			§ They also have a text file containing code that can be run to load every Python library necessary for the project to run.   
Education - no progress+