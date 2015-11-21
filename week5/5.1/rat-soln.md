answers
--------
1. Say Watson's Jeopardy! system had a question-answering accuracy of 60% to begin with.
	1. If we ask it questions from the medical domain only, what is the change in Watson's question-answering accuracy?
		- 19-20% - At its baseline, Watson's Jeopardy! system is an open domain question-answering system. It can answer general or open domain questions with high accuracy, but when posed domain-specific questions, its accuracy drops considerably because it needs more in-depth, domain-specific knowledge.
	2. When we replace the content that Watson uses for answering medical questions with medical content, what is the change in Watson's question-answering accuracy?
		- By just replacing the open domain content corpus to medical domain content corpus, Watson's accuracy in answering questions increases to 26% from 19%, a 7% increase. Content adaptation is the first stage of domain adaptation, and it involves creating a domain-specific corpus of content by using structured and unstructured sources of data.
2. Among the following resources, which one would you consider the most important to adapt Watson to the medical domain?
	d) PubMed - Adapting Watson to the medical domain involves having Watson focus on medical domain-specific resources such as PubMed and not open-domain and general-knowledge-related resources such as Wikipedia or Encyclopedia Britannica.
3. Which is a structured source of information for the medical domain?
	d) UMLS - Unified Medical Language System (UMLS) is an ontology that has evolved over several years of work by different public organizations and government bodies. This organized ontology contains millions of concepts and variants of those concepts. Books, clinical guidelines, journals, magazines, and web resources are examples of unstructured sources in the medical domain.
4. Which of the following is a challenge to Corpus Expansion?
	a) Noisy, bad-quality text - Corpus Expansion is an important part of content adaptation, as it entails extending the corpus to describe most of the concepts of interest in the domain-specific knowledge base available to Watson. The main challenges to corpus expansion are dealing with a large quantity of data but also filtering out noisy, bad-quality data and text.
