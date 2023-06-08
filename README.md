*A talk from [MediaParty 2023](https://mediaparty.org/)*

# How I convinced GPT to teach me about Hungarian folktales (without speaking a word of Hungarian)

I promise this is actually about data journalism and generative AI, even if you reaaaally don't believe it! Based on my post [Multi-language document Q&A with LangChain and GPT-3.5-turbo](https://jonathansoma.com/words/multi-language-qa-gpt.html) from March 2023.

**Material:**

* [Slides live here](presentation.pdf)
* [Notebook with examples](multilingual-embeddings-walkthrough.ipynb), or you can [run it live online using Google Colab](https://colab.research.google.com/github/jsoma/mediaparty-folktales/blob/main/multilingual-embeddings-walkthrough.ipynb)

**Data sources:**

* [Eredeti népmesék](https://www.gutenberg.org/ebooks/38852) on Project Gutenberg (a nice text file!)
* [Eredeti népmesék](https://www.google.com/books/edition/Eredeti_n%C3%A9pmes%C3%A9k/FcZSEAAAQBAJ?hl=en) on Google Books (the original!)

**Tools and tech:**

* [langchain](https://python.langchain.com/en/latest/index.html) for anything and everything
* [Our embeddings](https://huggingface.co/sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2) on HuggingFace
* [Chroma](https://www.trychroma.com/) vector database
* [LlamaIndex](https://gpt-index.readthedocs.io/en/latest/) for an alternative to langchain

**Contact me:**

* [js4571@columbia.edu](js4571@columbia.edu)
* [@dangerscarf](https://twitter.com/dangerscarf)