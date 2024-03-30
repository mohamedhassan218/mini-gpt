# Mini GPT
A simulation to GPT language model but on the character level.

As the author said:
>    miniGPT tries to be small, clean, interpretable and educational, as most of the currently available GPT model implementations can a bit sprawling.

As you may know, GPT model uses tokens to predict words. Due to the lack of resources and data, this model do the same stages of GPT but on the character level not the tokens.

The owner of this code is Andrej Karpathy, who is one of the most productive persons in the AI field.

Prerequisites:
- [Bigram language model](https://www.analyticsvidhya.com/blog/2019/08/comprehensive-guide-language-model-nlp-python-code/#:~:text=A%20bigram%20language%20model%20is,in%20a%20text%20or%20sentence.).
- [Self-attention](https://medium.com/@geetkal67/attention-networks-a-simple-way-to-understand-self-attention-f5fb363c736d).
- [PyTorch](https://pytorch.org/).

You can find the source code of the project [here](https://github.com/karpathy/minGPT?tab=readme-ov-file).

You can find the tutorial in which he builds this code step by step with explanation [here](https://youtu.be/kCc8FmEb1nY?si=psCig6GBKbVHWXVH).

In this [notebook](https://colab.research.google.com/drive/1kNY87MIVt6Yifi0mSO9Gtr0mj_Q_iclo?usp=sharing), I've added some lines and print statements just for debugging and good understanding but the main structure is the same with Andrej code.

Feel free to take the code, customize it and try different ideas.