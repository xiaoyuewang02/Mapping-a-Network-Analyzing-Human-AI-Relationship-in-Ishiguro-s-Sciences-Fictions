# Mapping-a-Network-Analyzing-Human-AI-Relationship-in-Ishiguro-s-Sciences-Fictions-through-a-Posthumanist-Lens

The research question is to explore what kind of relationships between artificial intelligence and humans was presented in Ishiguro’s "Never Let Me Go" (2005) and "Klara and the Sun" (2021) through network analysis.

1. Data
The data source is from Klara And The Sun.pdf and Never Let Me Go.pdf. They were extracted and converted to TXT format.
Preprocessed Data：the labelled text are named Never_Label_Name.txt and Klara_Label_Name.txt. (Character aliases have been unified)

2. Workflow
The workflows are documented in Klara_Workflow.ipynb and Never_Workflow.ipynb. (Python)
2.1 Build the name dictionary manually (the references can be seen in Klara and the Sun Characters Listed With Descriptions.pdf and Never Let Me Go Characters Listed With Descriptions.pdf).
2.2 Plot the histograms of the names' frequency distribution.
2.3 Check the turning point of frequency by plotting a Log-Log Plot of character frequency.
2.4 Calculate the character co-occurrence matrix using a Python sliding window size(=50).
2.5 Create the character co-occurrence network; manual categorization of character types was conducted.
2.6 Calculate character centrality measures.
2.7 Extract stopwords from these novels, and conduct manual checking to retain meaningful words (the edited files are named Klara_Label_stopwords.txt and Never_Label_stopwords.txt).
2.8 Draw the main characters' context cloud map by extracting and cleaning the contexts in which their names appeared.
