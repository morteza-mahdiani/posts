# Paper Title: NeuroCLIP: Brain-Aligned Vision-Language Pretraining
**Authors:** Smith et al.  
**Published in:** NeurIPS 2024  
**Link:** https://arxiv.org/abs/2401.00001  
**Tags:** `vision-language` `rsa` `neuroscience`

---

## 🔍 Summary
This paper introduces NeuroCLIP, a contrastive pretraining framework that aligns visual and textual embeddings with neural activity in the human brain.

## 🧠 Key Insights
- Brain-aligned objectives improve generalization in zero-shot tasks.
- RSA loss on fMRI data encourages more biologically plausible embeddings.
- Uses CLIP backbone with additional brain alignment head.

## 📊 Methods
- **Architecture / Model:** CLIP + linear projection to brain RDM space
- **Dataset(s):** NSD (Natural Scenes Dataset)
- **Loss Function:** Contrastive + RSA alignment loss
- **Evaluation Metrics:** RSA score, retrieval accuracy

## 🧪 Results
- NeuroCLIP outperforms vanilla CLIP on neural alignment benchmarks.
- Shows higher RSA scores in MST and VTC regions.

## 🤔 Critique / Thoughts
- Strengths:
  - Integrates cognitive neuroscience into VLM training.
- Weaknesses:
  - Assumes RSA is the ideal metric—could explore alternatives.
- Opportunities:
  - Apply to other sensory modalities or extend to continual learning.

## 🔗 Relevance to My Work
- Directly relates to my master’s project on aligning vision models with brain data.
- I can build on their RSA-based loss function for my own training loop.
