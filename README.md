# Thesis-dataset

This study investigates the capacity of Large Language Models (LLMs), specifically ChatGPT 3.5 and 4, to evaluate citations in scholarly papers. Given the
importance of accurate citations in academic writing, our goal was to determine
how well these models can assist in verifying citations.
We conducted a series of experiments using a dataset we created, which includes
three main citation categories: Direct Quotation, Paraphrasing, and Summarising,
along with subcategories such as minimal and long source text.
In our initial experiment, ChatGPT 3.5 demonstrated perfect accuracy, while ChatGPT 4 showed a tendency towards false positives. Further experiments with an
extended dataset revealed that ChatGPT 4 excels in correctly identifying valid citations, particularly with longer and more complex texts, but is also more prone
to incorrect invalidations. ChatGPT 3.5, on the other hand, provided a more balanced performance across different text lengths.
Our reliability experiments indicated that ChatGPT 4 is more consistent in its responses compared to ChatGPT 3.5, although it also had a higher rate of consistent
wrong predictions.
This study highlights the potential of LLMs to assist scholars in citation verification, suggesting a hybrid approach where ChatGPT 4 is used for initial scans
and ChatGPT 3.5 for final verification.


The primary objective of our thesis is to evaluate citation types using Large Language
Models (LLMs). However, upon conducting research, we found no existing datasets
suitable for our experimentation. We decided to create our own dataset, which we consider a significant contribution of this research.
This dataset was required to include citation categories, both true citations and false
citations, and the corresponding source texts. We began by focusing on the categories
of direct quotation, paraphrasing, and summarizing. For each category, we manually
created 20 samples. This involved a detailed process of reviewing student theses to
extract citations that fit our defined categories.
To obtain these samples, we reviewed past student theses from Linnaeus University.
We randomly selected portions of these theses to use as source texts, ensuring a diverse
representation of citation practices. Each selected text was paired with a citation to
create both valid and invalid examples.
We further expanded this dataset by incorporating additional features and subcategories. The complete dataset is publicly available on GitHub and can be
accessed via this link.


Done by Ahmad Zeeb and Philip Olsson.
