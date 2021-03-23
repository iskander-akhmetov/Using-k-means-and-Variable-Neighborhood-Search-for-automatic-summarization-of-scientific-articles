# Using-k-means-and-Variable-Neighborhood-Search-for-automatic-summarization-of-scientific-articles
Using K-means and Variable Neighborhood Search for Automatic Summarization of Scientific Articles

This work presents a method for summarizing scientific arti-cles from the arXive dataset using Variable Neighborhood Search (VNS)heuristics to automatically find the best summaries in terms of ROUGE-1  score  we  could  assemble  from  scientific  article  text  sentences.  Thenvectorizing the sentences using BERT pre-trained language model andaugmenting the vectors with topic embeddings obtained by applying theK-means  algorithm.  Finally,  training  the  Random  Forest  classificationmodel to find sentences suitable for the summary and compile a sum-mary  from  the  selected  sentences.  The  described  algorithm  producedsummaries with high ROUGE-1 scores (0.45 on average), so we are head-ing for further developments on a larger dataset.

The method is fully described in the article https://link.springer.com/chapter/10.1007/978-3-030-69625-2_13.

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
