# SurvCNN

Redefining the utility of multi-omics data in cancer survival prediction.

Introduction
------------

The utility of multi-omics in personalized therapy and cancer survival analysis has been debated and demonstrated extensively in the recent past. Most of the current methods still suffer from the constraints of data such as high-dimensionality, unexplained interdependence and subpar integration methods. Here we propose SurvCNN, an alternative approach to process multi-omics data in a way that it can be used with robust computer vision architectures to predict cancer prognosis for Lung Adenocarcinoma. Numerical multi-omics data was transformed into their image representations and fed into a Convolutional Neural network with a proportional hazard layer to predict survival probabilities. The framework also dichotomized patients into risk subgroups based on their survival probabilities over time. SurvCNN was evaluated on multiple performance metrics and was able to outperform existing methods with a high degree of confidence. Moreover, comprehensive insights into the relative performance of various combinations of omics datasets were probed. Critical biological processes, pathways and cell types, identified from downstream processing of differentially expressed genes suggested that the framework was able to elucidate elements that are detrimental to a patient's survival. Such integrative models with high predictive power would have a significant impact and utility in precision oncology.

Data/Notebook for a classification model with Drug features containing only **XAE** and target features having only **Descriptors** as features.

Usage
------------

* **Modular approach** — We propose to harness the potential of state-of-the-art ML (Machine Learning) algorithms like Bi-directional Long Short-Term Memory (bi-LSTM) and Graph Convolutional neural networks (gCNNs)

Questions? Need Help? Found a bug?
--------------------
Found a bug with upstream Slate? Go ahead and [submit an issue](https://github.com/iamysk/dNNDR/issues). And, of course, feel free to submit pull requests with bug fixes or changes to the `dev` branch.

Contributors
--------------------
- [Shashank Yadav](https://github.com/xinformatics)
- [Yogesh Kalakoti](https://github.com/iamysk)
