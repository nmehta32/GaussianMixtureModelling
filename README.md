# GaussianMixtureModelling
Code for implementing gaussian mixture modelling given a set of data.

Although the question is for dealing for only 2 classes of data of 4 each. This can classify any type of 1-D data with how ever many classes. The only problem being its speed,
although o(n^2) is not the worst, when classifying modern types of data with more values it could be better.
One way to improve it is simply using np.covar()
it computes in O(nLogN) {worst case, much faster in practice}
