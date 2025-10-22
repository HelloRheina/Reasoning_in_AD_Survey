<!--Title-->
# 🚗Embodied Reasoning in Autonomous Driving Systems: Open Challenges and Emerging Paradigms
<p align="center">
    <img src="./Asset/Images/logo_1.png" width="100%" height="100%">
</p>
<!--This project links-->

## Our AD Reasoning Work

🔥🔥🔥 **Embodied Reasoning in Autonomous Driving Systems: Open Challenges and Emerging Paradigms**  
**[Project Page [This Page]](https://github.com/IIGROUP/Reasoning_in_AD_Survey)** | **[Paper](https://github.com/IIGROUP/Reasoning_in_AD_Survey)** | :black_nib: **[BiBTeX Citation]()** | **[💬 WeChat (AD Reasoning WeChat Group Discussion)]()**

:sparkles:  A comprehensive survey for autonomous driving systems :sparkles:  

---

<!--For future related works-->
<!--
🔥🔥🔥 **VITA: Towards Open-Source Interactive Omni Multimodal LLM**  
<p align="center">
    <img src="./images/vita-1.5.jpg" width="60%" height="60%">
</p>

<font size=7><div align='center' > [[📽 VITA-1.5 Demo Show! Here We Go! 🔥](https://youtu.be/tyi6SVFT5mM?si=fkMQCrwa5fVnmEe7)] </div></font>  

<font size=7><div align='center' > [[📖 VITA-1.5 Paper](https://arxiv.org/pdf/2501.01957)] [[🌟 GitHub](https://github.com/VITA-MLLM/VITA)] [[🤖 Basic Demo](https://modelscope.cn/studios/modelscope/VITA1.5_demo)] [[🍎 VITA-1.0](https://vita-home.github.io/)] [[💬 WeChat (微信)](https://github.com/VITA-MLLM/VITA/blob/main/asset/wechat-group.jpg)]</div></font>  

<font size=7><div align='center' > We are excited to introduce the **VITA-1.5**, a more powerful and more real-time version. ✨ </div></font>

<font size=7><div align='center' >**All codes of VITA-1.5 have been released**! :star2: </div></font>  

You can experience our [Basic Demo](https://modelscope.cn/studios/modelscope/VITA1.5_demo) on ModelScope directly. The Real-Time Interactive Demo needs to be configured according to the [instructions](https://github.com/VITA-MLLM/VITA?tab=readme-ov-file#-real-time-interactive-demo).
-->



<!--Table of Contents-->

<font size=5><center><b> 📕 Table of Contents </b> </center></font>
- [System-Centric Approaches](#system-centric-approaches)
- [Evaluation-Centric Practices](#evaluation-centric-practices)
  - [Evaluating Foundational Cognitive Abilities](#evaluating-foundational-cognitive-abilities)
    - [Spatial Comprehension and Scene Understanding](#spatial-comprehension-and-scene-understanding)
    - [Causal and Logical Reasoning](#causal-and-logical-reasoning)
    - [Social Comprehension and Rationale Generation](#social-comprehension-and-rationale-generation)
  - [Evaluating System-Level and Interactive Performance](#evaluating-system-level-and-interactive-performance)
    - [Closed-Loop System Validation](#closed-loop-system-validation)
    - [Interactive and Critical Scenarios](#interactive-and-critical-scenarios)
  - [Evaluating Robustness and Trustworthiness](#evaluating-robustness-and-trustworthiness)
    - [Evaluating Generalization to the Long Tail](#evaluating-generalization-to-the-long-tail)
    - [Verifying System Trustworthiness and Safety](#verifying-system-trustworthiness-and-safety)
  - [Additional Supporting Datasets](#additional-supporting-datasets)
---

<!--References_System-Cetric Approaches-->
# System-centric-approaches


<!--References_Evaluation-Centric Practices-->

# Evaluation-centric-practices

## Evaluating Foundational Cognitive Abilities

### Spatial Comprehension and Scene Understanding
| Dataset | Time | Code | Data Source | Main Challenges | Driving Task Direction |
|:--------:|:----:|:----:|:-----------:|:---------------:|:---------------------:|
| [**NuScenes-QA**](https://arxiv.org/pdf/2305.14836.pdf) <br> ![Star](https://img.shields.io/github/stars/qiantianwen/NuScenes-QA.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/qiantianwen/NuScenes-QA) | nuScenes | C3, C4, C6 | Perception |
| [**NuScenes-MQA**](https://arxiv.org/pdf/2305.14836.pdf) <br> ![Star](https://img.shields.io/github/stars/turingmotors/NuScenes-MQA.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/turingmotors/NuScenes-MQA) | nuScenes | C3, C4, C6 | Perception |
| [**NuScenes-SpatialQA**](https://arxiv.org/pdf/2504.03164) <br> ![Star](https://img.shields.io/github/stars/taco-group/NuScenes-SpatialQA.svg?style=social&label=Star) | 2025 | [GitHub](https://github.com/taco-group/NuScenes-SpatialQA) | nuScenes | C3, C4, C5, C6 | Perception |
| [**SURDS-Bench**](https://arxiv.org/pdf/2504.03164) <br> ![Star](https://img.shields.io/github/stars/xiandaguo/drive-mllm.svg?style=social&label=Star) | 2025 | [GitHub](https://github.com/xiandaguo/drive-mllm) | - | C3, C4, C5, C6 | Perception |
| [**RoadTextVQA**](https://arxiv.org/pdf/2307.03948) <br> ![Star](https://img.shields.io/github/stars/georg3tom/RoadtextVQA.svg?style=social&label=Star) | 2023 | [GitHub](https://github.com/georg3tom/RoadtextVQA) | Multi-country | C3, C4, C6 | Perception |
| [**STSBench**](https://arxiv.org/pdf/2506.06218) <br> ![Star](https://img.shields.io/github/stars/LRP-IVC/STSBench.svg?style=social&label=Star) | 2025 | [GitHub](https://github.com/LRP-IVC/STSBench) | nuScenes | C3, C4, C5, C6, C7 | Perception & Decision-Making |
| [**DriveMLLM**](https://arxiv.org/pdf/2312.09245) <br> ![Star](https://img.shields.io/github/stars/xiandaguo/drive-mllm.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/xiandaguo/drive-mllm) | nuScenes | C3, C4, C5, C6 | Perception |
| [**NuPrompt**](https://arxiv.org/pdf/2309.04379) <br> ![Star](https://img.shields.io/github/stars/wudongming97/Prompt4Driving.svg?style=social&label=Star) | 2025 | [GitHub](https://github.com/wudongming97/Prompt4Driving) | nuScenes | C3, C4, C6 | Perception |

### Causal and Logical Reasoning
| Dataset | Time | Code | Data Source | Main Challenges | Driving Task Direction |
|:--------:|:----:|:----:|:-----------:|:---------------:|:---------------------:|
| [**DriveLM-Data**](https://arxiv.org/pdf/2312.14150) <br> ![Star](https://img.shields.io/github/stars/OpenDriveLab/DriveLM.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/OpenDriveLab/DriveLM) | nuScenes, CARLA | C3, C4, C5, C6, C7 | Perception & Decision-Making |
| [**DriveLM-Bench**](https://arxiv.org/pdf/2312.14150) <br> ![Star](https://img.shields.io/github/stars/OpenDriveLab/DriveLM.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/OpenDriveLab/DriveLM) | nuScenes, CARLA | C3, C4, C5, C6, C7 | Perception/Prediction/Planning/Decision-making |
| [**Reason2Drive**](https://arxiv.org/pdf/2312.14150) <br> ![Star](https://img.shields.io/github/stars/fudan-zvg/reason2drive.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/fudan-zvg/reason2drive) | nuScenes, Waymo, ONCE | C3, C4, C5, C6 | Perception/Prediction/Inference |
| [**WOMD-Reasoning**](https://arxiv.org/pdf/2312.14150) <br> ![Star](https://img.shields.io/github/stars/yhli123/WOMD-Reasoning.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/yhli123/WOMD-Reasoning) | Waymo Open Motion | C3, C4, C5, C7 | Prediction |
| [**DrivingVQA**](https://arxiv.org/pdf/2501.04671v1) <br> ![Star](https://img.shields.io/github/stars/vita-epfl/DrivingVQA.svg?style=social&label=Star) | 2025 | [GitHub](https://github.com/vita-epfl/DrivingVQA) | Driving Theory Exams | C3, C4, C6 | Perception |
| [**OmniDrive**](https://arxiv.org/pdf/2312.14150) <br> ![Star](https://img.shields.io/github/stars/NVlabs/OmniDrive.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/NVlabs/OmniDrive) | nuScenes | C3, C4, C5, C6, C7 | Perception & Decision-Making |
| [**Rank2Tell**](https://arxiv.org/pdf/2312.14150) <br> - | 2023 | - | - | C3, C4, C5, C6, C7 | Perception & Decision-Making |
| [**DriveLMM-o1**](https://arxiv.org/pdf/2503.10621) <br> ![Star](https://img.shields.io/github/stars/ayesha-ishaq/DriveLMM-o1.svg?style=social&label=Star) | 2025 | [GitHub](https://github.com/ayesha-ishaq/DriveLMM-o1) | NuScenes | C3, C4, C5, C6, C7 | Perception & Decision-Making |

### Social Comprehension and Rationale Generation
| Dataset | Time | Code | Data Source | Main Challenges | Driving Task Direction |
|:--------:|:----:|:----:|:-----------:|:---------------:|:---------------------:|
| [**LingoQA**](https://arxiv.org/abs/2312.14115) <br> ![Star](https://img.shields.io/github/stars/wayveai/LingoQA.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/wayveai/LingoQA) | Wayve Team | C4, C5, C6, C7 | Perception & Decision-Making |
| [**LaMPilot-Bench**](https://arxiv.org/abs/2312.04372) <br> ![Star](https://img.shields.io/github/stars/PurdueDigitalTwin/LaMPilot.svg?style=social&label=Star) | 2024 | [Github](https://github.com/PurdueDigitalTwin/LaMPilot) | Simulation + Measured | C3, C5, C6, C7 | Planning & Decision-Making |
| [**DriveAction**](https://arxiv.org/html/2506.05667v1) <br> - | 2025 | [HuggingFace](https://huggingface.co/datasets/LiAuto-DriveAction/drive-action) | Self-collected | C3, C4, C5, C7 | Planning & Decision-Making |

## Evaluating System-Level and Interactive Performance

### Closed-Loop System Validation
| Dataset | Time | Code | Data Source | Main Challenges | Driving Task Direction |
|:--------:|:----:|:----:|:-----------:|:---------------:|:---------------------:|
| [**DriveMLM**](https://arxiv.org/pdf/2312.14150) <br> ![Star](https://img.shields.io/github/stars/xiandaguo/drive-mllm.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/xiandaguo/drive-mllm) | - | C3, C4, C5, C6 | Perception & Decision-Making |
| [**CarLLaVA**]() <br> ![Star](https://img.shields.io/github/stars/RenzKa/simlingo.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/RenzKa/simlingo) | CARLA | C2, C4, C5 | End-to-End Driving |
| [**VLM-AD**](https://arxiv.org/pdf/2412.14446) <br> - | 2024 | - | nuScenes | C2, C3, C5, C6 | Planning & Decision-Making / End-to-End |

### Interactive and Critical Scenarios
| Dataset | Time | Code | Data Source | Main Challenges | Driving Task Direction |
|:--------:|:----:|:----:|:-----------:|:---------------:|:---------------------:|
| [**DriveArena**](https://arxiv.org/abs/2408.00415) <br> ![Star](https://img.shields.io/github/stars/PJLab-ADG/DriveArena.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/PJLab-ADG/DriveArena) | World Map + Generation | C3, C4, C5, C6 | Planning & Decision-Making |
| [**Bench2ADVLM**](https://bench2advlm.github.io/) <br> - | 2025 | [GitHub](https://anonymous.4open.science/r/BENCH2ADVLM-C0EF/README.md) | - | C1, C2, C3, C4, C5 | Planning & Decision-Making |
| [**DriveDreamer-2**](https://arxiv.org/pdf/2403.06845) <br> ![Star](https://img.shields.io/github/stars/f1yfisher/DriveDreamer2.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/f1yfisher/DriveDreamer2) | nuScenes | C2, C3, C6 | Planning & Decision-Making |

## Evaluating Robustness and Trustworthiness

### Evaluating Generalization to the Long Tail
| Dataset | Time | Code | Data Source | Main Challenges | Driving Task Direction |
|:--------:|:----:|:----:|:-----------:|:---------------:|:---------------------:|
| [**DrivingDojo**](https://arxiv.org/pdf/2312.14150) <br> ![Star](https://img.shields.io/github/stars/Robertwyq/Drivingdojo.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/Robertwyq/Drivingdojo) | Large-scale real videos | C3, C4, C5, C7 | Planning & Decision-Making |
| [**CODA-LM**](https://arxiv.org/pdf/2404.10595) <br> ![Star](https://img.shields.io/github/stars/DLUT-LYZ/CODA-LM.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/DLUT-LYZ/CODA-LM) | CODA | C3, C4, C5 | Perception & Decision-Making |
| [**VLM-C4L**](https://arxiv.org/abs/2503.23046) <br> - | 2025 | - | Waymo/CODA | C1, C3, C4, C5 | Planning & Decision-Making |
| [**DriveDiTFit**](https://arxiv.org/abs/2407.15661) <br> ![Star](https://img.shields.io/github/stars/TtuHamg/DriveDiTFit.svg?style=social&label=Star) | 2025 | [GitHub](https://github.com/TtuHamg/DriveDiTFit) | Multi-dataset | C2, C3, C4 | Data Generation |
| [**VLMine**](https://arxiv.org/abs/2409.15486) <br> - | 2025 | - | Waymo Open | C3, C6 | Data Mining |

### Verifying System Trustworthiness and Safety
| Dataset | Time | Code | Data Source | Main Challenges | Driving Task Direction |
|:--------:|:----:|:----:|:-----------:|:---------------:|:---------------------:|
| [**AutoTrust**](https://arxiv.org/abs/2412.15206) <br> ![Star](https://img.shields.io/github/stars/taco-group/AutoTrust.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/taco-group/AutoTrust) | - | C1, C4, C5, C6, C7 | Trust Assessment |
| [**DriveBench**](https://arxiv.org/pdf/2312.14150) <br> ![Star](https://img.shields.io/github/stars/drive-bench/toolkit.svg?style=social&label=Star) | 2025 | [GitHub](https://github.com/drive-bench/toolkit) | Multi-source | C1, C3, C4, C5, C6 | Perception+Prediction+Planning+Explanation |
| [**BDD-X**]() <br> ![Star](https://img.shields.io/github/stars/JinkyuKimUCB/BDD-X.svg?style=social&label=Star) | 2024 | [GitHub](https://github.com/JinkyuKimUCB/BDD-X-dataset) | Berkeley Deep Drive | C3, C4, C5, C6 | End-to-End Driving |

## Additional Supporting Datasets

| Dataset | Time | Code | Data Source | Main Challenges | Driving Task Direction |
|:--------:|:----:|:----:|:-----------:|:---------------:|:---------------------:|
| [**DRAMA**]() <br> ![Star](https://img.shields.io/github/stars/drama2022/DRAMA.svg?style=social&label=Star) | 2022 | [GitHub](https://github.com/drama2022/DRAMA) | - | C3, C4, C5, C7 | Perception & Decision-Making |
| [**Talk2Car**]() <br> ![Star](https://img.shields.io/github/stars/talk2car/Talk2Car.svg?style=social&label=Star) | 2019 | [GitHub](https://github.com/talk2car/Talk2Car) | nuScenes | C3, C4, C6, C7 | Perception |
| [**Refer-KITTI**]() <br> ![Star](https://img.shields.io/github/stars/referkitti2023/Refer-KITTI.svg?style=social&label=Star) | 2023 | [GitHub](https://github.com/referkitti2023/Refer-KITTI) | KITTI | C3, C4, C6 | Perception |