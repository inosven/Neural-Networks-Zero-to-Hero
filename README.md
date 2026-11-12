# Neural Networks: Zero to Hero — Study Notes

English | [简体中文](README.zh-CN.md)

My notes and code while working through Andrej Karpathy's [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html) course — building neural networks from scratch, typing out the code alongside the videos.

## Contents

| Lecture | Topic | File |
| --- | --- | --- |
| 1. micrograd | A scalar-valued autograd engine and backpropagation from scratch, plus a tiny MLP | [`micrograd/micrograd_from_scratch_yay.ipynb`](micrograd/micrograd_from_scratch_yay.ipynb) |
| 1. micrograd exercises | Post-lecture exercises | [`Copy of micrograd_exercises.ipynb`](Copy%20of%20micrograd_exercises.ipynb) |
| 2. makemore | Character-level language model: bigram counting → neural network | [`makemore.ipynb`](makemore.ipynb) |
| 2. makemore exercises | Bigram post-lecture exercises | [`makemore_bigram_excercise.ipynb`](makemore_bigram_excercise.ipynb) |
| 3. makemore Part 2 | MLP language model: embeddings, train/dev/test splits, sampling | [`makemore_Part_2_MLP.ipynb`](makemore_Part_2_MLP.ipynb) |
| 4. makemore Part 3 | Activations, gradients & BatchNorm (in progress) | [`Building_makemore_Part_3_Activations_&_Gradients,_BatchNorm.ipynb`](Building_makemore_Part_3_Activations_%26_Gradients%2C_BatchNorm.ipynb) |

Dataset: [`Data/names.txt`](Data/names.txt) (~32k English names, used by makemore)

## Progress

- [x] micrograd — backpropagation and autograd
- [x] makemore Part 1 — bigram language model
- [x] makemore Part 2 — MLP
- [ ] makemore Part 3 — activations, gradients & BatchNorm (in progress)
- [ ] makemore Part 4 — becoming a backprop ninja
- [ ] makemore Part 5 — WaveNet
- [ ] GPT — building GPT from scratch
- [ ] Tokenizer — building the GPT tokenizer

## Running

```bash
python -m venv .venv
source .venv/bin/activate
pip install jupyter numpy matplotlib torch graphviz
jupyter notebook
```

Some notebooks can also be opened and run directly in Google Colab.

## References

- Course page: https://karpathy.ai/zero-to-hero.html
- YouTube playlist: https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ
- Official code: [karpathy/micrograd](https://github.com/karpathy/micrograd), [karpathy/makemore](https://github.com/karpathy/makemore), [karpathy/nn-zero-to-hero](https://github.com/karpathy/nn-zero-to-hero)
