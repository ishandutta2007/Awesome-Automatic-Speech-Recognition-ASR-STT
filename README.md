# Awesome Automatic Speech Recognition (ASR / STT) 🎙️ 📝

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Automatic Speech Recognition ASR STT Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Automatic-Speech-Recognition-ASR-STT"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Automatic-Speech-Recognition-ASR-STT?style=social" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Automatic-Speech-Recognition-ASR-STT/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Automatic-Speech-Recognition-ASR-STT?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Automatic-Speech-Recognition-ASR-STT/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Automatic-Speech-Recognition-ASR-STT?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Automatic Speech Recognition (ASR / STT) Ecosystem 🎙️

**Curated Directory of Speech-to-Text APIs, Real-Time ASR Engines, Multilingual Audio Models, & Open-Source Speech Recognition Frameworks** ⚡

*Focused on Real-Time Streaming Transcription, High-Accuracy Multilingual Recognition, Speaker Diarization, On-Device Edge Inference, & Self-Hosted Speech Pipelines.* 🚀

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary 🔍

Welcome to the definitive curated index of **automatic speech recognition (ASR) software**, **speech-to-text (STT) cloud APIs**, and **open-source speech recognition models**. Modern voice intelligence relies on enterprise cloud services (such as *Deepgram*, *AssemblyAI*, *Google Cloud Speech-to-Text*, *Azure AI Speech*, and *Speechmatics*) as well as state-of-the-art open-source engines (like *OpenAI Whisper*, *whisper.cpp*, *faster-whisper*, *Sherpa-ONNX*, *Vosk*, *Cohere Transcribe*, and *Qwen3-ASR*). This repository serves developers, AI researchers, and audio engineers looking for real-time transcription, offline dictation, low-latency streaming ASR, and multi-speaker diarization algorithms. 🌐

---

## 📑 Table of Contents 📜

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms-)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects-)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute-)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship-)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer-)

---

## 🏢 SaaS / Commercial Platforms 💼

> [!NOTE]
> **Market Size & Industry Structure:** The global Automatic Speech Recognition (ASR) and Speech-to-Text market size is estimated at **$15.4 Billion in 2026** and projected to reach **$38.2 Billion by 2030**, growing at a CAGR of ~25.5%. The sector is **moderately fragmented**: cloud hyperscalers (Microsoft Azure, AWS, Google Cloud) dominate foundational cloud distribution, while specialized voice AI pioneers (Deepgram, AssemblyAI, Speechmatics) command premium developer mindshare through hyper-optimized streaming latency, domain-specific accuracy, and lower word error rates (WER). 📈

Below is the comparison of top commercial speech recognition API providers, sorted by company valuation/market cap in descending order: 📊

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap 💰 | Standard Edition Starting Price 🏷️ | Free Tier / Free Trial Limits 🎁 | Description 📝 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure AI Speech](https://azure.microsoft.com/en-us/products/ai-services/speech-to-text)** 🔷 | Microsoft | ~$3.90 Trillion | $0.0167/minute (standard); $0.024/minute (enhanced) | **Free tier:** 5 hours of audio/month | **Microsoft's cloud speech service** — Real-time streaming and batch transcription. Custom speech models, pronunciation assessment, and multi-speaker diarization. ☁️ |
| **[Amazon Transcribe](https://aws.amazon.com/transcribe/)** ☁️ | Amazon | ~$2.00 Trillion | $0.024/minute (first 250K min/month) | **Free tier:** 60 minutes/month for 12 months | **AWS-native speech-to-text** — Streaming and batch ASR. Custom vocabulary, speaker identification, and medical transcription. Integrates with AWS S3 & Lambda. 📦 |
| **[Google Cloud Speech-to-Text](https://cloud.google.com/speech-to-text)** 🌐 | Google (Alphabet) | ~$2.00 Trillion | $0.016/minute (standard); $0.024/minute (enhanced) | **Free tier:** 60 minutes of audio/month | **Google's speech recognition** — Powered by Chirp models for 125+ languages. Real-time streaming, speaker diarization, and automatic punctuation. 🎯 |
| **[Whisper Cloud (OpenAI)](https://platform.openai.com/docs/guides/speech-to-text)** 🔵 | OpenAI | ~$80.00 Billion | $0.006/minute (pay-as-you-go) | **Free trial:** $5 free API trial credits for new accounts (expires in 3 months) | **OpenAI's hosted Whisper API** — Multilingual speech recognition, translation, and language identification. Supports 99 languages with zero infra overhead. 🤖 |
| **[Deepgram](https://deepgram.com/)** 🟢 | Deepgram | ~$1.20 Billion | $0.0043/minute (Nova-3 model, pay-as-you-go) | **Free trial:** $200 free API credits for new signups | **Real-time ASR with Nova-3** — Ultra-low latency streaming transcription with keyterm prompting, speaker diarization, and smart formatting. ⚡ |
| **[AssemblyAI](https://www.assemblyai.com/)** 🟣 | AssemblyAI | ~$300.00 Million | $0.15/hour ($0.0025/minute, Universal-2) | **Free tier / trial:** $50 free API credits upon signup | **Developer-first speech AI** — Universal-3.5 Pro models with ~30% lower hallucinations than Whisper. Real-time streaming and entity detection. 🧠 |
| **[Rev AI](https://www.rev.com/api)** 📝 | Rev.com | ~$250.00 Million | $0.02/minute (automated machine transcription) | **Free trial:** 300 minutes (5 hours) free machine transcription | **Hybrid machine + human transcription** — High-accuracy machine ASR with optional human transcription fallbacks. Custom vocabulary and diarization. ✍️ |
| **[Sonix](https://sonix.ai/)** 🎬 | Sonix | ~$50.00 Million | $10.00/hour (standard pay-as-you-go) | **Free trial:** 30 minutes of free automated transcription | **Automated transcription platform** — Web editor for 40+ languages, speaker labeling, automated subtitles, and translation API. 🎧 |
| **[Gladia](https://www.gladia.io/)** 🎧 | Gladia | ~$30.00 Million | $0.00016/second ($0.0096/minute) | **Free tier:** 10 hours of audio transcription/month | **Real-time audio intelligence API** — Multilingual STT with real-time streaming, speaker diarization, and live sentiment extraction. ⚡ |
| **[Speechmatics](https://www.speechmatics.com/)** 🎯 | Speechmatics | ~$25.00 Million | $0.005/minute ($0.30/hour, standard batch) | **Free tier / trial:** 4 hours of free audio transcription/month | **Enterprise ASR with global coverage** — Autonomous speech recognition supporting 50+ languages with high accuracy in noisy environments. 🔊 |

---

## 🔓 Open-Source GitHub Projects 🌾

*Sorted by GitHub Stars Count (Descending)* 🌟

- **[OpenAI Whisper](https://github.com/openai/whisper)** [![Stars](https://img.shields.io/github/stars/openai/whisper?style=social&color=white)](https://github.com/openai/whisper/stargazers)  
  **The foundational open-source ASR model**, MIT licensed. Transformer sequence-to-sequence model trained on 680,000 hours of multilingual data. Six model sizes: tiny (39M), base (74M), small (244M), medium (769M), large (1550M), and turbo (809M). Supports 99 languages, speech translation, and language identification. Runs on CPU and GPU. 🌍

- **[whisper.cpp](https://github.com/ggerganov/whisper.cpp)** [![Stars](https://img.shields.io/github/stars/ggerganov/whisper.cpp?style=social&color=white)](https://github.com/ggerganov/whisper.cpp/stargazers)  
  **High-performance C/C++ port of Whisper**, MIT licensed. CPU inference with minimal dependencies. Runs on edge devices, Raspberry Pi, Apple Silicon, and mobile devices. Quantization support (int4/int8) for minimal memory usage. ⚡

- **[faster-whisper](https://github.com/SYSTRAN/faster-whisper)** [![Stars](https://img.shields.io/github/stars/SYSTRAN/faster-whisper?style=social&color=white)](https://github.com/SYSTRAN/faster-whisper/stargazers)  
  **Faster Whisper reimplementation using CTranslate2**, MIT licensed. Up to 4x faster than original OpenAI Whisper with 50% less memory usage. Supports 8-bit quantization on CPU and GPU while retaining full accuracy. 🏎️

- **[WhisperX](https://github.com/m-bain/whisperX)** [![Stars](https://img.shields.io/github/stars/m-bain/whisperX?style=social&color=white)](https://github.com/m-bain/whisperX/stargazers)  
  **Whisper with word-level timestamps and speaker diarization**, BSD-2-Clause licensed. Integrates pyannote-audio for fast speaker diarization and precise forced alignment for subtitles and video processing. 🗣️

- **[NVIDIA NeMo](https://github.com/NVIDIA/NeMo)** [![Stars](https://img.shields.io/github/stars/NVIDIA/NeMo?style=social&color=white)](https://github.com/NVIDIA/NeMo/stargazers)  
  **Enterprise conversational AI & ASR toolkit**, Apache-2.0 licensed. Features NVIDIA Parakeet and FastConformer models optimized for GPU training and TensorRT-LLM edge deployment. 🚀

- **[Vosk](https://github.com/alphacep/vosk-api)** [![Stars](https://img.shields.io/github/stars/alphacep/vosk-api?style=social&color=white)](https://github.com/alphacep/vosk-api/stargazers)  
  **Offline lightweight speech recognition toolkit**, Apache-2.0 licensed. Compact 50MB models for 20+ languages. Zero-latency streaming API running locally on Android, iOS, and Raspberry Pi. 🍓

- **[FunASR](https://github.com/alibaba-damo-academy/FunASR)** [![Stars](https://img.shields.io/github/stars/alibaba-damo-academy/FunASR?style=social&color=white)](https://github.com/alibaba-damo-academy/FunASR/stargazers)  
  **Industrial-grade ASR framework from Alibaba**, MIT licensed. Features Paraformer and SenseVoice models. 0.8B parameter models delivering performance of 12B speech foundation models across Asian languages. 🏭

- **[Buzz](https://github.com/chidiwilliams/buzz)** [![Stars](https://img.shields.io/github/stars/chidiwilliams/buzz?style=social&color=white)](https://github.com/chidiwilliams/buzz/stargazers)  
  **Cross-platform desktop speech-to-text app**, MIT licensed. Feature-rich GUI application powered by Whisper for transcribing and translating live microphone audio or audio files offline. 🐝

- **[Sherpa-ONNX](https://github.com/k2-fsa/sherpa-onnx)** [![Stars](https://img.shields.io/github/stars/k2-fsa/sherpa-onnx?style=social&color=white)](https://github.com/k2-fsa/sherpa-onnx/stargazers)  
  **Next-gen Kaldi speech engine with ONNX Runtime**, Apache-2.0 licensed. Ultra-fast CPU/GPU streaming ASR, TTS, VAD, and speaker diarization. Native bindings for 12 programming languages including Python, C++, Go, Rust, and Swift. 🎯

- **[SpeechBrain](https://github.com/speechbrain/speechbrain)** [![Stars](https://img.shields.io/github/stars/speechbrain/speechbrain?style=social&color=white)](https://github.com/speechbrain/speechbrain/stargazers)  
  **All-in-one PyTorch speech toolkit**, Apache-2.0 licensed. Flexible open-source library for ASR, speaker recognition, speech enhancement, multi-microphone processing, and end-to-end audio learning. 🔬

- **[Distil-Whisper](https://github.com/huggingface/distil-whisper)** [![Stars](https://img.shields.io/github/stars/huggingface/distil-whisper?style=social&color=white)](https://github.com/huggingface/distil-whisper/stargazers)  
  **Distilled lightweight Whisper variants from Hugging Face**, MIT licensed. 6x faster than OpenAI Whisper Large while maintaining 99% accuracy and reducing parameters by 49%. 💨

- **[MacWhisper](https://github.com/goodsnooze/macwhisper)** [![Stars](https://img.shields.io/github/stars/goodsnooze/macwhisper?style=social&color=white)](https://github.com/goodsnooze/macwhisper/stargazers)  
  **Native macOS desktop transcription tool**, Freemium / Open UI component. Drag-and-drop audio files for fast local Whisper transcription, speaker diarization, and export to SRT/VTT. 🍎

- **[WhisperLive](https://github.com/collabora/WhisperLive)** [![Stars](https://img.shields.io/github/stars/collabora/WhisperLive?style=social&color=white)](https://github.com/collabora/WhisperLive/stargazers)  
  **Real-time streaming Whisper server**, MIT licensed. WebSocket-based server architecture for low-latency live speech transcription. Integrates with OBS and browser audio stream pipelines. 📡

- **[whisper_streaming](https://github.com/ufal/whisper_streaming)** [![Stars](https://img.shields.io/github/stars/ufal/whisper_streaming?style=social&color=white)](https://github.com/ufal/whisper_streaming/stargazers)  
  **Real-time streaming implementation for Whisper**, MIT licensed. Uses LocalAgreement policy to perform low-latency chunk-based streaming transcription on endless microphone inputs. 🌊

- **[Qwen3-ASR](https://github.com/QwenLM/Qwen3-ASR)** [![Stars](https://img.shields.io/github/stars/QwenLM/Qwen3-ASR?style=social&color=white)](https://github.com/QwenLM/Qwen3-ASR/stargazers)  
  **Alibaba's multilingual speech foundation model**, Apache-2.0 licensed. Supports 52 languages and regional dialects. High accuracy with 0.6B & 1.7B variants backed by vLLM streaming inference. 🌏

- **[Speech Note (Linux)](https://github.com/mkiol/dsnote)** [![Stars](https://img.shields.io/github/stars/mkiol/dsnote?style=social&color=white)](https://github.com/mkiol/dsnote/stargazers)  
  **Linux desktop offline note-taking & speech app**, GPL-3.0 licensed. Supports multiple offline ASR engines (Whisper, Vosk, Coqui) for private voice dictation. 🐧

- **[Cohere Transcribe](https://github.com/cohere-ai/transcribe)** [![Stars](https://img.shields.io/github/stars/cohere-ai/transcribe?style=social&color=white)](https://github.com/cohere-ai/transcribe/stargazers)  
  **SOTA open-source ASR model**, Apache-2.0 licensed. Ranked #1 on HuggingFace Open ASR Leaderboard with 5.42% WER. 2B parameter Conformer architecture trained across 14 languages. 🏆

- **[VibeVoice-ASR](https://github.com/microsoft/VibeVoice)** [![Stars](https://img.shields.io/github/stars/microsoft/VibeVoice?style=social&color=white)](https://github.com/microsoft/VibeVoice/stargazers)  
  **Microsoft's long-form ASR model**, MIT licensed. Transcribes up to 60 minutes of uninterrupted audio in a single pass using a 64K token context window with built-in diarization. 📅

- **[YazSes](https://github.com/MSKazemi/yazses)** [![Stars](https://img.shields.io/github/stars/MSKazemi/yazses?style=social&color=white)](https://github.com/MSKazemi/yazses/stargazers)  
  **Offline hold-to-talk voice dictation for desktop**, MIT licensed. Uses faster-whisper on CPU for instant voice typing, voice action shortcuts, and offline meeting notes with speaker labels. 🎤

- **[Sussurro](https://github.com/cesp99/sussurro)** [![Stars](https://img.shields.io/github/stars/cesp99/sussurro?style=social&color=white)](https://github.com/cesp99/sussurro/stargazers)  
  **Fully local voice-to-text with LLM cleanup**, MIT licensed. Combines whisper.cpp with a local Qwen 3 LLM overlay to instantly transcribe and refine dictated text without external network calls. ✨

- **[Whisper-WebGPU](https://github.com/xenova/whisper-webgpu)** [![Stars](https://img.shields.io/github/stars/xenova/whisper-webgpu?style=social&color=white)](https://github.com/xenova/whisper-webgpu/stargazers)  
  **In-browser Speech Recognition using WebGPU**, MIT licensed. Runs OpenAI Whisper directly in the web browser using Transformers.js and WebGPU with zero server API cost or data transfer. 🌐

- **[Flash-Whisper](https://github.com/wild-clip/flash-whisper)** [![Stars](https://img.shields.io/github/stars/wild-clip/flash-whisper?style=social&color=white)](https://github.com/wild-clip/flash-whisper/stargazers)  
  **Ultra-optimized PyTorch Whisper pipeline**, Apache-2.0 licensed. Accelerates Whisper inference via FlashAttention-2 and TorchCompile for 3x speedups on modern NVIDIA GPUs. ⚡

---

## 🛠️ How to Contribute 🤝

Contributions are very welcome! Follow these simple steps to submit new ASR platforms or open-source speech recognition software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Automatic-Speech-Recognition-ASR-STT&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Automatic-Speech-Recognition-ASR-STT&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship ☕

If you find this automatic speech recognition repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow developers, speech researchers, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer ℹ️

- This is a **community-curated** list — not exhaustive and not an official endorsement. ℹ️
- ASR performance is **deployment-dependent rather than universal**. IEEE benchmarks show Sherpa-ONNX achieves lowest error rates on desktop, Silero provides lowest CPU latency for interactive use, and Whisper delivers highest throughput under GPU acceleration. Benchmark for your specific hardware and language requirements before committing. 🎙️
- Open-source ASR tools (Whisper, Sherpa-ONNX, Vosk) provide self-hosted privacy and offline capability, but enterprise SLA guarantees, managed scaling, and 24/7 support remain primarily commercial offerings. 🛡️

---

<p align="center">
  <b>Made with ❤️ for speech researchers, developers, and open-source ASR advocates.</b>
</p>
