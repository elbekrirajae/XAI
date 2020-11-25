# XAI


AI is still facing many challenges like (1) the complexity of current deep learning models, which restraint their deployment in some environments and devices, (2) the lack of robustness to adversarial attacks, which pose a severe security risk in application such as autonomous driving (3) **the lack of transparency and explainability**

So in the first part of our project, we worked on the meta-explanation, an approach that differs from other families of explainability methods because it is deals large
large amount of heatmaps to explain the behavior of the model unlike the other methods which provide single, individual explanation.
thus, we applied the spectral clustering on all the heatmaps that we have, then when we visualized the clusters with the t-SNE, we noticed that the algorithm does not give exactly good results and that
the clusters are not instinctive. However, we used kmeans instead and looked for the best possible number of clusters which turned out to be 7, then we visualized the clusters in different ways.
Yet, the saliency maps of ultrasound images do not allow to see and distinguish the difference between
them, that is why we have to compare between the clusters using the prediction error and the head circumferance measurement.

For the second part of the project, it concerned the evaluation of the explainability methods, because
it is very necessary to be able to distinguish the best method among a panoply of methods and which
of course adapts to the problem treated. Moreover, I based myself on the article[] which proposes a methodology to qualify the methods by adding randomness at the label level and at the parameter level to show the sensitivity and variance of the method to these two elements. We used a simple CNN
model and the methods in the iNNvestigate toolbox.



