# Structured Reasoning project website

Source for the project homepage of **Structured Reasoning for LLMs: A Unified Framework for Efficiency and Explainability** (ICLR 2026).

[Live homepage](https://cnsdqd-dyb.github.io/structured-reasoning/) · [Main project repository](https://github.com/cnsdqd-dyb/Enhancing-Large-Language-Models-through-Structured-Reasoning) · [Public dataset](https://huggingface.co/datasets/FreeFrank/Structured-Reasoning)

## Website content

- `index.html`: research overview, official paper and PDF links, public dataset, loading example, open-source plan, and citation.
- `analyzer.html`: the existing interactive step-dependency research demonstration.
- `static/`: existing figures, styles, scripts, and demo data.

The dataset has 516 examples, 23 cognitive step types, and one training split, distributed under MIT. The conference paper and research demo are available. Training implementations, reproducibility scripts/configurations, and model checkpoints are planned; dates and licenses for those releases will be announced separately. See the main repository's [ROADMAP.md](https://github.com/cnsdqd-dyb/Enhancing-Large-Language-Models-through-Structured-Reasoning/blob/main/ROADMAP.md).

## Local preview

From the repository root:

```bash
python -m http.server 8000
```

Open `http://localhost:8000/`. Serve the files over HTTP so the demo can fetch its assets and example data. The homepage is a static page; the analysis demo loads browser-based dependencies separately.

GitHub Pages serves the existing project URL. The website repository and main project repository have distinct purposes: website source lives here, while dataset release documentation and the implementation roadmap live in the main repository linked by the original arXiv paper.
