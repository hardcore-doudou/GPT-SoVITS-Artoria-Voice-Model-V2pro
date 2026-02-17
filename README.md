# Artoria Pendragon (Fate/Stay Night) - GPT-SoVITS Voice Model

## 📝 项目介绍 / Introduction
这是一个基于 **GPT-SoVITS-v2Pro** 训练的《Fate》系列阿尔托莉雅·潘德拉贡（Artoria Pendragon / Saber）AI 语音模型。
模型致力于还原川澄绫子（Ayako Kawasumi）的经典声线，适用于二创配音或个人娱乐。

This is an AI voice model of Artoria Pendragon (Saber) from the *Fate* series, trained using **GPT-SoVITS-v2Pro**.
The model aims to replicate the voice of Ayako Kawasumi.

## 📦 模型信息 / Model Info
- **底模版本 / Base Model**: GPT-SoVITS v2Pro
- **训练数据 / Dataset**: 约 [XX] 分钟高质量干声 (From Fate/Stay Night [Realta Nua] / Anime)
- **训练轮数 / Epochs**: GPT [XX] / SoVITS [XX] (Recommended)

## 📂 文件说明 / Files
- `Artoria_SoVITS.pth`: SoVITS 权重文件，负责音色还原 (Timbre/Tone)。
- `Artoria_GPT.ckpt`: GPT 权重文件，负责语气和韵律 (Prosody/Rhythm)。
- `inference_ref.wav`: 推荐使用的参考音频（Excalibur!）。

## 🚀 使用方法 / Usage
1. 下载本项目的所有模型文件。
2. 将 `.pth` 文件放入 GPT-SoVITS 的 `SoVITS_weights_v2` (或 `SoVITS_weights_v2Pro`) 文件夹。
3. 将 `.ckpt` 文件放入 `GPT_weights_v2` (或 `GPT_weights_v2Pro`) 文件夹。
4. 启动 WebUI，在推理页面加载对应模型即可。
   - **参考音频建议**: 推荐使用时长 3-10秒 的清晰语音作为 Reference Audio。

## ⚠️ 免责声明 / Disclaimer
本模型仅供学习交流使用，严禁用于任何商业用途或非法传播。请尊重角色原配音演员（川澄绫子）及 TYPE-MOON 版权方利益。
This model is for educational and research purposes only. Commercial use is strictly prohibited. Please respect the rights of the voice actor (Ayako Kawasumi) and TYPE-MOON.
