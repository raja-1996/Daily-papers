# Daily-papers

Daily papers from AI, ML, and RecSys research.

*Last updated: 2026-03-18*

## Papers by Topic

| Topic | File | Papers |
|-------|------|--------|
| Scaling Laws & Large Recommendation Models | [papers/scaling-laws-and-large-recommendation-models.md](papers/scaling-laws-and-large-recommendation-models.md) | 7 |
| Industrial Ranking & CTR Prediction | [papers/industrial-ranking-and-ctr-prediction.md](papers/industrial-ranking-and-ctr-prediction.md) | 10 |
| Generative Recommendation & Semantic IDs | [papers/generative-recommendation-and-semantic-ids.md](papers/generative-recommendation-and-semantic-ids.md) | 21 |
| LLM-Powered Recommender Systems | [papers/llm-powered-recommender-systems.md](papers/llm-powered-recommender-systems.md) | 14 |
| Sequential & Behavior Modeling | [papers/sequential-and-behavior-modeling.md](papers/sequential-and-behavior-modeling.md) | 8 |
| On-Device & Efficient Recommendation | [papers/on-device-and-efficient-recommendation.md](papers/on-device-and-efficient-recommendation.md) | 3 |
| Reranking & Listwise Optimization | [papers/reranking-and-listwise-optimization.md](papers/reranking-and-listwise-optimization.md) | 5 |
| Multimodal Recommendation | [papers/multimodal-recommendation.md](papers/multimodal-recommendation.md) | 5 |
| Graph Neural Networks for Recommendation | [papers/graph-neural-networks-for-recommendation.md](papers/graph-neural-networks-for-recommendation.md) | 2 |

## Emerging Search Queries for arXiv RecSys Tracking

The following queries were discovered through adaptive follow-up analysis and should be added to regular monitoring:

### Scaling & Architecture
- `arxiv MixFormer TokenMixer ByteDance scaling recommendation` — ByteDance is publishing a family of billion-scale ranking architectures (MixFormer, TokenMixer-Large, Zenith) that represent a new paradigm in co-scaling dense and sequence components.
- `arxiv ULTRA-HSTU Meta generative recommendation scaling` — Meta's HSTU lineage continues to evolve with ULTRA-HSTU and billion-parameter extensions.

### Semantic IDs
- `arxiv semantic ID generative recommendation` — Semantic IDs (discrete item tokenization) are becoming the dominant representation for generative recommenders, with 6+ papers in early 2026 covering collisions, variable-length IDs, end-to-end learning, and multimodal representations.

### Multimodal RecSys
- `arxiv multimodal recommendation vision text embedding` — Vision-text fusion is a cross-cutting trend appearing in CTR prediction, reranking, and generative recommendation. Key challenge: textual dominance over visual signals.

### Synthetic Data
- `arxiv synthetic data recommendation model training` — Synthetic data is enabling the first scaling laws for LLM-based recommenders, with +130% recall improvements over real data training.

### On-Device / Edge
- `arxiv on-device edge recommendation model compression` — On-device LLM recommendation is production-viable in 2026 with tailored compression (OD-LLM at WSDM 2026).

### LLM Safety & Explainability in RecSys
- `arxiv LLM safety alignment conversational recommender` — Safety alignment for LLM-based conversational recommenders is an emerging concern (SafeCRS, GDPO).
- `arxiv explainable recommendation LLM reasoning` — Preference-consistent explanations and joint optimization of explanations with recommendations are new research directions.

### Listwise & Generative Reranking
- `arxiv listwise reranking generative LLM recommendation` — Listwise reranking is converging with generative models; autoregressive ranking and zero-LLM-call graph approaches are notable.

### Post-Training & Alignment for Generative Recommenders
- `arxiv post-training RLHF alignment generative recommender` — Post-training/alignment for generative recommenders is a fast-growing subfield; exponential reward-weighted SFT, SAGE, and GRC all address reward collapse and hacking issues.

### Cold-Start with Multimodal LLMs
- `arxiv cold-start multimodal LLM CTR prediction embedding` — Multimodal LLMs for cold-start CTR is a distinct new production pattern (IDProxy at Xiaohongshu, MARS at Kuaishou).

### Constrained Generative Reranking
- `arxiv constraint-aware generative reranking advertising` — Constrained optimization in generative reranking (CGR) is emerging as a distinct problem from unconstrained listwise reranking.

### Hierarchical Session-Aware Generative Recommendation
- `arxiv hierarchical preference-aware generative recommendation` — Session-hierarchical modeling (HPGR, HiGR) is a clear architectural trend beyond flat-sequence HSTU approaches.

### RL/Reward Optimization for Recommenders
- `arxiv recommendation reinforcement learning reward model` — RL/reward optimization is converging with generative rec (MiniRec data-efficient RL, SAGE sequence-level RL, Robust Post-Training).

### Diffusion Models for Generative Recommendation
- `arxiv diffusion model generative recommendation semantic ID` — Masked discrete diffusion (DiffGRM, MaskGR, LLaDA-Rec, MDGR) is emerging as the primary non-autoregressive alternative for semantic ID generation, with WWW 2026 and KDD 2026 publications.

### Continual/Incremental LLM Personalization
- `arxiv preference drift incremental learning LLM recommender` — Preference drift adaptation (RAIE, SPRInG) is becoming a distinct subfield, using region-aware LoRA editing and drift-driven selective parametric updates.

### RL-from-RecSys-Feedback for LLMs
- `arxiv reinforcement learning LLM recommendation closed-loop reward` — Closed-loop RL from rec model feedback (Rec-R1, ReRe) is a new training paradigm distinct from SFT distillation, enabling LLMs to optimize directly against recommendation metrics.

### Embedding Backbones for Recommendation
- `arxiv embedding backbone recommendation contrastive semantic ID` — Purpose-built embedding backbones (EncodeRec) that align PLM representations with rec objectives are solving semantic ID collision and improving generative rec tokenization quality.
