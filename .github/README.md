# Automating Systematic Literature Review using BERTopic

## Table Contents
* [Project Description](#PD)
* [Future Direction](FP)
* [Collaborators](CO)
* [Reference](RF)
<a id = "PD"></a>
## Project Description
Fairness in AI is getting a significant presence in AI ethics. Fairness is positioned third in a prevailing ethical issue ranking [1], and the EU allocated it as one of the seven criteria for trustworthiness in their guideline. Meanwhile, the word "Fairness" is broadly used in numerous cross-discipline fields, not only in the AI field. Consequently, it makes searching the target literature complex to investigate fairness even with concurrence words such as AI, machine learning, and deep learning. We employed topic modelling, BERTopic which assembles embedding, reducing dimentionality, clustering and class-based TF-IDF and automated a part of the literature review process [2].

## Getting Started
To start understanding how the code works, you can search your topic in Web of Science and download the list of results as CSV file and use [this](https://github.com/Kuniko925/Literature-review-with-BERTopic/blob/main/Notebooks/literature-review-with-fair-and-equality.ipynb) Notebook.

<a id = "FP"></a>
## Future Direction
BERTopic functioned along with Llama 2 and can be applied in the topic representation process [3].  Using LLM for the summarisation and sentimental analysis between embedded documents and reductional dimensions, we would like to create hierarchical sentence vectorization to analyze latent topics more sophisticatedly by highlighting the context and nuance.

<a id = "CO"></a>
## Collaborators
Kuniko Paxton<br>
Dr Koorosh Aslansefat

<a id = "RF"></a>
## Reference
[1] Čartolovni, Anto, Ana Tomičić, and Elvira Lazić Mosler. "Ethical, legal, and social considerations of AI-based medical decision-support tools: A scoping review." International Journal of Medical Informatics 161 (2022): 104738.<br>
[2] Grootendorst, Maarten. "BERTopic: Neural topic modeling with a class-based TF-IDF procedure." arXiv preprint arXiv:2203.05794 (2022).
[3] Grootendorst, Maarten. “Topic Modeling with Llama 2.” Medium, 12 Oct. 2023, towardsdatascience.com/topic-modeling-with-llama-2-85177d01e174. Accessed 10 Jan. 2024.

## Related Projects
[LitStudy: a Python package that enables analysis of scientific literature from the comfort of a Jupyter notebook.](https://github.com/NLeSC/litstudy)
