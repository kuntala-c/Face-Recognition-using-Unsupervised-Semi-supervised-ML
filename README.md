# Face-Recognition-using-Unsupervised-Semi-supervised-ML
Face Recognition Algorithm using Unsupervised and Semi-supervised Techniques

The Olivetti faces dataset:
--------------------------

This dataset contains a set of face images taken between April 1992 and April 1994 at AT&T Laboratories Cambridge. 
The `sklearn.datasets.fetch_olivetti_faces` function is the data fetching / caching function that downloads the data
archive from AT&T.

The `target` for this database is an integer from 0 to 39 indicating the identity of the person pictured; however, with only 10 examples per class, this
relatively small dataset is more interesting from an unsupervised or semi-supervised perspective.

Below tasks are covered in the project:
--------------------------
* Apply various unsupervised techniques and compare what works best for the data
* Apply pca, kmeans as a preprocessing
* Determine the optimal number of clusters and plot the cluster of faces
* Take the test data and create labels for the test data using the semi-supervised method
* Have a validation dataset to verify the created labels are close to the validation test labels before propagating them into the test set
* `Final Result: Accuracy increased from 73% to 80% by propagating labels only to the instances that are really close to the centroid`
