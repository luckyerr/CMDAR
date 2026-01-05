# CMDAR: A Chinese Multi-scene Dynamic Audio Reasoning Benchmark with Diverse Challenges

</div>

<div align="center">
<p align="center">
    📖<a href="https://arxiv.org/abs/2509.22461">Paper</a> |
  🤗<a href="https://huggingface.co/datasets/LLLLuckyer/CMDAR">CMDAR Benchmark</a> |
</p>
</div>


## 🎯Overview
We introduce **CMDAR**, a chinese benchmark for evaluating models on complex, multi-scene, and dynamically evolving audio reasoning tasks. CMDAR comprises 3,000 carefully curated question–answer pairs linked to diverse audio clips, covering five categories of complex reasoning and spanning three question types. We benchmark 26 state-of-the-art audio language models on CMDAR and observe that they exhibit limitations in complex reasoning tasks. In CMDAR-main, Qwen2.5-Omni (open-source) achieves 76.67\% accuracy, whereas GPT-4o Audio (closed-source) reaches 68.47\%. However, GPT-4o Audio substantially outperforms Qwen2.5-Omni on the more challenging multiple-choice with multiple audios and open-ended tasks. And we provide detail analysis corresponding suggestions for the future development of large audio language models (LALMs).
| | Mixed audio | Multiple audio | Open ended | Multi-scene within One audio | Chinese | Instruct following |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| AudioBench | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ |
| AIR-Bench | ❌ | ❌ | ✅ | ❌ | ❌ | ❌ |
| MMAU | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| MMAU-pro | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ |
| MMAR | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ |
| **CMDAR(Ours)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |

## 🏁 Evaluation

## 🤖 Leaderboard




## To-Do List
- [x] Release the CMDAR paper.
- [x] Release the Benchmark and Code of Evalution.
- [x] Release the Source Audios.
- [x] Release the Complete README.

## 📜 Citation
```
@article{li2025mdar,
  title={MDAR: A Multi-scene Dynamic Audio Reasoning Benchmark},
  author={Li, Hui and Jiang, Changhao and Wang, Hongyu and Zhang, Ming and Sun, Jiajun and Yang, Zhixiong and Cao, Yifei and Dou, Shihan and Fan, Xiaoran and Fan, Baoyu and others},
  journal={arXiv preprint arXiv:2509.22461},
  year={2025}
}

