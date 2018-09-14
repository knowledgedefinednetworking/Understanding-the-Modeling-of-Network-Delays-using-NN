# Understanding-the-Modeling-of-Network-Delays-using-NN
Recent trends in networking are proposing the use of Machine Learning (ML) techniques for the control and operation of the network. In this context, ML can be used as a computer network modeling technique to build models that estimate the network performance. Indeed, network modeling is a central technique to many networking functions, for instance in the field of optimization, in which the model is used to search a configuration that satisfies the target policy. In this paper, we aim to provide an answer to the following question: Can neural networks accurately model the delay of a computer network as a function of the input traffic? For this, we assume the network as a black-box that has as input a traffic matrix and as output delays. Then we train different neural networks models and evaluate its accuracy under different fundamental network characteristics: topology, size, traffic intensity and routing. With this, we aim to have a better understanding of computer network modeling with neural nets and ultimately provide practical guidelines on how such models need to be trained.


###### [Arxiv] (https://arxiv.org/pdf/1807.08652):
###### [ACM Proceedings of the 2018 Workshop on Big Data Analytics and Machine Learning for Data Communication Networks in ACM-SIGCOMM] (https://dl.acm.org/citation.cfm?id=3229613):
Albert Mestres,	Eduard Alarcón, Yusheng Ji, Albert Cabellos-Aparicio	

The research community has considered in the past the application of Artificial Intelligence (AI) techniques to control and operate networks. A notable example is the Knowledge Plane proposed by D.Clark et al. However, such techniques have not been extensively prototyped or deployed in the field yet. In this paper, we explore the reasons for the lack of adoption and posit that the rise of two recent paradigms: Software-Defined Networking (SDN) and Network Analytics (NA), will facilitate the adoption of AI techniques in the context of network operation and control. We describe a new paradigm that accommodates and exploits SDN, NA and AI, and provide use cases that illustrate its applicability and benefits. We also present simple experimental results that support its feasibility. We refer to this new paradigm as Knowledge-Defined Networking (KDN).



# General networking modeling 



## Different datasets (different topologies, sizes and traffic characteristics)

Datasets available here [here](http://knowledgedefinednetworking.org/).


---

author: amestres@ac.upc.edu

* [MATLAB](https://www.mathworks.com/products/matlab.html)
* [TENSORFLOW](https://www.tensorflow.org/)
* [KDN](https://arxiv.org/abs/1606.06222)
* [OMNeT++](https://omnetpp.org/)
