# Transformer Training 04 — Optimisers: SGD, Momentum, Adam, AdamW

The gradient says which way is downhill; the optimiser decides how far, and in which direction exactly. SGD, momentum, Adam's two moments and bias correction, AdamW's decoupled weight decay, run live on a narrow valley and measured on the real model.

**Live site:** https://brendanjameslynskey.github.io/Transformer_Training_04_Optimisers/

SGD in a narrow valley (live); momentum; Adam's moments and bias correction; AdamW's decoupled weight decay; the four optimisers on the real model; optimiser state; newer optimisers in context.

## Live, animated companion

This deck is the slide companion to Part 2 (Training) of [Transformer Decoder Explained](https://transformer-decoder-explained.vercel.app/training), where the same model trains in your browser:

- [Chapter 5: Optimisers](https://transformer-decoder-explained.vercel.app/training/05-optimisers)

## Where the numbers come from

Every measured number on these slides comes from the site's [results.md](https://github.com/BrendanJamesLynskey/transformer-explainer/blob/main/results.md) (seeded NumPy reference runs; CI recomputes them), filled in at build time from its `results.json`. Numbers from papers are cited on the slide with a link. The model is tiny (5,376 parameters, one book, a CPU): its runs show mechanisms, not what happens at scale, and the slides say so where it matters. GPU runs of the site's Colab notebooks are pending; no GPU number appears here.

Part of the [Transformer Training sub-hub](https://github.com/BrendanJamesLynskey/LLM_Hub_Transformer_Training) &middot; [LLMs hub](https://github.com/BrendanJamesLynskey/LLMs)
