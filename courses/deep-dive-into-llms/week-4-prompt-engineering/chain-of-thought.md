# Chain of Thought

Chain of Thought is essentially a prompting approach that gives the model not only more or better context like the previous methods (e.g. few-shot prompting, 6 golden prompting rules..) but let model think longer to get the correct answer. More thinking here means more computation. As you can see in the figure below without chain-of-thought thinking the model has basically just one forward pas through the transformer model to get to the correct answer. That might be enough for simple tasks like sentiment analysis but not enough for more complex tasks. With this think step by step approach the model can use more computations to get to the correct result. This is actually not very different from who human are instructed to work step by step through complex problems.

<figure><img src="../../../.gitbook/assets/grafik.png" alt=""><figcaption><p>Image Source: <a href="https://arxiv.org/abs/2205.11916">Kojima et al. (2022)</a></p></figcaption></figure>

