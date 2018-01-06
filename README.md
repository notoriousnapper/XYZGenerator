# XYZGenerator

Assumptions: 

1. Co-occurence - frequency between X and Z, and Y and Z
2. Surprisal Factor - How uncommon an adjective Z is
3. Ambiguity - How many "senses" exist for a given word

Data Sets: 
WordNet (Collection of similar words by meaning, "synnets" and "
	approximate thesaurus that mixes in hypernyms, 
Google NGram Data
	Collection of co-occurence between n-grams
	* 
	

Data Structures:
Hashmap for X, to select the best XYZ combinations
Tree Structure or Linked list to get best top 30 XYZ jokes given X
Given N words, O(N*A) is runtime after all the processing

Crazy Ideas:
   - Use a Neural Net
   - Use a pipeline, that, *** Instead of generating all XYZ combinations for a given X,
	and its accompanying data storage, will selectively exclude
	data that has low Surprisal Factor, or Co-occurence, etc.



Links: 
Getting correct words with custom dictionaries: http://pythonhosted.org/pyenchant/tutorial.html#pyenchant-tutorial
Understanding N-Gram Data/ Research Paper: http://support.sas.com/resources/papers/proceedings16/12487-2016.pdf

