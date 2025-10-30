<h2>LLM from Scratch</h2>
<p align="justify">
An attempt to replicate how large language models (LLMs) like ChatGPT are built—on a much smaller scale. Credits: <a href="https://home.vizuara.ai/">Vizuara AI Labs</a>.
</p>

---

**01-main** : This notebook closely follows the lecture series up to Lecture 31 (saving and loading LLM weights using PyTorch).  

**02-clean** : A more refined and organized version of `01-main`, containing only the core components essential to building the model.  

**03-openai-32** : Implementation corresponding to Lecture 32.  

**04-classification-finetuning** : Implements fine-tuning the LLM for a spam-vs-ham text classification task.  

**05-instruction-finetuning** : Implements instruction-based fine-tuning for allowing the transformer to generate responses conditioned on given instructions. The dataset used was `instruction-data.json`.  

**08-encoder-decoder** : My attempt at building an encoder–decoder transformer by implementing cross-attention from scratch (not part of the lecture series). The architecture follows the model proposed in the paper *“Attention Is All You Need.”* However, this implementation still requires significant modifications and refinement.