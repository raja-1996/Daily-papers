# arXiv Recommender Systems Research Report

**Date:** 2026-03-08
**Coverage:** Papers from early 2026 (January–March), prioritizing the last 7 days

---

## 1. Scaling Laws & Large Recommendation Models

| Paper | Link | Key Details |
|-------|------|-------------|
| ⭐🔥 **ULTRA-HSTU: Bending the Scaling Law Curve in Large-Scale Recommendation Systems** | [arXiv:2602.16986](https://arxiv.org/abs/2602.16986) | **Meta** · 5x faster training scaling, 21x faster inference scaling vs conventional models. Deployed at scale serving billions of users with 4–8% engagement gains. |
| ⭐🔥 **Kunlun: Establishing Scaling Laws for Massive-Scale Recommendation Systems** | [arXiv:2602.10016](https://arxiv.org/abs/2602.10016) | Introduces GDPA, Hierarchical Seed Pooling, Sliding Window Attention, CompSkip for systematic scaling efficiency. |
| 🔥 **Principled Synthetic Data Enables the First Scaling Laws for LLMs in Recommendation** | [arXiv:2602.07298](https://arxiv.org/abs/2602.07298) | First evidence of robust power-law scaling for LLM-based recommenders via synthetic data curriculum (+130% recall@100 over real data). |
| ⭐🔥 **LUM: Unlocking Scaling Law in Industrial Recommendation Systems** | [arXiv:2502.08309](https://arxiv.org/abs/2502.08309) | Large User Model scaling to 7B parameters. Online A/B: +2.9% CTR, +1.2% RPM. |
| ⭐ **Climber: Toward Efficient Scaling Laws for Large Recommendation Models** | [arXiv:2502.09888](https://arxiv.org/abs/2502.09888) | Deployed on **Netease Cloud Music**. +12.19% online metric growth via balanced sequence/depth scaling. |
| 🔥 **Scaling Recommender Transformers to One Billion Parameters** | [arXiv:2507.15994](https://arxiv.org/abs/2507.15994) | **Meta** · KDD 2026. Recipe for training 1B-parameter transformer recommenders, extending HSTU beyond 176M. |

**Practical takeaway:** The industry consensus in 2026 is that scaling laws for recommendation require co-design of model architecture and system infrastructure — pure parameter scaling without efficiency innovations hits diminishing returns.

---

## 2. Industrial Ranking & CTR Prediction

| Paper | Link | Key Details |
|-------|------|-------------|
| ⭐🔥 **TokenMixer-Large: Scaling Up Large Ranking Models in Industrial Recommenders** | [arXiv:2602.06563](https://arxiv.org/abs/2602.06563) | **ByteDance** · Scales to 7B–15B params. Deployed across e-commerce (+1.66% orders), ads (+2.0% ADSS), live streaming (+1.4% revenue). Sparse MoE with FP8 and Token Parallel. |
| ⭐🔥 **MixFormer: Co-Scaling Up Dense and Sequence in Industrial Recommenders** | [arXiv:2602.14110](https://arxiv.org/abs/2602.14110) | **ByteDance** · Unified transformer jointly modeling sequential behaviors and feature interactions. Deployed on Douyin and Douyin Lite with engagement gains. |
| ⭐🔥 **RIA: Ranking-Infused Approach for Optimized Listwise CTR Prediction** | [arXiv:2511.21394](https://arxiv.org/abs/2511.21394) | **Meituan** · ACM Web Conference 2026. First framework unifying pointwise and listwise CTR. +1.69% CTR, +4.54% CPM in production. |
| 🔥 **Meta Lattice: Model Space Redesign for Cost-Effective Ads Recommendations** | KDD 2026 | **Meta** · Cost-effective architecture redesign for industrial ads ranking. |
| **RQ-GMM: Residual Quantized GMM for Multimodal Semantic Discretization in CTR** | [arXiv:2602.12593](https://arxiv.org/abs/2602.12593) | Bridges multimodal features into CTR prediction via residual quantization of Gaussian mixture models. |
| **MLPlatt: Simple Calibration Framework for Ranking Models** | [arXiv:2601.08345](https://arxiv.org/abs/2601.08345) | Converts ranker outputs to calibrated CTR probabilities. +10% improvement in F-ECE without ranking quality loss. |

**Practical takeaway:** ByteDance's TokenMixer-Large and MixFormer represent the new frontier of billion-scale ranking models with practical sparse MoE training; Meituan's RIA shows listwise CTR is production-ready.

---

## 3. Generative Recommendation & Semantic IDs

| Paper | Link | Key Details |
|-------|------|-------------|
| ⭐🔥 **CAUSE: Accelerating Generative Recommendation** | [arXiv:2601.19158](https://arxiv.org/abs/2601.19158) | WSDM 2026. 6x compute reduction vs HSTU with up to 39% higher accuracy at comparable cost. |
| **RankGPT: Towards Large-scale Generative Ranking** | [arXiv:2505.04180](https://arxiv.org/abs/2505.04180) | Action-oriented organization yields 78.7% speedup; 94.8% total training speedup with slight AUC improvement. |
| **ACERec: Unleash the Potential of Long Semantic IDs** | [arXiv:2602.13573](https://arxiv.org/abs/2602.13573) | Attentive Token Merger compresses long semantic IDs into fixed-size latents via content-adaptive aggregation. |
| **UniSID: End-to-End Semantic ID Generation for Ads Recommendation** | [arXiv:2602.10445](https://arxiv.org/abs/2602.10445) | Joint optimization of embeddings and semantic IDs from raw ad data. Up to +4.62% Hit Rate. |
| **QuaSID: Qualification-Aware Semantic ID Learning at Industrial Scale** | [arXiv:2603.00632](https://arxiv.org/abs/2603.00632) | Addresses semantic ID collisions by selectively repelling conflict pairs scaled by collision severity. |
| **Variable-Length Semantic IDs for Recommender Systems** | [arXiv:2602.16375](https://arxiv.org/abs/2602.16375) | Bridges recsys and emergent communication with adaptive-length item representations via discrete VAE. |
| **When Text-as-Vision Meets Semantic IDs** | [arXiv:2601.14697](https://arxiv.org/abs/2601.14697) | OCR-based text representations match or surpass standard text embeddings for semantic ID learning. |

**Practical takeaway:** Semantic IDs are becoming the dominant item representation paradigm for generative recommenders; collision handling (QuaSID) and efficient compression (ACERec) are the active research frontiers.

---

## 4. LLM-Powered Recommender Systems

| Paper | Link | Key Details |
|-------|------|-------------|
| **SafeCRS: Personalized Safety Alignment for LLM-Based Conversational RecSys** | [arXiv:2603.03536](https://arxiv.org/abs/2603.03536) | Proposes GDPO optimization for safety in conversational recommenders. First benchmark for CRS safety failures. |
| **Beyond Factual Correctness: Mitigating Preference-Inconsistent Explanations** | [arXiv:2603.03080](https://arxiv.org/abs/2603.03080) | Treats preference consistency as a first-class objective in explainable recommendation. |
| **Next-Gen RecSys Benchmark: Personalized Recommendation Assistant with LLMs** | [arXiv:2503.09382](https://arxiv.org/abs/2503.09382) | WSDM 2026. Benchmark with high-quality textual user queries reflecting real-world recommendation scenarios. |
| **CURec: Comprehensible Recommendation with LLM Fine-tuning** | [arXiv:2508.07595](https://arxiv.org/abs/2508.07595) | KDD 2026. LLMs generate and refine content features for content-aware, comprehensible recommendations. |
| **Can Explanations Improve Recommendations? Joint Optimization with LLM Reasoning** | [arXiv:2502.16759](https://arxiv.org/abs/2502.16759) | When properly calibrated, natural-language explanations measurably improve recommendation quality. |
| **AlignUSER: Human-Aligned LLM Agents for RecSys Evaluation** | [arXiv:2601.00930](https://arxiv.org/abs/2601.00930) | World-model-driven agents from human interactions for counterfactual trajectory generation. |
| **ScienceDB AI: LLM-Driven Agentic Recommender for Scientific Data** | [arXiv:2601.01118](https://arxiv.org/abs/2601.01118) | +200% CTR vs keyword search on one of the largest scientific data platforms. |
| **DUIP: Enhancing User Intent via LLMs** | [arXiv:2501.10871](https://arxiv.org/abs/2501.10871) | LSTM + LLM hybrid for dynamic user intent prediction. |

**Practical takeaway:** LLM-based recommenders are moving beyond basic integration toward safety alignment, explainability, and agentic architectures — signaling maturation of the paradigm.

---

## 5. Sequential & Behavior Modeling

| Paper | Link | Key Details |
|-------|------|-------------|
| 🔥 **PerSRec: Efficient Sequential Recommendation for Long-Term User Interest** | [arXiv:2601.03479](https://arxiv.org/abs/2601.03479) | **Meta** · Compresses long histories into learnable tokens. Compatible with HSTU and HLLM. Open source. |
| **Boundary-Aware Multi-Behavior Dynamic Graph Transformer** | [arXiv:2602.10493](https://arxiv.org/abs/2602.10493) | Dynamic graph structure reflecting evolving multi-behavior user patterns with transformer aggregation. |
| **Cross-Representation Knowledge Transfer for Sequential Recommendations** | [arXiv:2602.23471](https://arxiv.org/abs/2602.23471) | Aligns transformer and GNN representations for next-item prediction, outperforming pure sequential or graph approaches. |
| **Sensory-Aware Sequential Recommendation via Review-Distilled Representations** | [arXiv:2603.02709](https://arxiv.org/abs/2603.02709) | LLM-distilled sensory attributes from reviews consistently improve SASRec, BERT4Rec, BSARec. |
| **Multi-Behavior Sequential Modeling with Transition-Aware Graph Attention** | [arXiv:2601.14955](https://arxiv.org/abs/2601.14955) | Models click/buy/cart/favorite multi-type action sequences with transition-aware attention. |
| **Sparse Autoencoders for Sequential Recommendation: Interpretation and Control** | [arXiv:2507.12202](https://arxiv.org/abs/2507.12202) | Extends SAEs to sequential recsys for interpretable, monosemantic hidden state directions. |

**Practical takeaway:** Long-sequence compression (PerSRec) and multi-behavior modeling are the key practical advances; sensory-aware features from reviews represent a novel signal source.

---

## 6. On-Device & Efficient Recommendation

| Paper | Link | Key Details |
|-------|------|-------------|
| **OD-LLM: On-Device LLMs for Sequential Recommendation** | [arXiv:2601.09306](https://arxiv.org/abs/2601.09306) | WSDM 2026. 3.4x faster than GPTQ, 2.4x faster than SparseGPT. No effectiveness loss at 50% model size. |
| **NaCS: Efficient Content-based Recommendation Model Training** | [arXiv:2601.10067](https://arxiv.org/abs/2601.10067) | WWW 2026. Coreset construction via gradient matching with Monte Carlo Dropout uncertainty filtering. |
| **UG-Separation: Compute Only Once for Efficient Large Recommendation Models** | [arXiv:2602.10455](https://arxiv.org/abs/2602.10455) | Separates user-general computation to avoid redundant inference in large recommendation models. |

**Practical takeaway:** On-device LLM recommendation is viable in 2026 with tailored compression; OD-LLM's progressive alignment approach preserves sequential pattern quality.

---

## 7. Reranking & Listwise Optimization

| Paper | Link | Key Details |
|-------|------|-------------|
| **L2G: Listwise Reranking for Corpus Feedback** | [arXiv:2510.00887](https://arxiv.org/abs/2510.00887) | WSDM 2026. Induces document graphs from reranker logs — zero additional LLM calls. |
| **Rank-Nexus: Multimodal Image-Text Listwise Reranking** | [arXiv:2601.20623](https://arxiv.org/abs/2601.20623) | Lightweight 2B VLM achieves strong reranking on text (TREC, BEIR) and image (INQUIRE, MMDocIR) benchmarks. |
| **Autoregressive Ranking: Bridging the Gap** | [arXiv:2601.05588](https://arxiv.org/abs/2601.05588) | Survey of generative LLM reranking paradigms including RecRanker with pointwise + pairwise + listwise objectives. |

**Practical takeaway:** Listwise reranking is converging with generative models; L2G's zero-LLM-call graph approach is notable for production cost efficiency.

---

## 8. Multimodal Recommendation

| Paper | Link | Key Details |
|-------|------|-------------|
| **VIRAL: Vision-Language Information-Aware Recommendation** | [arXiv:2511.02113](https://arxiv.org/abs/2511.02113) | VLM-based visual enrichment with information-aware fusion via Partial Information Decomposition. |
| **Magic-MM-Embedding: Visual-Token-Efficient Multimodal Embedding** | [arXiv:2602.05275](https://arxiv.org/abs/2602.05275) | Visual token compression for efficient MLLM-based multimodal retrieval. |
| **Are Multimodal Embeddings Truly Beneficial for Recommendation?** | [arXiv:2508.07399](https://arxiv.org/abs/2508.07399) | Key finding: textual dominance overshadows visual signals in multimodal recommenders — visual modality is underutilized. |

**Practical takeaway:** Multimodal recsys suffers from textual dominance; VIRAL's information-aware fusion and Magic-MM's token compression are promising mitigations.

---

## 9. Graph Neural Networks for Recommendation

| Paper | Link | Key Details |
|-------|------|-------------|
| **On the Impact of GNNs in RecSys: A Topological Perspective** | [arXiv:2512.07384](https://arxiv.org/abs/2512.07384) | Monograph linking 13 topological dataset characteristics to GNN-based recommender behavior and performance. |
| **CFedGR: Cluster-Enhanced Federated GNN for Recommendation** | [arXiv:2412.08066](https://arxiv.org/abs/2412.08066) | Privacy-preserving GNN recommendation via federated clustering with communication-efficient strategies. |

**Practical takeaway:** GNN-based recommendation research is shifting toward understanding *why* GNNs work (topological analysis) and privacy-preserving federated settings.

---

## New Keywords Discovered

The following emerging topics were identified during Phase 1 and explored in Phase 2 follow-up queries:

| Follow-Up Query | Rationale |
|-----------------|-----------|
| `arxiv MixFormer TokenMixer ByteDance scaling recommendation 2026` | ByteDance emerged as a dominant publisher with multiple new architectures (MixFormer, TokenMixer-Large, Zenith) — needed dedicated coverage. |
| `arxiv semantic ID generative recommendation 2026` | Semantic IDs appeared across multiple Phase 1 results as a rapidly growing sub-field with 6+ papers in early 2026 alone. |
| `arxiv multimodal recommendation vision text embedding 2026` | Vision-text fusion in recsys surfaced in both the CTR and reranking searches, suggesting a cross-cutting trend. |
| `arxiv synthetic data recommendation model training 2026` | Synthetic data for scaling laws was a novel finding — traditionally absent from recsys but now enabling LLM scaling. |
| `arxiv on-device edge recommendation model compression 2026` | On-device LLM recommendation appeared as a new deployment paradigm at WSDM 2026, warranting deeper exploration. |
