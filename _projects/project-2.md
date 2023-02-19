---
title: 基于网络表征学习的实时动态Top-N推荐技术研究

description: Real-time and Dynamic Top-N Recommendation based on Network Representation Learning

people:
  - liuqidong
  - yaoenguang
  - liuchaoyue
  - qiuzixin
  - gaoxiaofeng
  - niushaoyao
  - lixiaowen
  - hewenxuan
  - zhangshilin
  - shenxin
  - gaofei

layout: project
last-updated: 2023-01-01
---



现有关于推荐系统的研究主要集中在如何提升推荐算法的质量，却忽视了推荐系统的实时性和动态可扩展性。实时性指的是推荐系统针对用户个性化请求快速反馈的能力，关乎用户体验；动态可扩展性指的是推荐系统根据动态变化数据实时更新推荐策略的能力，关乎系统生命周期。推荐系统的实时性和动态可扩展性非常关键，不亚于推荐算法精度的重要程度。机器学习算法已经在许多领域展示出强大的数据处理能力，是解决推荐系统实时推荐的最优选择。但是由于主流机器学习算法不擅长处理推荐系统中的网络数据，且静态的机器学习算法模型不能够根据动态变化的网络数据实时更新，制约了主流机器学习算法在推荐系统领域的推广。针对上述问题，我们提出用网络表征学习算法将动态变化的网络数据转化为实时更新的节点矢量，之后再用静态的机器学习算法模型进行快速预测，从而实现推荐系统的实时动态反馈，提升推荐系统的整体实用性。



***In English:***

### Real-time and Dynamic Top-N Recommendation based on Network Representation Learning

The recent researches on recommender systems mainly focus on how to improve the commendation quality, but ignore the real-time and dynamic characteristics of recommender systems. The real-time performance denotes the quickly respond ability of users' personalized requests, which is related to user experience. The dynamic performance refers to the real-time update ability of the recommendation strategy according to the dynamic changing data, which is associated with the life cycle of the systems. The real-time and dynamic of recommender systems are extremely important, not less than the accuracy of recommendation algorithms. With powerful data processing capabilities in many areas, machine learning algorithms are the optimal choice for real-time recommendation. However, the mainstream machine learning algorithms are not good at processing network data in the recommender systems, and the static machine learning algorithm models cannot be updated in real time according to the dynamic network data, which restrict the promotion of the mainstream machine learning algorithms in the recommender systems field. To solve the above problems, we propose network representation learning algorithms to transform dynamic network data into real-time updated node vectors, and then use static machine learning algorithm models to make rapid prediction, so as to realize real-time dynamic feedback of recommender systems and improve the overall practicability of recommender systems.
