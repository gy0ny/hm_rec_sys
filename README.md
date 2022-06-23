###  (Kaggle) H&M Personalized Fashion Recommendations 

- 고급통계학특론 개인 프로젝트

- Content-based 추천시스템

1. **Label이 없는 이미지데이터의 Feature map 추출**
    
    ⇒ **Deep clustering** 모델 구현하여 Fine-tuning (Pytorch)
    
2. Pseudo-label 생성의 불균형으로 인해 하나의 cluster로 수렴하는 현상
    
    ⇒ Uniform 분포에서 sampling, 더 깊은 pre-trained CNN 사용 후 해결
    
3. 추출된 Feature에 대해  **코사인 거리 기반(K-NN)으로 유사한 상품** Ranking 후 Top12 추천

 → 시각적으로 유사한 상품들 추천해주는 결과 확인
















References
[1] Mathilde Caron, Piotr Bojanowski, Armand Joulin, and Matthijs Douze. Deep clustering for
unsupervised learning of visual features. CoRR, abs/1807.05520, 2018. URL http://arxiv.
org/abs/1807.05520.
[2] Yashar Deldjoo, Fatemeh Nazary, Arnau Ramisa, Julian J. McAuley, Giovanni Pellegrini, Alejandro Bellogín, and Tommaso Di Noia. A review of modern fashion recommender systems. CoRR,
abs/2202.02757, 2022. URL https://arxiv.org/abs/2202.02757.
[3] Gunnar Schröder, Maik Thiele, and Wolfgang Lehner. Setting goals and choosing metrics for
recommender system evaluations. 811, 01 2011.
[4] Hessel Tuinhof, Clemens Pirker, and Markus Haltmeier. Image based fashion product recommendation with deep learning. CoRR, abs/1805.08694, 2018. URL http://arxiv.org/abs/
1805.08694.
