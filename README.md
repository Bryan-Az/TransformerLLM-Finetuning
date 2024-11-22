# TransformerLLM-Finetuning

In this repo, I experiment with the transformer LLM architecture by finetuning Nanogpt, and implement a case study of a dataset to evaluate the performance of the LLM.
 

## NanoGPT from Scratch
I implement nanogpt from scratch using low level code in pytorch. I'll took help from a code interpreter / gpt4 plugin. The code is modular, available in colab and has debug functionality. The result of this section is summarized within a medium article. The model is evaluated on its ability to handle input and make inference with a short video presentation.

[Link to the Medium Article](https://medium.com/@alexyszam/what-i-learned-building-a-mini-gpt-transformer-model-e11027f1190d)

### References

1. https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing#scrollTo=EDarxEWIRMKq
2. https://www.youtube.com/watch?v=kCc8FmEb1nY&t=18s
3. [Prof. Eranti's Lecture, CMPE 297](https://docs.google.com/presentation/d/1fk8QlODYkBTTH4ftw8M7Sw_tmhJa8KB97s7dYP6s4mI/edit#slide=id.g24535d0c6d4_0_178)

## The "Textbooks are all you need" Case Study
I implement a "textbooks are all you need" case study with a book of my choice. The goal is to train a model to understand the book using the colab A100 environment, using a smaller amount of data to be able to train on a single GPU and using ChatGPT-4s code interpreter abilities.


### References 

1. https://www.youtube.com/watch?v=gmFi6W8DPdM
2. https://github.com/jina-ai/textbook
3. https://colab.research.google.com/drive/1T4IfGfDJ8uxgU8XBPpMZivw_JThzdQim?usp=sharing
4. https://arxiv.org/pdf/2306.11644.pdf
