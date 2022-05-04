tensorflow code read
===

2015年11月9日，Google发布深度学习框架TensorFlow并宣布开源，并迅速得到广泛关注，在图形分类、音频处理、推荐系统和自然语言处理等场景下都被大面积推广。
TensorFlow系统更新快速，官方文档教程齐全，上手快速且简单易用，支持Python和C++接口。本文依据对Tensorflow（简称TF）白皮书[1]、TF Github[2]和TF官方教程[3]的理解，从系统和代码实现角度讲解TF的内部实现原理。

2022年是不寻常的一年，疫情肆虐，俄乌冲突。五一假期也不敢去乌克兰旅游，百无聊赖之际，阅读tensorflow源码，于是乎，就记录下来。

tensorflow 目前已经迭代到2.9版本， 不知道几年是不是要迭代到3.0，我选却了2.6版本作为基准。

[origin README](README_origin.md)

# 论文汇总
- [TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems](https://arxiv.org/abs/1603.04467)


# 源码分析

* [源码目录](docs/directory.md)
* [基本概念](docs/base_concept.md)
