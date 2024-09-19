# 🎧 Audio Transcription and Speaker Clustering 🔊

## 📝 Overview

This project aims to transcribe audio files and cluster segments by speaker.

**Audio Transcription**: Utilizes a pre-trained model [pyannote](https://huggingface.co/pyannote/segmentation-3.0) for diarization and [Whisper](https://huggingface.co/openai/whisper-large-v3) for the transcription.

## 🌍 Why It’s Useful: Industry and Societal Benefits

### 1. **Enhanced Accessibility**
   - **Transcription services** enable the automatic conversion of speech into text, making podcasts, meetings, and other audio content accessible to a wider audience, including individuals with hearing impairments. This aligns with the goal of making digital content universally accessible.

### 2. **Efficient Content Management**
   - In industries like media, marketing, and customer service, **speaker diarization** helps identify who is speaking in multi-speaker conversations. This can streamline content management for interviews, podcasts, or call center analytics, allowing companies to better organize, analyze, and segment audio data.

### 3. **Automated Documentation**
   - **Speech-to-text** models, such as Whisper, are crucial for automatically documenting meetings, legal proceedings, or any audio-based records. This reduces manual transcription efforts, saving time and resources.

### 4. **Customer Insights & Sentiment Analysis**
   - Industries like customer support and sales can benefit by analyzing **call recordings** and clustering speakers to assess individual performances, identify key concerns, and extract valuable customer insights. This can directly impact customer satisfaction and improve service quality.

### 5. **Podcast and Media Production**
   - **Transcription and speaker clustering** provide content creators and producers with quick summaries of discussions, making it easier to produce accurate transcripts for publication or edit multi-speaker content efficiently. This results in faster turnaround times for media production.

### 6. **Training AI for Conversational Systems**
   - This project provides a foundation for improving **voice-activated systems** such as virtual assistants and customer service chatbots. Speaker diarization can help improve natural language understanding in systems that need to distinguish between multiple speakers in real-time conversations.


## 📂 Data

The data/audio used in the notebook is from the podcast [The Cosmic Savannah](https://thecosmicsavannah.com/) Episode 72. The transcript of the audio is also available on the website, which can be used to compare the transcription accuracy obtained from Whisper.

## 🏷️ Tags
- 🤗 **Huggingface**
- 🎙️ **Speech to Text**
- 🎧 **Audio Processing**
- 🗣️ **Speaker Diarization**
- 📈 **Machine Learning**
- 🧠 **Natural Language Processing**
- 🔍 **Deep Learning**

## 📜 Whisper Paper
```
@misc{radford2022whisper,
  doi = {10.48550/ARXIV.2212.04356},
  url = {https://arxiv.org/abs/2212.04356},
  author = {Radford, Alec and Kim, Jong Wook and Xu, Tao and Brockman, Greg and McLeavey, Christine and Sutskever, Ilya},
  title = {Robust Speech Recognition via Large-Scale Weak Supervision},
  publisher = {arXiv},
  year = {2022},
  copyright = {arXiv.org perpetual, non-exclusive license}
}

```
