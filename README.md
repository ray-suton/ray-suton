# Hi, I'm Rui Gao

I'm an AI undergraduate at the Mohamed bin Zayed University of Artificial Intelligence (MBZUAI), researching LLM reasoning, representations, and efficient inference. I enjoy music and climbing.

[LinkedIn](https://www.linkedin.com/in/rui-gao-gr/) | [Portfolio](https://ray-suton.github.io) | [GitHub](https://github.com/ray-suton)

## Research Interests

- LLM reasoning, including whether reasoning models accept valid mid-inference updates
- efficient inference for diffusion language models
- hidden-state representations, linear probing, and interpretability
- rigorous evaluation of language models and inference policies
- agentic systems
- computer vision, robotics, and performing arts

## Research & Publications

| Project | Status | What it shows |
| --- | --- | --- |
| Phase3Lock: Three-Phase Locking for Efficient Diffusion Language Models | In progress (Sep 2026-present) with Prof. Zhiqiang Shen and team; targeting ICML 2027 | Separates token commitment, representation reuse, and selective computation, showing that prior acceleration methods conflate at least two of these decisions. Governing each independently matches full-compute answer quality while improving inference efficiency. |
| LLM Reasoning Injection and Interruptible Reasoning: Selective Update Acceptance | In progress (Aug 2026-present) with Prof. Zangir Iklassov | A benchmark, to our knowledge the first, jointly testing whether reasoning models accept valid, authorized mid-inference updates while rejecting false claims and adversarial instructions, with a linear-probing study relating hidden-state representations of acceptance to model behavior. |
| EoKono: Benchmarking LLM's Understanding of Esperanto Language and Culture | Coauthor, under review at ACL Rolling Review | An Esperanto benchmark of 23 language models and 2,667 questions reviewed by nine qualified speakers, revealing gaps between linguistic knowledge and understanding of Esperanto history and culture. |
| [Metric Choice Determines Semantic Geometry in LLM Hidden States](https://github.com/ray-suton/LLM_Expansion) | First author, ICML 2026 Mechanistic Interpretability Workshop ([OpenReview](https://openreview.net/forum?id=PygdYDVgQc)) | Raw L2 tracks norm growth across layers, while centered cosine reveals semantic, topic, and category structure. |
| [Deadline-Valid Replay: Anytime-Valid Testing for LLM Inference Policies](https://github.com/ray-suton/Deadline_Valid) | First author, ICML 2026 Hypothesis Testing Workshop ([OpenReview](https://openreview.net/forum?id=KcqIBf7un6)) | An anytime-valid replay protocol separating apparent leaderboard gaps from certified policy-level advantages. |
| [SymStep: Symbolic Step Verification for Logical Reasoning](https://openreview.net/forum?id=THDsMgkDaj) | Coauthor, IJCAI-ECAI 2026 NILA Workshop | Step-wise symbolic verification with constraint-guided LLM reasoning; 97% accuracy on a ZebraLogicBench subset. |

## Experience

- **Machine Learning Engineer Intern, GenBio AI** (May 2026-Oct 2026): established expert-designed baselines for VCHarness, an agentic framework for biomedical model construction and prediction that combines an LLM coding agent, Monte Carlo Tree Search (MCTS), and biological foundation models. Optimized the MCTS-based search strategies, improving overall benchmark Macro-F1 by 7 percentage points.
- **Undergraduate Researcher, MBZUAI** (Aug 2025-present): AI for computer graphics with Prof. Lingqi Yan.

## Technical Stack

- Languages: Python, C++, SQL, TypeScript/JavaScript
- ML/AI: Deep learning, CNN, NLP, LLM evaluation, linear probing, interpretability, agentic systems
- Tools: PyTorch, Hugging Face Transformers, TensorFlow, Git/GitHub, Docker, Linux/HPC/GPU, Slurm

## Education, Honors, And Community

- B.S. in AI Engineering, MBZUAI, Aug 2025-expected Fall 2029 (GPA 3.82/4.0)
- MBZUAI Dean's List (Top 10%); Sheikh Tahnoon bin Zayed Scholarship in AI Excellence; Pioneer Scholarship
- Kaggle Gold Medal: Open Problems, Single-Cell Perturbations; Kaggle Silver Medal: HMS, Harmful Brain Activity Classification
- Reviewer, NeurIPS 2026 Sim2Science Workshop
- Founding Student Peer Tutor at MBZUAI: Calculus, Linear Algebra, DSA, and Deep Learning
- Founder and President, MBZUAI Climbing Club (50+ students)
