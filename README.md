# prinia-project

The prinia-project is a pipeline to analyse multispecies acoustic datasets in Python and MATLAB

It allows for easy visualisation and classification based tools to look for 
1. _Acoustic Signal Partitioning in Note Space_
2. _Complexity Analysis of Birdsong_
3. _Repetition Rate Analysis_

__Methods__
1. We perform PCA to ordinate song notes as points in N-dimensional space
2. Build Linear Discriminant Classifiers using scikitlearn (in Python) and MATLAB
3. Perform Higherarchical Clustering to classify song notes
4. Extract distributions of repetition rate for species with a single note type

The pipeline can be extended to look for clustering in multi-species community data

Check out [our paper in Behavioural Ecology](https://academic.oup.com/beheco/advance-article/doi/10.1093/beheco/arz216/5702188) to find out more! 
(Data in this github repository also available [on DRYAD](https://datadryad.org/stash/dataset/doi:10.5061/dryad.7sqv9s4p9))
