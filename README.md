# Sami Chellia

AI Engineer, Data & AI. Master of Engineering from ESILV (2026), after three years as a Data & AI engineer apprentice at Orange.

I work on small language models, model compression and evaluation methodology. In every project below, the results come with fixed seeds, held-out test sets, reference baselines and the limits of what was measured.

## Projects

| Project | Summary | Stack |
|---|---|---|
| [tinyllm-compression-pipeline](https://github.com/samichellia90-bit/tinyllm-compression-pipeline) | Distilling Qwen2.5-7B into Qwen2.5-0.5B on one 8 GB GPU: teacher-written corpus, cached logits, LoRA distillation, 4-bit quantization, with MMLU and GSM8K measured for every model | PyTorch, Transformers, PEFT |
| [unified-xai-audio-xray](https://github.com/samichellia90-bit/unified-xai-audio-xray) | Explainable AI on chest X-rays and audio: a classifier at 0.934 test accuracy (AUC 0.987) and a faithfulness benchmark of Grad-CAM, LIME, SHAP and occlusion against random references | PyTorch, Streamlit, Docker |
| [spatio-temporal-deepfake-detection](https://github.com/samichellia90-bit/spatio-temporal-deepfake-detection) | Deepfake video detection trained on FaceForensics++: AUC 0.960 in-domain, 0.741 on the unseen Celeb-DF v2, and a robustness study over 16 perturbations | PyTorch, timm |
| [gp-active-learning-higgs](https://github.com/samichellia90-bit/gp-active-learning-higgs) | Genetic programming on ATLAS Higgs data: 1.6 % of the labels match full-data training, and uncertainty sampling loses to random sampling in 9 seeds out of 10 | NumPy, DEAP, scikit-learn |
| [bal-spark-incremental-pipeline](https://github.com/samichellia90-bit/bal-spark-incremental-pipeline) | Incremental storage of 26 million French addresses with reversible daily diffs and as-of reconstruction | Java, Spark SQL, Hive |
| [transconnect-logistics-manager](https://github.com/samichellia90-bit/transconnect-logistics-manager) | Logistics console application with Dijkstra shortest paths and a generic organisation tree | C#, .NET 8 |
| [word-search-game-csharp](https://github.com/samichellia90-bit/word-search-game-csharp) | Multiplayer word-search game with grid generation and dictionary binary search | C#, .NET 8 |

## Skills

- **Machine learning:** PyTorch, Hugging Face Transformers, knowledge distillation, quantization, computer vision, explainable AI
- **Data engineering:** Apache Spark, SQL, Hive, Parquet
- **Languages:** Python, Java, C#, SQL
- **Tools:** Git, Docker, GitHub Actions
