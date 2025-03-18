# AI Resume Ranker 
(In progress)

How does it work?

> User uploads a Resume (pdf/docx format) and Job Description (text)
> Preprocess both the texts (cleaning, tokenization etc)
> Convert both texts into embeddings (first using basic TF-IDF then using SBERT maybe even fine tuning it)
> Compute Similarity Score using Cosine Similarity
> Show result -
* High Score (80-100%) -> Resume is a great match!
* Medium Score (50-79%) -> Resume needs improvement
* Low Score (<50%) -> Resume is not a good match.

