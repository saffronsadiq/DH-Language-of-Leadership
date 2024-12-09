# DH-Language-of-Leadership
MPhil Digital Humanities project titled 'The Language of Leadership: A Digital Humanities Approach to Analysing Emotional Resonance and Linguistic Complexity in Political Speech'

This repository contains the code, data, and analytical documentation for the project The Language of Leadership: Emotional Resonance and Rhetoric in Political Speech. The study explores how computational methods can deepen our understanding of political rhetoric, with a particular focus on emotional resonance and thematic patterns in speeches by American political leaders.

Project Overview

This research sits at the intersection of Digital Humanities, Political Science, and Computer Science. By employing NLP tools, such as RoBERTa and Co-occurrence Network Analysis, the project investigates the linguistic patterns, emotional intensity, and thematic networks within (2020-2024) Republican and Democratic rhetoric. The analysis seeks to uncover how political leaders invoke shared values, appeal to voter psychology, and construct rhetorical strategies that mobilise collective identities.

Research Questions
	1.	How do emotional and thematic patterns in political speeches differ across party lines?
	2.	What linguistic strategies resonate most with audiences, and how do these vary in framing and sentiment?
	3.	Can computational tools capture the nuance and complexity of emotional resonance in political language?

Contents of This Repository

Datasets

	•	Corpus of Donald Trump Speeches: A collection of speeches by Donald Trump, preprocessed for analysis.
 
	•	Corpus of Joe Biden Speeches: A collection of speeches by Joe Biden, preprocessed for analysis.

Key Files

	•	biden_co-occurence_keywords.csv: Co-occurrence keyword data for Joe Biden’s speeches.
 
	•	trump_co-occurence_keywords.csv: Co-occurrence keyword data for Donald Trump’s speeches.

Preprocessing Notebooks

	1. 	Cleaned Data
	
	•	A notebook outlining steps taken to clean data. 

	2.	Co-occurence Analysis.ipynb:

 	•	A custom dictionary of keywords corresponding to seven emotional categories to train RoBERTa.

Analytical Notebooks

	1.	Co-occurence Analysis.ipynb:
 
	•	Maps relationships between emotionally charged terms in Trump and Biden’s speeches.
 
	•	Visualises thematic clusters using co-occurrence network analysis.
 
	2.	Emotional Distribution Analysis.ipynb:
 
	•	Classifies emotional tones in political speeches.
 
	•	Compares emotional patterns across leaders.
 
	3.	Emotional Ngram Frequency.ipynb:
 
	•	Analyses recurring emotional n-grams to identify trends in emotional framing.
 
	4.	Language Complexity Analysis.ipynb:
 
	•	Measures linguistic complexity in speeches to examine their accessibility and resonance.
 
	5.	RobertaForTrump.ipynb:
 
	•	Custom fine-tuning and application of the RoBERTa model for Trump’s speeches.
 
	6.	RobertaForBiden.ipynb:
 
	•	Custom fine-tuning and application of the RoBERTa model for Biden’s speeches.
 
	7.	Pre-trained Roberta.ipynb:
 
	•	Demonstrates the use of pre-trained RoBERTa for initial speech classification and feature extraction.

 Visualisation Notebook

	1. 	Co-Occurence Network
	
	•	A visualisation showing the co-occurence networks of Trump and Biden speeches.

 ## Pretrained Models

The models used for analysis are  hosted on Hugging Face:

- **Biden Model**: (https://huggingface.co/SaffronSadiq/biden-speech-analyser)
- **Trump Model**: (https://huggingface.co/SaffronSadiq/trump-speech-analyser)

These models can be used for various NLP tasks, including co-occurrence analysis, emotional distribution analysis, and more.

Key Features and Findings:

	•	Emotional Framing:
 
	•	Insights into how Trump and Biden use emotional rhetoric to engage audiences.
 
	•	Differences in sentiment distribution and intensity.
 
	•	Thematic Co-Occurrence Networks:
 
	•	Visualisation of connections between keywords and overarching themes in political speeches.
 
	•	Linguistic Complexity:
 
	•	Analysis of how speech patterns align with target audiences’ comprehension levels.
 
	•	Methodological Reflections:
 
	•	Evaluation of the capabilities and constraints of computational tools in capturing political nuance.

Tools and Technologies

	•	NLP Libraries: Hugging Face Transformers, spaCy, NLTK
 
	•	Data Analysis and Visualisation: Pandas, Matplotlib


Data: Chalkiadakis, Ioannis; Anglès d'Auriac, Louise; Peters, Gareth W.; Frau-Meigs, Divina (2024). A text dataset of campaign speeches of the main tickets in the 2020 US presidential election. figshare. Dataset. https://doi.org/10.6084/m9.figshare.26862064.v1

Significance: This project demonstrates the value of combining computational methods with traditional humanities inquiry, contributing to the growing field of Digital Humanities. It also highlights how interdisciplinary approaches can enhance our understanding of political rhetoric and its societal impact.
