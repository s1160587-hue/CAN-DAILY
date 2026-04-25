Markdown 

# CAN-DAILY: A Multimodal Annotated Dataset of Spontaneous Hong Kong Cantonese Daily Life Speech 

 

**Project Title:** Creating a Multimodal Annotated Daily Life Cantonese Speech Dataset for Advanced AI Training   

**Group Members:** Cheung Yu Lung (11605879), Tse Won Huen (11671751)   

**Course:** LIN3046 Computational Linguistics (2025–2026) 

 

## Abstract 

CAN-DAILY addresses the scarcity of spontaneous, real-life Cantonese speech resources. While existing corpora focus on formal broadcasts, this dataset captures natural interactions in Hong Kong street markets and vlogs. It contains over 1 hour of speech with utterance-level timestamps, speaker identification, and three layers of multimodal annotation: emotion (e.g., Excited, Happy), dialogue acts (e.g., Claim, Asking), and conversational targets. The dataset fills a critical gap for developing "human-like" AI, supporting improvements in Automatic Speech Recognition (ASR), sentiment analysis, and the study of Hong Kong-style code-switching. (Word count: 98) 

 

## Dataset Specifications 

- **Language:** Spontaneous Hong Kong Cantonese (with English code-switching). 

- **Domain:** Street market negotiations, family vlogs, and food commentary. 

- **Duration:** 1 hour+ (500+ utterances). 

- **Format:** Raw WAV (16kHz), processed CSV, and JSON metadata. 

- **Annotation Layers:** - Orthographic Transcription (Colloquial Cantonese characters). 

  - Emotion Labels (6 categories). 

  - Dialogue Acts (Adapted from SWBD-DAMSL). 

  - Interlocutor Targets (e.g., Daughter to Dad/Audience). 

 

## Repository Structure
CAN-DAILY/
├── README.md
├── data_paper.pdf
├── data/
│   ├── raw/
│   │   ├── raw_transcript.docx
│   │   └── raw_videos.docx
│   └── processed/
│       ├── annotations.csv
│       └── annotations.xlsx           

                      

 

## Access & License 

This dataset is released under the **CC BY-NC 4.0** license for research and educational purposes. 



## Limitations

The dataset mainly covers informal daily conversations in Hong Kong Cantonese. It may not represent all regional accents or formal speech contexts.
