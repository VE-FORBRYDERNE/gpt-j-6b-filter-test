[GPT-J-6B](https://github.com/kingoflolz/mesh-transformer-jax) is a GPT-like language model from EleutherAI for text generation.

This is a version of their inference Colab notebook with an additional `repetition_penalty` setting that makes tokens that have already appeared less likely to reappear in the hopes that it improves the quality of the output text. The technique was originally described in section 4.1 of [this paper](https://arxiv.org/pdf/1909.05858.pdf).

[You can try out this new Colab notebook here.](https://colab.research.google.com/github/VE-FORBRYDERNE/gpt-j-6b-filter-test/blob/main/infer.ipynb)
