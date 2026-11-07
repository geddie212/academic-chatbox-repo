# Academic Chatbox — Exploring Procedural Understanding and AI Agents

**Using a USFCA-inspired Chatbox to Support Procedural Understanding in Academic Planning**

Paul Gedrimas, Cynthia Carnero, Lisa Jurca · CS 486 / CS 686, University of San Francisco

A research study comparing a baseline LLM chatbot against a Retrieval-Augmented Generation (RAG) enhanced agent for helping Computer Science undergraduates build a correct, prerequisite-aware, 4-year course plan from USFCA's course catalog.

The enhanced agent scrapes and chunks the USFCA CS course catalog, embeds it with OpenAI's `text-embedding-ada-002`, stores vectors in MongoDB, retrieves the most relevant chunks for a given user prompt via cosine similarity, and assembles a token-budgeted prompt before calling OpenAI's API — compared against a baseline agent that is effectively a plain ChatGPT shell.

Read the full paper: [`Academic_Planning_Chatbot_final.pdf`](./Academic_Planning_Chatbot_final.pdf)

## Contents

- Research questions and methodology (20-participant, double-blind study design)
- Data collection, study protocol, and quantitative analysis
- Results on whether the RAG-enhanced agent produced more accurate, useful course plans than the baseline
- Discussion, limitations, and future directions

Related project: [uni-chatbox](https://github.com/ljurca/uni-chatbox)
