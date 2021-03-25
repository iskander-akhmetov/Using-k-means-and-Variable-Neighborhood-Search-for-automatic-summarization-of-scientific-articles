# Using-k-means-and-Variable-Neighborhood-Search-for-automatic-summarization-of-scientific-articles
Using K-means and Variable Neighborhood Search for Automatic Summarization of Scientific Articles

This work presents a method for summarizing scientific articles from the arXive dataset using Variable Neighborhood Search (VNS) heuristics to automatically find the best summaries in terms of ROUGE-1  score  we  could  assemble  from  scientific  article  text  sentences.  Then vectorizing the sentences using BERT pre-trained language model and augmenting the vectors with topic embeddings obtained by applying the K-means  algorithm.  Finally,  training  the  Random  Forest  classification model to find sentences suitable for the summary and compile a summary  from  the  selected  sentences.  The  described  algorithm  produced summaries with high ROUGE-1 scores (0.45 on average), so we are heading for further developments on a larger dataset.

The method is fully described in the article https://link.springer.com/chapter/10.1007/978-3-030-69625-2_13.

Original data (arXive articles collection by A Cohan, 2018) used in this experiment was obtained from here https://github.com/armancohan/long-summarization.
The data sample we worked with can be downloaded from here https://yadi.sk/d/rBfaMTYeGt28CQ.

It would be nice if you cite our article as:

@INPROCEEDINGS {iskanderakhmetovrustammussabayevnenadmladenovic2021,
    author       = "Iskander Akhmetov, Rustam Mussabayev, Nenad Mladenovic",
    title        = "Using K-Means and Variable Neighborhood Search for Automatic Summarization of Scientific Articles",
    booktitle    = "Variable Neighborhood Search",
    year         = "2021",
    volume       = "12559",
    series       = "Lecture Notes in Computer Science",
    pages        = "166-175",
    month        = "mar",
    organization = "International Conference on Variable Neighborhood Search",
    publisher    = "Springer, Cham",
    doi          = "https://doi.org/10.1007/978-3-030-69625-2_13"
}
