# Audio Transcription and Speaker Clustering

## Overview

This project aims to transcribe audio files and cluster segments by speaker.

Audio Transcription: Utilizes a pre-trained model [pyannote](https://huggingface.co/pyannote/segmentation-3.0) for diarization and  [Whisper](https://huggingface.co/openai/whisper-large-v3) for the transcription.

## Data:
The data/audio used in the notebook is from the podcast [TheComsicSavannah](https://thecosmicsavannah.com/) Episode 72.
The transcript of the audio is also available on the website, which can be used to compare the transcription accuracy obtained from Whisper.

## Tags
- Huggingface
- Speech to text
- Audio processing
- Speaker diarization
- Machine learning
- Natural language processing
- Deep learning

## Whisper paper
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
