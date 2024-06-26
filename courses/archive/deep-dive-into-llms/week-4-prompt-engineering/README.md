# Week 4 - Prompt Engineering



### This week you will...

* Master Prompt Engineering
* Familiarize yourself with different prompting frameworks

### Slides



### Until next week you should...

* Go through the learning material below
* Apply and try the learned prompt engineering techniques on your project and report on your findings in the next session



### Learning Resources

**Prompt engineering** is a relatively new discipline for developing and optimizing prompts(a.k.a the text inputs) **to get the best out** of large language models (LLMs) for a wide variety of tasks. This means that we manipulate the text input to the model with the goal to get the best or most desired output out of the model.

Prompt engineering skills generally help us to better understand the capabilities and limitations of LLMs just as they are very valuable to improve the capacity of LLMs on a wide range of common and complex tasks such as question answering and arithmetic reasoning.&#x20;

We can also look at it, that Prompt Engineering is referring to methods on how to communicate with the LLM to steer its behavior towards desired outcomes. One key point of prompt engineering methods is that they don't touch/change the model weights. **So the LLM is completely frozen and the only change is happening in the input values - the prompts.**

Prompt engineering is a very empirical science and the effect of specific prompt engineering methods can vary a lot among models, thus requiring heavy experimentation and heuristics.

We will now look at different prompt engineering methods..

## Basic Prompting <a href="#basic-prompting" id="basic-prompting"></a>

Zero-shot and few-shot learning are two most basic approaches for prompting the model, pioneered by many LLM papers and commonly used for benchmarking LLM performance.

### Zero-Shot <a href="#zero-shot" id="zero-shot"></a>

**Zero-shot learning** is to simply feed the task text to the model and ask for the result.

Prompt:

```
Classify the text into neutral, negative or positive. 

Text: I think this course is amazing.
Sentiment:
```

Output:

```
positive
```

As you see for sophisticated LLMs and easy enough tasks this is already enough to achieve the aim.

### Few-shot <a href="#few-shot" id="few-shot"></a>

**Few-shot learning** presents a set of demonstrations, each consisting of both input and desired output, on the target task. Normally they are high quality examples. As the model first sees good examples, it can better understand human intention and criteria for what kinds of answers are expected. Therefore, few-shot learning often leads to better performance than zero-shot. However, it comes at the cost of more token consumption.

Prompt:

```
A "whatpu" is a small, furry animal native to Tanzania. An example of a sentence that uses
the word whatpu is:
We were traveling in Africa and we saw these very cute whatpus.
To do a "farduddle" means to jump up and down really fast. An example of a sentence that uses
the word farduddle is:
```

Output\_

```
When we won the game, we all started to farduddle in celebration.
```



For further improvements we first have to understand which are the elements of a prompt.&#x20;

## Elements of a Prompt

A prompt contains any of the following elements:

**Instruction** - a specific task or instruction you want the model to perform

**Context** - external information or additional context that can steer the model to better responses

**Input Data** - the input or question that we are interested to find a response for

**Output Indicator** - the type or format of the output.

You do not need all the four elements for a prompt and the format depends on the task at hand.

### **Best Practices**

Usually, the more specific and relevant the context is to the task we are trying to perform, the better.

We should be very specific about the instruction and task we want the model to perform. The more descriptive and detailed the prompt is, the better the results. This is particularly important when we have a desired outcome or style of generation we are seeking. There aren't specific tokens or keywords that lead to better results. It's more important to have a good format and descriptive prompt. In fact, providing examples in the prompt is very effective to get desired output in specific formats.

Here a the golden 6 bullet points for good prompting:

1. Write as clearly and precisely as possible.
2. Provide as much context as possible/necessary.
3. Really use ChatGPT as a chat interaction.
4. Iterate until you are satisfied with the results.
5. Break down the task into individual steps.
6. Provide examples.

Next we will go to see specific prompting frameworks which increase the outputs especially for more complex tasks even more.

Ressources:

[https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/)
