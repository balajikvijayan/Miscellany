answers
--------
1. What is the role of spatial and temporal reasoning in question answering?
	a) Provide evidence from the ontology supporting candidate answers - Spatial and temporal reasoning are used in the evidence scoring process to improve the ranking of candidate answers by finding compatibility with the question.
2. Spatial and temporal reasoning relies on which of the following?
	d) Entity disambiguation and matching - After entity disambiguation and matching is complete for the candidate answer and the terms in the question, Watson performs geographic and temporal reasoning using the information provided by the linked concepts in the ontology.
3. Evidence diffusion allows you to use evidence supporting entities that are explicitly mentioned in the corpus to derive evidence about other entities, even though such evidence is not explicitly expressed in text. Why is this possible?
	b) The relationships between candidate answers provided by the ontology allow Watson to propagate features across different answers - Evidence diffusion works because candidate answers are not independent—there are relationships between them. Watson applies rules that are driven by the ontology to improve the final ranking, transferring features from one answer to another.
4. What type of information triggers the activation of answer merging?
	d) Wikipedia redirects - Answer merging collapses the information from different candidate answers into a single answer when they refer to the same entity. Wikipedia redirects provide a vocabulary of synonyms that can be used to accomplish this.
