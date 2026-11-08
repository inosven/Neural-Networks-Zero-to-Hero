# Neural Networks: Zero to Hero — 学习笔记

[English](README.md) | 简体中文

跟着 Andrej Karpathy 的课程 [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) 从零开始学习神经网络，边看视频边手敲代码。

## 目录

| 课程 | 内容 | 文件 |
| --- | --- | --- |
| 1. micrograd | 从零实现标量自动求导引擎和反向传播，搭一个小型 MLP | [`micrograd/micrograd_from_scratch_yay.ipynb`](micrograd/micrograd_from_scratch_yay.ipynb) |
| 1. micrograd 练习 | 课后练习 | [`Copy of micrograd_exercises.ipynb`](Copy%20of%20micrograd_exercises.ipynb) |
| 2. makemore | 字符级语言模型：bigram 计数 → 神经网络 | [`makemore.ipynb`](makemore.ipynb) |

数据集：[`Data/names.txt`](Data/names.txt)（约 32k 个英文名字，makemore 使用）

## 课程进度

- [x] micrograd — 反向传播与自动求导
- [ ] makemore Part 1 — bigram 语言模型
- [ ] makemore Part 2 — MLP
- [ ] makemore Part 3 — 激活值、梯度与 BatchNorm
- [ ] makemore Part 4 — 手写反向传播
- [ ] makemore Part 5 — WaveNet
- [ ] GPT — 从零构建 GPT
- [ ] Tokenizer — 构建 GPT 分词器

## 运行

```bash
python -m venv .venv
source .venv/bin/activate
pip install jupyter numpy matplotlib torch graphviz
jupyter notebook
```

部分 notebook 也可以直接在 Google Colab 中打开运行。

## 参考

- 课程主页：https://karpathy.ai/zero-to-hero.html
- YouTube 播放列表：https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ
- 官方代码：[karpathy/micrograd](https://github.com/karpathy/micrograd)、[karpathy/makemore](https://github.com/karpathy/makemore)、[karpathy/nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero)
