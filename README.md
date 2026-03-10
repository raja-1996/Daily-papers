# Daily-papers

Daily papers from AI, ML, and RecSys research.

*Last updated: 2026-03-10*

## Papers by Topic

| Topic | File | Papers |
|-------|------|--------|
| Scaling Laws & Large Recommendation Models | [papers/scaling-laws-and-large-recommendation-models.md](papers/scaling-laws-and-large-recommendation-models.md) | 6 |
| Industrial Ranking & CTR Prediction | [papers/industrial-ranking-and-ctr-prediction.md](papers/industrial-ranking-and-ctr-prediction.md) | 8 |
| Generative Recommendation & Semantic IDs | [papers/generative-recommendation-and-semantic-ids.md](papers/generative-recommendation-and-semantic-ids.md) | 13 |
| LLM-Powered Recommender Systems | [papers/llm-powered-recommender-systems.md](papers/llm-powered-recommender-systems.md) | 8 |
| Sequential & Behavior Modeling | [papers/sequential-and-behavior-modeling.md](papers/sequential-and-behavior-modeling.md) | 6 |
| On-Device & Efficient Recommendation | [papers/on-device-and-efficient-recommendation.md](papers/on-device-and-efficient-recommendation.md) | 3 |
| Reranking & Listwise Optimization | [papers/reranking-and-listwise-optimization.md](papers/reranking-and-listwise-optimization.md) | 4 |
| Multimodal Recommendation | [papers/multimodal-recommendation.md](papers/multimodal-recommendation.md) | 4 |
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
