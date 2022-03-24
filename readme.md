
# 모두의 연구소 
## 설명가능 인공지능 기획
- 1회차 
- 2회차

# Introduction
모두의 연구소에서 진행했던, 설명가능 인공지능 XAI 관련 코드 리뷰를 작성하는 repo입니다.
해당내용은 알려져있는 Opensource 를 제멋대로 해석해서 공유하려하는 목적으로 만들어져있습니다.
fork 로 작성하면 공부가 전혀 안되는 까닭으로, 참고하는 repo만 주석으로 링크로 만들어서 공유하고
내부내용은 어느정도 자율적으로 진행할 예정입니다.

# Scope
큰 분류는 다음의 책에 따르며, 해당 내용은 크리스토프 아재 글을 공부하면서 정리할 예정입니다. + 과거에 했던 내용도 같이 정리합니다.
- 1차. 논문의 리뷰 (Notion 정리)
- 2차. Colab 등을 통한 간단한 시연
- 3차. 최종적으로 누구나 볼수 있게하는 Web 상의 Embedding 및 시각화 

# Index
## Global Model-Agnostic [\[8\]](https://christophm.github.io/interpretable-ml-book/global-methods.html)
- PDP (ref.Sklearn)
- ALE Plot (ref.Sklearn)
- H-statistic (ref.Sklearn)
- Feature Importance (ref.Sklearn)

## Local Model-Agnostic [\[9\]](https://christophm.github.io/interpretable-ml-book/local-methods.html)
- ICE (ref.Sklearn)
- LIME (ref.marcotcr lime)
- SHAP (ref.slundberg shap)

## Neural Network Interpretation [\[10\]](https://christophm.github.io/interpretable-ml-book/neural-networks.html)
- Learned Features
- TCAV

### Pixel Attention [\[10.2\]](https://christophm.github.io/interpretable-ml-book/pixel-attribution.html)
- Saliency Maps
- CAM
- Grad-CAM
- Adversarial Examples


# Reference 
- https://christophm.github.io/interpretable-ml-book/
- https://github.com/marcotcr/lime
- https://github.com/slundberg/shap
- https://github.com/pytorch/captum
