# TRIPLE: Theory-Driven Integration of Planned and Habitual Behaviors for LLM-based Personalization

**Theory-guided Reasoning for Intent and habIt Profiling with LLMs for pErsonalization**

This repository contains the project website for TRIPLE, a novel framework that systematically integrates dual-process theory from social psychology into LLM-based user modeling.

🌐 **Website**: [https://yestaehyung.github.io/aaai26-triple/](https://yestaehyung.github.io/aaai26-triple/)

📄 **Paper**: AAAI 2026

## Overview

TRIPLE addresses a key limitation in current LLM-based personalization: reliance on empirical heuristics that overlook the psychological mechanisms driving human behavior. Our framework:

- **Constructs a habitual behavior profile** by identifying repeated patterns over time to model automatic responses
- **Builds an intentional behavior profile** by inferring user attitudes, subjective norms, and perceived behavioral control based on the Theory of Planned Behavior (TPB)
- **Generates behavioral rationale** that reveals the interaction between habitual and intentional processes to predict user behavior in context-specific situations

## Key Features

- ✅ **Theory-driven**: First framework to systematically integrate dual-process theory into LLM-based personalization
- ✅ **Interpretable**: Provides psychologically grounded explanations for user behavior
- ✅ **Effective**: Achieves state-of-the-art results on LaMP benchmark, especially on generative tasks
- ✅ **Scalable**: Performance improves steadily with more user history

## Repository Structure

```
triple/
├── index.html          # Main website page
├── static/
│   ├── css/           # Stylesheets
│   ├── images/        # Images and figures
│   └── js/            # JavaScript files
└── README.md          # This file
```

## Citation

If you find TRIPLE useful for your work, please cite:

```bibtex
@inproceedings{noh2026triple,
  author    = {Noh, Taehyung and Jin, Seungwan and Yeo, Haein and Han, Kyungsik},
  title     = {TRIPLE: Theory-Driven Integration of Planned and Habitual Behaviors for LLM-based Personalization},
  booktitle = {Proceedings of the 40th AAAI Conference on Artificial Intelligence (AAAI-26)},
  year      = {2026},
  publisher = {AAAI Press}
}
```

## Authors

- **Taehyung Noh** - Department of Artificial Intelligence, Hanyang University
- **Seungwan Jin** - Department of Data Science, Hanyang University
- **Haein Yeo** - Department of Artificial Intelligence, Hanyang University
- **Kyungsik Han** (Corresponding Author) - Departments of AI and Data Science, Hanyang University

## License

This website is adapted from [Nerfies](https://nerfies.github.io), licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
