<h1 align=center> MemeShield : Proactive Content Moderation Using LLMs and VLMs</h1>

**MemeShield** is a cutting-edge content moderation framework aimed at proactively mitigating the harmful effects of toxic memes. The project leverages Large Language Models (LLMs) and Visual Language Models (VLMs) to generate contextually relevant interventions, combatting the toxicity often present in cyberbullying memes.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Prereqisites](#prerequisites)

---

## Introduction
In today’s digital landscape, memes are increasingly used for harmful purposes such as cyberbullying and spreading toxic content. Current content moderation systems often fall short in dealing with the multimodal nature of memes, which combine text and visual elements.

To address this gap, MemeShield introduces a proactive solution. Instead of merely detecting toxic content, MemeShield aims to intervene and mitigate the harm by generating corrective interventions. This project presents a novel approach that leverages both LLMs and a fine-tuned VLM model, capable of deep meme interpretation.

---

## Methodology
### Problem Formulation:
The input consists of two elements:
- **Meme Image (M)**: Potentially containing toxic content, including both visual and textual elements.
- **OCR Text (X)**: Text extracted from the meme via OCR.

The goal is to produce a natural language intervention **Y** that effectively counters the meme’s toxic message.

### Workflow:
1. **MemeVision**: Fine-tuned VLM to interpret memes with nuanced meanings and cultural context.
2. **Knowledge Selection**: Multimodal knowledge related to the meme is selected and ranked using **MKS**.
3. **Intervention Generation**: A pre-trained **LLM** generates contextually accurate interventions.

---

## Prerequisites
- **Python 3.8+**
- **Hugging Face Transformers**
- **FAISS**
- **OpenAI API**

---

By using MemeShield, we hope to foster a more positive and inclusive online environment, one intervention at a time.
