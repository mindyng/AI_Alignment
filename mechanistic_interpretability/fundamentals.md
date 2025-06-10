1. [Barebones Pre-req's](https://www.neelnanda.io/mechanistic-interpretability/prereqs)
2. [Neel Nanda's Updated Quickstart Guide 2023](https://apartresearch.com/news/updated-quickstart-guide-for-mechanistic-interpretability)
3. [Neel Nanda's Get Started](https://www.neelnanda.io/mechanistic-interpretability/getting-started)
4. [Interpretable ML - 2019](https://christophm.github.io/interpretable-ml-book/)
5. [Survey of LLM's](https://arxiv.org/abs/2303.18223)
6. [ARENA Fundamentals](https://arena-chapter0-fundamentals.streamlit.app/)
7. [ARENA Transformers from Scratch](https://arena-chapter1-transformer-interp.streamlit.app/[1.1]_Transformer_from_Scratch)
8. [Notes from The Utility of Interpretability](https://www.youtube.com/watch?v=9YQW2mH9FyA)

0-80% for Mech Interp
- Superposition - bunch of things crammed into neurons
- how does model represent 'red'
-- what direction does model store this? - features as directions (5 directions)
-- can allow model to represent more concepts than it has dimensions
-- want model to extract these concepts automatically - SAE's
-- supervision signal- take neurons, learn a model that will expand them to actual concepts in neurons (5 concepts) and contract it back what it was (model you are training) by incentivizing it to be sparse, only 2 features active at a time
-- if it works, dictionary to decode neurons: this direction, unknown but model is pointing in red direction
- features --> circuits (algorithms)

current activity: building models to make them more interpretale faster
Induction Heads - in pairs, copying over what was seen after a word when first word is repeated
