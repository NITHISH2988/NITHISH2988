# Hi, I'm Nithish

Third-year B.Tech Computer Science student building practical experience in AI/ML engineering. I enjoy understanding how model training, evaluation, retrieval, and serving fit together—not only calling a model API.

## Interests

- Classical machine learning and experiment design
- Deep learning and computer vision with PyTorch
- NLP, transformer inference, and model serving
- Retrieval-augmented generation and local inference
- Reproducible Python systems, testing, and MLOps foundations

## Selected projects

These projects are currently presented through open **draft release-candidate PRs**. The implementation and CI are on the `release-candidate/initial` branches while review is pending.

### [House Price Lab](https://github.com/NITHISH2988/house-price-lab)

A leakage-aware scikit-learn regression workflow comparing a mean baseline, Ridge, and Random Forest. Its reported metrics are from a deterministic synthetic dataset, not a real housing market.

- [Draft release candidate](https://github.com/NITHISH2988/house-price-lab/pull/1)
- Stack: Python, pandas, scikit-learn, FastAPI, pytest

### [Vision Bench](https://github.com/NITHISH2988/vision-bench)

An inspectable PyTorch CIFAR-10 training pipeline comparing a compact CNN with a ResNet-18 initialized from random weights. Full-dataset performance and CUDA behavior are not claimed as verified.

- [Draft release candidate](https://github.com/NITHISH2988/vision-bench/pull/1)
- Stack: Python, PyTorch, torchvision, scikit-learn metrics

### [Review Sentiment API](https://github.com/NITHISH2988/review-sentiment-api)

A TF-IDF/logistic-regression sentiment baseline with an optional pretrained transformer inference comparison and a FastAPI prediction interface. It includes no bundled review dataset or claimed real-corpus score.

- [Draft release candidate](https://github.com/NITHISH2988/review-sentiment-api/pull/1)
- Stack: Python, scikit-learn, FastAPI, Hugging Face Transformers (optional)

### [StudyBuddy RAG](https://github.com/NITHISH2988/studybuddy-rag)

A local-first document Q&A application with dense retrieval, SQLite persistence, source records, retrieval metrics, and optional Ollama integration. Retrieved citations identify passages; they do not prove every generated claim is supported.

- [Draft release candidate](https://github.com/NITHISH2988/studybuddy-rag/pull/1)
- Stack: Python, FastAPI, Sentence Transformers, NumPy, SQLite, Ollama (optional)

## Tools I use in these projects

Python · JavaScript · HTML/CSS · SQL/SQLite · PyTorch · scikit-learn · FastAPI · pandas · NumPy · pytest · Ruff · GitHub Actions · Docker · Ollama

## Currently learning

Model evaluation and data quality, deeper PyTorch internals, retrieval evaluation, reliable model serving, and practical MLOps. I prefer measured improvements and clear limitations over unsupported benchmark claims.
