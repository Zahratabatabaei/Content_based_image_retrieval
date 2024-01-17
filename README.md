Hi world!

This code corresponds to a search engine that searches for similar cases in a breast cancer data set. 
The used data set in this code is BreaKHis at 100X magnification.
In this code, we load a feature extractor to extract the features of the database and index them to save them as in our previous cases.
Then, it receives a query. It applies the same feature extractor to the query to extract its feature vectors.
In the following step, a similarity measure is applied to measure the distance between the query features and the indexed features.
Finally, it is time to retrieve similar patches and evaluate the performance.
