# Semi-supervised-Anomaly-Detection-Framework
This repo is based on the python implementation of the anomaly detection method described in https://web.archive.org/web/20220801212701id_/https://aisel.aisnet.org/cgi/viewcontent.cgi?article=1099&context=ecis2020_rp
See section 3 for the detaild description.

When we have a large unlabelled dataset to detect anomalies from, it is difficult to experiment with unsupervised algorithms because of the computational constraints.
We can produce a representative small subset of the entire data and then we can detect anomalies in the small data.Next, we can create labels on this smaller subset of the data to run a classifier.
Once we have the trained classifier we can predict the outliers in the rest of the data (practically the bigger subset of the data.)
Note that, the domain experts can also cross-check the anomalies obtained in the smaller part of the data, so that human expertise can be incorporated in the entire exercise.
