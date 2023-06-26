## GAI & LLMs Dictionary

One of the challenges when learning new technology or a field of study is understanding their commonly used terminologies and acronyms.  This repository aims to help those who are new to GAI and LLMs by providing a clear and concise definition of each of the commonly used terminologies and acronyms in these areas.  Each term in the dictionary is accompanied by a definition and a link to a relevant resource.

My hope is this GAI & LLMs Dictionary will become a valuable resource for anyone who is interested in learning about and keeping up with the rapidly evolding GAI and LLMs

Public contributions are very much welcome

**_The hottest new programming language is English_**

| Term/Acronym        | Definition           | Resource  |
| ------------------- |:--------------------:| ---------:|
| GAI                 | A type of AI that can create new content, such as text, images, videos, code, and more. An example of GAI is ChatGPT, Bard, Bing Chat,etc.  GAI can be used to automate, augment, and accelerate work.| |
| LLMs                | Large language models are a type of AI that are trained on massive datasets of text, code, books, and more. They are able capable of many NLP related tasks, such as generate text, translate languages, summarize text, extract meaning and intent, etc.| |
| GPT                 | Generated pre-trained transformer, which are ML models that are trained to understand natural language and code.  They provide text outputs in response to their input| [GPT models](https://platform.openai.com/docs/guides/gpt)|
| Tokens              | A unit of text. LLMs read and write text in chunks called tokens, which are common sequences of characters found in text.  LLMs understand the statistical relationships between tokens and excel at producing the next token in a sequence of tokens.  One token generally corresponds to ~4 characters of text for common English text, which translates to roughly 3/4 of a word.  This means 100 tokens is roughly equivalent to 75 words | [OpenAI tokenizer](https://platform.openai.com/tokenizer)|
|BPE                   | Byte pair encoding is a way of converting text into tokens.  It has many desire properties, such as reversible, lossless, compression, etc| [BPE github](https://github.com/openai/tiktoken) |
| Prompts             | The text inputs to GPTs | |
| Prompt engineering  | Also known as in-context prompting. It is referring to method and process of crafting effective prompts to elicite desired reponses from LLMs without updating their model weights. | [Prompt Engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/)|
| Zero-shot learning  |Learning to generalize to new classes without training. In other words, when a model successfully solves a problem that it was not explicitly trained on. | |
| Few-shot learning   | Also known as in-context learning. A method to enable LLMs to generate more accurate responses by providing a few examples (labeled data) to explain the intent or task instructions.   | |
| Transformer   | A deep learning model architecture used in NLP tasks | [Attention is all you need paper](https://arxiv.org/pdf/1706.03762.pdf)|
| Autoregressive model  |A type of model that predicts or genereate next token in a sequence based on the context of the preceding tokens. Examples of autoregressive models are RNN and tranformers  | |
| Fine-tuning  |The process of adapting a pre-trained LLM to new tasks | |
| Embedding  | A vector representation of a word or sequence | |
| Context window | Also known as context length.  The technical definition is the number of text tokens an LLM can process in a forward pass. This process aids in capturing contextual information for each token by taking into account neighbouring tokens.  In simpler terms, LLMs comprehend the meaning of a word by examining the words surrounding it.  A larger the context window allows LLMs to learn word representations more effectively, thereby enhancing the accuracy of predicting the next word in a sequence. [Anthropic introduced 100k tokens context window from 9k.](https://www.anthropic.com/index/100k-context-windows)   | [What's a Context Window Anyway?](https://www.linkedin.com/pulse/whats-context-window-anyway-caitie-doogan-phd/)|
| SFT | An acronym for supervised fine-tuning. A method to optimize the pretrainied model to generate responses that users are looking for ||
| RLHF | An acronym for reinforcement learning from human feedback.  It is a method that uses human preferences as a reward signal to fine-tune LLMs to improve the truthfulness and reduce the toxicity in the responses they produce. |[RLHF blog by Chip Huyen](https://huyenchip.com/2023/05/02/rlhf.html)|
