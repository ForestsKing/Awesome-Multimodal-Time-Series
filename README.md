<div align="center">

# Awesome Multimodal Time Series Analysis

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
![Visits Badge](https://badges.pufler.dev/visits/ForestsKing/Awesome-Multimodal-Time-Series)
![Stars](https://img.shields.io/github/stars/ForestsKing/Awesome-Multimodal-Time-Series)
![Forks](https://img.shields.io/github/forks/ForestsKing/Awesome-Multimodal-Time-Series)

</div>

A curated list of paper, code, data, and other resources focus on multimodal time series analysis.

🚀 This repo will be continuously updated. <br>
⭐️ Please Star it if you find it helpful! <br>
🤝 Feel free to submit a PR or open an issue with suggestions or improvements. <br>

---

## Table of Contents

- [Time Series Forecasting](#Time-Series-Forecasting)
- [Time Series Reasoning](#Time-Series-Reasoning)
- [Time Series Captioning](#Time-Series-Captioning)
- [Time Series Generation](#Time-Series-Generation)
- [Time Series Alignment](#Time-Series-Alignment)

---

## Time Series Forecasting

| Title                                                                                                                                              |  Venue  |  Month  |                                                                      Code                                                                      |
|:---------------------------------------------------------------------------------------------------------------------------------------------------|:-------:|:-------:|:----------------------------------------------------------------------------------------------------------------------------------------------:|
| [Does Multimodality Lead to Better Time Series Forecasting?](https://arxiv.org/abs/2506.21611)                                                     |  arXiv  | 2025.06 |                                                                      None                                                                      |
| [FinMultiTime: A Bilingual Multimodal Financial Time-Series Dataset](https://arxiv.org/abs/2506.05019)                                             |  arXiv  | 2025.06 | [HuggingFace](https://huggingface.co/datasets/Wenyan0110/Multimodal-Dataset-Image_Text_Table_TimeSeries-for-Financial-Time-Series-Forecasting) |
| [ChronoSteer: Bridging Large Language Model and Time Series Foundation Model via Synthetic Data](https://arxiv.org/abs/2505.10083)                 |  arXiv  | 2025.05 |                                                                      None                                                                      |
| [Dual-Forecaster: A Multimodal Time Series Model Integrating Descriptive and Predictive Texts](https://arxiv.org/abs/2505.01135)                   |  arXiv  | 2025.05 |                                                                      None                                                                      |
| [Multimodal Conditioned Diffusive Time Series Forecasting](https://arxiv.org/abs/2504.19669)                                                       |  arXiv  | 2025.04 |                                                   [Github](https://github.com/synlp/MCD-TSF)                                                   |
| [Exploring the Effectiveness and Interpretability of Texts in LLM-based Time Series Models](https://arxiv.org/abs/2504.08808)                      |  arXiv  | 2025.04 |                                               [Github](https://github.com/zachysun/TS-Lang-Exp)                                                |
| [Explainable Multi-modal Time Series Prediction with LLM-in-the-Loop](https://arxiv.org/abs/2503.01013)                                            |  arXiv  | 2025.03 |                                                                      None                                                                      |
| [Evaluating System 1 vs. 2 Reasoning Approaches for Zero-Shot Time-Series Forecasting: A Benchmark and Insights](https://arxiv.org/abs/2503.01895) |  arXiv  | 2025.02 |                                                [Github](https://github.com/AdityaLab/OpenTimeR)                                                |
| [TimeCAP: Learning to Contextualize, Augment, and Predict Time Series Events with Large Language Model Agents](https://arxiv.org/abs/2502.11418)   |  AAAI   | 2025.02 |                                                                      None                                                                      |
| [Language in the Flow of Time: Time-Series-Paired Texts Weaved into a Unified Temporal Narrative](https://arxiv.org/abs/2502.08942)                |  arXiv  | 2025.02 |                                                                      None                                                                      |
| [ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data](https://arxiv.org/abs/2412.11376)                |  AAAI   | 2024.12 |                                               [Github](https://github.com/ForestsKing/ChatTime)                                                |
| [Multi-Modal Forecaster: Jointly Predicting Time Series and Textual Data](https://arxiv.org/abs/2411.06735)                                        |  arXiv  | 2024.11 |                                        [Github](https://github.com/Rose-STL-Lab/Multimodal_Forecasting)                                        |
| [Context is Key: A Benchmark for Forecasting with Essential Textual Information](https://arxiv.org/abs/2410.18959)                                 |  arXiv  | 2024.10 |                                       [Github](https://github.com/ServiceNow/context-is-key-forecasting)                                       |
| [From News to Forecast: Integrating Event Analysis in LLM-Based Time Series Forecasting with Reflection](https://arxiv.org/abs/2409.17515)         | NeurIPS | 2024.09 |                                       [Github](https://github.com/ameliawong1996/From_News_to_Forecast)                                        |
| [Time-MMD: Multi-Domain Multimodal Dataset for Time Series Analysis](https://arxiv.org/abs/2406.08627)                                             | NeurIPS | 2024.06 |                                                [Github](https://github.com/AdityaLab/Time-MMD)                                                 |
| [Beyond Trend and Periodicity: Guiding Time Series Forecasting with Textual Cues](https://arxiv.org/abs/2405.13522)                                |  arXiv  | 2024.05 |                                                   [Github](https://github.com/vewoxic/tgtsf)                                                   |
| [Language Models Still Struggle to Zero-shot Reason about Time Series](https://arxiv.org/abs/2404.11757)                                           |  arXiv  | 2024.04 |                                           [Github](https://github.com/behavioral-data/TSandLanguage)                                           |
| [Towards Explainable Traffic Flow Prediction with Large Language Models](https://arxiv.org/abs/2404.02937)                                         |  arXiv  | 2024.04 |                                                   [Github](https://github.com/guoxs/xtp-llm)                                                   |
| [GPT4MTS: Prompt-Based Large Language Model for Multimodal Time-Series Forecasting](https://ojs.aaai.org/index.php/AAAI/article/view/30383)        |  AAAI   | 2024.03 |          [Github](https://github.com/Flora-jia-jfr/GPT4MTS-Prompt-based-Large-Language-Model-for-Multimodal-Time-series-Forecasting)           |

## Time Series Reasoning

| Title                                                                                                                                             | Venue |  Month  |                                  Code                                   |
|:--------------------------------------------------------------------------------------------------------------------------------------------------|:-----:|:-------:|:-----------------------------------------------------------------------:|
| [ITFormer: Bridging Time Series and Natural Language for Multi-Modal QA with Large-Scale Multitask Dataset](https://arxiv.org/abs/2506.20093)     | arXiv | 2025.06 |          [Github](https://pandalin98.github.io/itformer_site)           |
| [MTBench: A Multimodal Time Series Benchmark for Temporal Reasoning and Question Answering](https://arxiv.org/abs/2503.16858)                     | arXiv | 2025.03 |    [Github](https://github.com/Graph-and-Geometric-Learning/MTBench)    |
| [Chat-TS: Enhancing Multi-Modal Reasoning Over Time-Series and Natural Language Data](https://arxiv.org/abs/2503.10883)                           | arXiv | 2025.03 |                                  None                                   |
| [Time-MQA: Time Series Multi-Task Question Answering with Context Enhancement](https://www.arxiv.org/abs/2503.01875)                              | arXiv | 2025.02 |              [HuggingFace](https://huggingface.co/Time-QA)              |
| [Position: Empowering Time Series Reasoning with Multimodal LLMs](https://arxiv.org/abs/2502.01477)                                               | arXiv | 2025.02 |                                  None                                   |
| [ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data](https://arxiv.org/abs/2412.11376)               | AAAI  | 2024.12 |            [Github](https://github.com/ForestsKing/ChatTime)            |
| [ChatTS: Aligning Time Series with LLMs via Synthetic Data for Enhanced Understanding and Reasoning](https://arxiv.org/abs/2412.03104)            | arXiv | 2024.12 |             [Github](https://github.com/NetManAIOps/ChatTS)             |
| [A Picture is Worth A Thousand Numbers: Enabling LLMs Reason about Time Series via Visualization](https://arxiv.org/abs/2411.06018)               | arXiv | 2024.11 |           [Github](https://github.com/haoxin1998/TimberBed-1)           |
| [TimeSeriesExam: A Time Series Understanding Exam](https://arxiv.org/abs/2410.14752)                                                              | arXiv | 2024.10 | [HuggingFace](https://huggingface.co/datasets/AutonLab/TimeSeriesExam1) |
| [Can LLMs Understand Time Series Anomalies?](https://arxiv.org/abs/2410.05440)                                                                    | ICLR  | 2024.10 |           [Github](https://github.com/Rose-STL-Lab/AnomLLM/)            |
| [Beyond Forecasting: Compositional Time Series Reasoning for End-to-End Task Execution](https://arxiv.org/abs/2410.04047)                         | arXiv | 2024.10 |                                  None                                   |
| [Towards Time Series Reasoning with LLMs](https://arxiv.org/abs/2409.11376)                                                                       | arXiv | 2024.09 |                                  None                                   |
| [Evaluating Large Language Models on Time Series Feature Understanding: A Comprehensive Taxonomy and Benchmark](https://arxiv.org/abs/2404.16563) | arXiv | 2024.04 |                                  None                                   |
| [Language Models Still Struggle to Zero-shot Reason about Time Series](https://arxiv.org/abs/2404.11757)                                          | arXiv | 2024.04 |       [Github](https://github.com/behavioral-data/TSandLanguage)        |

## Time Series Captioning

| Title                                                                                                                   | Venue |  Month  | Code |
|:------------------------------------------------------------------------------------------------------------------------|:-----:|:-------:|:----:|
| [Time Series Language Model for Descriptive Caption Generation](https://www.arxiv.org/abs/2501.01832)                   | arXiv | 2025.01 | None |
| [TADACap: Time-series Adaptive Domain-Aware Captioning](https://arxiv.org/abs/2504.11441)                               | ICAIF | 2024.12 | None |
| [Decoding Time Series with LLMs: A Multi-Agent Framework for Cross-Domain Annotation](https://arxiv.org/abs/2410.17462) | arXiv | 2024.10 | None |
| [Towards Time Series Reasoning with LLMs](https://arxiv.org/abs/2409.11376)                                             | arXiv | 2024.09 | None |

## Time Series Generation

| Title                                                                                                                | Venue |  Month  |                    Code                    |
|:---------------------------------------------------------------------------------------------------------------------|:-----:|:-------:|:------------------------------------------:|
| [T2S: High-resolution Time Series Generation with Text-to-Series Diffusion Models](https://arxiv.org/abs/2505.02417) | IJCAI | 2025.05 | [Github](https://github.com/WinfredGe/T2S) |

## Time Series Alignment

| Title                                                                                                                  | Venue |  Month  | Code |
|:-----------------------------------------------------------------------------------------------------------------------|:-----:|:-------:|:----:|
| [CLaSP: Learning Concepts for Time-Series Signals from Natural Language Supervision](https://arxiv.org/abs/2411.08397) | arXiv | 2024.11 | None |