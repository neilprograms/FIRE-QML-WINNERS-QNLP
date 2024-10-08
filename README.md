**<h1>Quantum Natural Language Processing (QNLP): Solving Complex Language Problems with Quantum Computing</h1>**
**<h2>Overview</h2>**
Welcome to our Quantum Natural Language Processing (QNLP) project. In this repository, we are tackling one of the cutting-edge frontiers in technology: leveraging quantum computing to solve natural language processing (NLP) problems. This README provides a detailed yet simplified explanation of the problem we're addressing, how we are approaching it, and why this is exciting for both the NLP and quantum computing communities.

**<h2>The Problem</h2>**
Natural language processing (NLP) is about teaching computers to understand and interpret human language. However, as language is extremely nuanced and complex, many NLP models require substantial computational resources to process text efficiently. Classical (non-quantum) computers are limited in how fast and effectively they can handle these operations.

This is where quantum computing comes in. Unlike classical computers, which process data in binary (1s and 0s), quantum computers use qubits, which allow for much more complex operations. The hope is that by using quantum computing, we can speed up tasks and even solve problems that are currently too difficult for classical computers. In our case, we are looking at how quantum computing can enhance NLP tasks like sentence classification and meaning extraction.

**<h2>Why Is This Important?</h2>**
The potential of quantum computing lies in its ability to handle tasks exponentially faster than classical computers. In fields like cryptography, chemistry, and now NLP, quantum computers could provide the computational power necessary to make huge leaps forward. In particular, understanding human language better and faster has implications for everything from AI assistants like Siri or Alexa, to medical research, legal automation, and much more.

However, quantum computing is still in its early stages. Current machines are limited (referred to as Noisy Intermediate-Scale Quantum or NISQ computers), meaning they are not yet fully capable of showing dramatic improvements over classical systems for most tasks. Yet, exploring how quantum computers handle language can help us pave the way for future breakthroughs when more advanced quantum machines become available.

**<h2>Our Approach (Add to this, this is only what the previous paper did)</h2>**
Our project aims to take the first steps into the new frontier of QNLP by running NLP tasks on quantum hardware. Specifically, we focus on sentence classification tasks. We generate representations of sentences, turning them into data structures that quantum computers can process more naturally. Our approach is grounded in a model called DisCoCat (Distributional Compositional Categorical model of meaning), which maps how sentences are structured to quantum circuits, the foundation of quantum computation.

We compare how different models perform, including:

<li>Bag-of-words: Where sentence structure is ignored, and words are treated as an unordered collection.</li>
<li>Word-sequence model: Which considers the order of words, but not deeper syntactic structures.</li>
<li>Syntax-sensitive model (DisCoCat): Which takes into account grammatical structure, producing more linguistically sound results.</li>
<h3>Datasets and Tasks</h3>
For our experiments, we use two small datasets:

<ol>
  <li>A dataset of 130 sentences related to food and IT, with a goal of classifying sentences into one of the two categories (binary classification task). <i>file beginning with mc</i></li>
  <li>A dataset of 105 noun phrases extracted from a linguistic dataset. Here, the task is to predict whether a phrase contains a subject-based or object-based relative clause. <i>file beginning with by rp</i></li>
</ol>

These tasks, though simple by traditional NLP standards, present significant challenges for current quantum computers due to their limited computational power.
**<h2>Key Takeaways from Our Work (TBD)</h2>**
TBD
**<h2>Installation and Setup (TBD)</h2>**
TBD

**<h2>References</h2>**
<ol>
  <li>https://github.com/CQCL/qnlp_lorenz_etal_2021_resources/tree/main</li>
</ol>
