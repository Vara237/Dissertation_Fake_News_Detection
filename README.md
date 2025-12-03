# Dissertation_Fake_News_Detection


     The wide spread of fake news via online sources has become a major issue, as it affects the trust of people and impacts the society in making a choice. Conventional manual ways of fact-checking are progressively not enough and automated detection ways should be developed. The given dissertation explores the efficacy of the machine learning (ML) and Deep Learning (DL) methods to detect fake news using the strict comparative paradigm. The study compares Logistic Regression, Random Forest, Extreme Gradient Boosting (XGBoost), and Light Gradient Boosting Machine (LightGBM) with Long Short-Term Memory (LSTM) networks and Bidirectional Encoder Representations (BERT) with the use of the FakeNewsNet benchmark dataset comprising of verified political and entertainment news by PolitiFact and GossipCop. Experimental pipeline was applied in a normal way, which included text pre-processing, feature representation, adaptive class imbalance control and a multi-metric performance. The findings indicate that ensemble-based ML models, more specifically LightGBM and XGBoost, are always more accurate, recalling more, and with higher Area Under the Receiver Operating Characteristic Curve as compared to Deep Learning models. Although BERT can be effective with contextual understanding, its results are poor unless it is fine-tuned to the task. The results are that optimized ML models provide strong, interpretable, and computationally efficient to detect fake news, and its direct application in the real-world setting.


Model	Accuracy	Precision	Recall	F1-Score	AUC-ROC
0	Logistic Regression	0.820474	0.904878	0.850674	0.876939	0.866056
1	Random Forest	0.826940	0.862777	0.915449	0.888333	0.852199
2	XGBoost	0.829095	0.848501	0.940671	0.892211	0.837351
3	LightGBM	0.835776	0.862344	0.930066	0.894926	0.851899
4	BERT	0.606000	0.832117	0.601583	0.698315	0.642633
5	LSTM	0.248060	0.000000	0.000000	0.000000	0.500000



References 

	Bovet, A., & Makse, H. A. (2019).
Influence of fake news in Twitter during the 2016 U.S. presidential election. Nature Communications, 10(1), 1–14.
https://doi.org/10.1038/s41467-018-07761-2
	Castillo, C., Mendoza, M., & Poblete, B. (2011).
Information credibility on Twitter. Proceedings of the 20th International World Wide Web Conference, 675–684.
https://doi.org/10.1145/1963405.1963500
	Chen, T., & Guestrin, C. (2016).
XGBoost: A scalable tree boosting system. Proceedings of the 22nd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 785–794.
https://doi.org/10.1145/2939672.2939785

