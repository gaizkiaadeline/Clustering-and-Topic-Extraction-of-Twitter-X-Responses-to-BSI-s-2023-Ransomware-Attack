# Clustering and Topic Extraction of Twitter (X) Responses to BSI's 2023 Ransomware Attack
This project explores user responses to the 2023 ransomware attack on BSI, which disrupted the bank's national operations. Twitter (X) was widely used for public discussion, and this project aims to model and analyze these discussions using both clustering and topic extraction methods.

**The project includes:**
- Clustering Analysis: Different clustering models are applied to group user tweets. Various values of clusters (k) are tested, and the silhouette score is used to compare and justify the chosen number of clusters.
- Persona Analysis: Persona analysis is conducted on the resulting clusters to gain insights into the characteristics and behaviors of users in each group.
- Topic Extraction: An alternative approach using topic extraction is implemented to uncover the main topics discussed by users. The method is compared to clustering, and persona analysis is repeated based on the extracted topics.
- Comparison of Clustering vs. Topic Extraction: A detailed comparison is conducted between the results of clustering and topic extraction, highlighting key similarities, differences, and interesting patterns in the data.

**Key Features:**
- Clustering: Multiple values of k are tested with silhouette score analysis.
- Persona Analysis: Insights into user personas based on both clustering and topic extraction.
- Topic Extraction: Models are applied to identify key topics discussed by users.
- Comparison: Detailed analysis comparing clustering and topic extraction results.

**Technologies Used:**
- Python: For data processing and model development.
- Scikit-learn: For clustering and silhouette score analysis.
- NLTK: For text preprocessing.
- Latent Dirichlet Allocation (LDA): For topic modeling.
- Matplotlib / Seaborn: For visualizing results.
