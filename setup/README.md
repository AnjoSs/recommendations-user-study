# Experimental Setup

## Participants

22 participants were investigated. They were all computer science students in their bachelors (4), masters (15), or Ph.D. (3).
First, two groups of seven participants each were randomly selected. One group received no recommendations, while the other received filter-based recommendations. At a later point of time, a third group of eight was given score-based recommendations.
This results in three groups of participants

They have different levels of experience with fragment-based Case Mmanagement (fCM). In a self assessment, the participants evaluated their experience on a scale from one to five:
Insert figure

## Experiments

All participants received an example process model and a textual description of their objective, and a custom version of an fCM-execution engine. The text document and execution engine provided to each group can be found in the respective folders `recommendations_without`, `recommendations_filter_based`, and `recommendations_score_based`.

The execution engines are privided as jar files. To execute them, please make sure to run the latest java version on your device. Also the engine is based on [CPN Tools] (http://cpntools.org) and therefore only supported on Windows. To start the execution engine, doenload it, open the according directory with the comand prompt and type in `java -jar <name_of_the_file>`.

When the engine is started, you will be asked whether or not you want to receive recommendations. To test the execution engine without recommendations, please select `NO`. If you want to receive recommendations in the respective engine, please select `YES`.