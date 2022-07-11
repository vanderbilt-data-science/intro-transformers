# intro-transformers

This repository provides a general overview of transformers: 
* What are transformers?
* Where can I learn more about them?

These resources are best used by those who may already have some knowledge/experience in data science, but would like to learn more about transformers in particular. 

## What Are Transformers? (Overview)
Transformer-based large language models have been widely applied in the analysis of text (and other modalities) since first being introduced in 2019 and are the state of the art across most natural language processing tasks. Models are initially trained on a large, diverse corpus through self-supervised learning, building a language model and semantic model learned from the corpus. The pretrained models can then be used for a variety of tasks--question answering, entity resolution, summarization, categorization, entailment assessment, sentiment analysis, tone analysis, style identification, and others. These foundational models can be further trained through domain adaptation or task fine tuning for better performance in a particular subject area, or on a specific task. In domain adaptation, the model is trained using self-supervised learning on domain-specific text, and thereby learns terms, concepts, and patterns associated with a particular field. As in the original training for the model, this does not require labeled data for learning, only text relevant to the domain. In task fine tuning, labeled data is used to improve performance on a particular task. Often, domain adaptation is combined with task fine tuning to leverage all available data. After domain adaptation, far less data is needed for task fine tuning. Transformer-based large language models adapted to domains offer new avenues for research and discovery that were previously unapproachable.

## Where Can I Learn More About Transformers? (Resources)
* Those with a vanderbilt.edu email address can log into O'Reilly Media and access the **book** *Natural Language Processing with Transformers* by Lewis Tunstall, Leandro von Werra and Thomas Wolf : https://learning.oreilly.com/library/view/natural-language-processing/9781098136789/. Vanderbilt licenses all content from O’Reilly.
* HuggingFace's **online course** offers an excellent introduction to Natural Language Processing using transformers in the HuggingFace ecosystem: https://huggingface.co/course
* AI Summer: https://github.com/vanderbilt-data-science/ai_summer
* For graduate students or undergrad seniors at Vanderbilt, consider the course DS 5899: https://docs.google.com/document/d/1Oh1qtLDE35R3HqqEHL_KaDgOkCiwAVaJmAKn-dEckkE/edit
