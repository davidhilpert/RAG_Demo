# RAG_Demo

This project showcases the potential of combining Large Language Models (LLMs) with Retrieval-Augmented Generation (RAG) to navigate and query extensive, complex text corpora. A chatbot built on these technologies enables intuitive interaction with dense and often inaccessible document sets, such as legal codes and rulebooks. An RAG-backed LLM answers a given query based on the most relevant texts from a data base. Users can extract information from large text databases simply by chatting with an LLM-model such as Meta's Llama.

As a practical use case, I applied a RAG-backed LLM to a dataset of 1,000 judgments from the Court of Justice of the European Union (CJEU). These judgments are an ideal test case: decades of European legal integration have created a vast, intricate body of law that challenges even legal experts. In order to back up its reasoning and build consistency over time, the CJEU often makes references to previous rulings (e.g., Derlén & Lindholm 2014; Larsson et al. 2017). The court's valuation of precedent shows parallels to Retrieval-Augmented Generation built into modern LLMs. I study whether RAG models, which recover relevant references by using learned sentence embeddings in a high-dimensional latent space and then ranking embedding vector in terms of their cosine similarity, identify the same rulings that the court in fact references in its judgments. This exercise provides unique insights into the usefulness of RAG in text corpora from highly specialized fields such as law.

References: 

Derlén, M., & Lindholm, J. (2014). Goodbye van g end en l oos, hello b osman? Using network analysis to measure the importance of individual CJEU judgments. European Law Journal, 20(5), 667-687.

Larsson, O., Naurin, D., Derlén, M., & Lindholm, J. (2017). Speaking law to power: the strategic use of precedent of the court of justice of the European Union. Comparative Political Studies, 50(7), 879-907.
