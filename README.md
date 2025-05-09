Value-Spectrum
===============================================

[![Website](https://img.shields.io/website?url=https://value-spectrum.readthedocs.io)](https://value-spectrum.readthedocs.io)
[![GitHub](https://img.shields.io/badge/GitHub-Repo-black?logo=github)](https://github.com/yizhouzhao/LLM4SocialMedia)

![10 Shwatz values](big.png)

🌄 Welcome to Value-Spectrum
---------------------
Recent advances in Vision-Language Models (VLMs) have expanded their multimodal capabilities, yet evaluations often focus on functional tasks, overlooking deeper dimensions such as personality traits and human values.  
**Value-Spectrum** introduces a fresh perspective by offering a novel Visual Question Answering (VQA) benchmark designed to assess VLMs based on **Schwartz’s core human values**.

Built from a diverse database of over 50,000 short videos across TikTok, YouTube Shorts, and Instagram Reels, Value-Spectrum challenges VLMs to engage with value-centered content spanning topics like family, health, society, technology, and more.  
Through both general preference tests and persona-based simulations, Value-Spectrum reveals how VLMs express, prioritize, and adapt their value interpretations.



❤️ Preference Evaluation
---------------------

Value-spectrum is a novel Visual Question Answering benchmark to assess VLMs based on **Schwartz's value**: 

- 🤝 **Benevolence** — caring for and helping others
- 🌍 **Universalism** — understanding, appreciation, and protection of all people and nature
- 🧭 **Self-Direction** — independent thought and action
- 🏆 **Achievement** — personal success through demonstrating competence
- 🎢 **Stimulation** — excitement, novelty, and challenge in life
- 🍰 **Hedonism** — pleasure and sensuous gratification
- 🛡️ **Security** — safety, harmony, and stability of society and relationships
- 📏 **Conformity** — restraint of actions that might upset others or violate social norms
- 🧧 **Tradition** — respect, commitment, and acceptance of cultural or religious customs
- 👑 **Power** — social status, prestige, and control over people and resources

🎭 Evaluating Persona Alignment
---------------------

Beyond measuring value preferences, **Value-Spectrum** also explores how VLMs can **adopt specific personas** when explicitly prompted.

By simulating role-playing scenarios — such as a family-oriented individual, an adventurous spirit, or a tradition-respecting persona — we assess how flexibly and consistently VLMs can align their responses with distinct value sets.

This persona alignment evaluation offers deeper insights into:
- 🧩 How well VLMs can simulate human-like shifts in preferences based on assigned roles


🚀 Why Value-Spectrum?
---------------------

Value-Spectrum offers a unique, comprehensive way to track VLMs' preferences,  
understand their behavior in value-driven contexts, and test their ability to **simulate diverse personas**.

Whether you are benchmarking AI systems or exploring how machines can align with human values,  
**Value-Spectrum opens new pathways for understanding and improving VLM behavior**.

---------------------


```console
# Install required Python dependencies (MkDocs etc.)
pip install -r docs/requirements.txt

# Run the mkdocs development server
mkdocs serve
```

Using the example in your own project
-------------------------------------

If you are new to Read the Docs, you may want to refer to the [Read the Docs User documentation](https://docs.readthedocs.io/).

If you are copying this code in order to get started with your documentation, you need to:

1. place your `docs/` folder alongside your Python project. If you are starting a new project, you can adapt the `pyproject.toml` example configuration.
1. use your existing project repository or create a new repository on Github, GitLab, Bitbucket or another host supported by Read the Docs.
1. copy `mkdocs.yml`, `.readthedocs.yaml` and the `docs/` folder into your project.
1. customize all the files, replacing example contents.
1. Rebuild the documenation locally to see that it works.
1. *Finally*, register your project on Read the Docs, see [Importing Your Documentation](https://docs.readthedocs.io/en/stable/intro/import-guide.html).


Read the Docs tutorial
----------------------

To get started with Read the Docs, you may also refer to the [Read the Docs tutorial](https://docs.readthedocs.io/en/stable/tutorial/). It provides a full walk-through of building an example project similar to the one in this repository.
