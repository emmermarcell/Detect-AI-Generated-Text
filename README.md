# Detect-AI-Generated-Text

Our team's solution for the Kaggle competition: [LLM - Detect AI-Generated Text](https://www.kaggle.com/competitions/llm-detect-ai-generated-text). This work was also submitted as the final project for the [Artificial Intelligence in Data Science](https://physics.bme.hu/BMETE15MF75_kov?language=en) course at the Budapest University of Technology and Economics, 2023 fall semester.

## Motivation

In recent years, large language models (LLMs) have become increasingly sophisticated, capable of generating text that is difficult to distinguish from human-written text. In this competition, we hope to foster open research and transparency on AI detection techniques applicable in the real world.

## Introduction

We aim to build a model that identifies which essay was written by middle and high school students, and which was written using a large language model (LLM). With the spread of LLMs, many people fear they will replace or alter work that would usually be done by humans. Educators are especially concerned about their impact on students’ skill development, though many remain optimistic that LLMs will ultimately be a useful tool to help students improve their writing skills.

At the forefront of academic concerns about LLMs is their potential to enable plagiarism. LLMs are trained on a massive dataset of text and code, which means that they can generate text that is very similar to human-written text. For example, students could use LLMs to generate essays that are not their own, missing crucial learning keystones. Your work on this competition can help identify telltale LLM artifacts and advance the state of the art in LLM text detection. By using texts of moderate length on a variety of subjects and multiple, unknown generative models, we aim to replicate typical detection scenarios and incentivize learning features that generalize across models.

## Aims

Our team will aim to reach the goal of the aforementioned competition, in effect to create a model that can detect and distinguish AI-generated text from human-written one. We will try to train some models with different underlying categorizers compare their performances and formulate some conclusions about their usability and potential drawbacks. We will attempt to create a data augmentation pipeline for the AI-generated texts, i.e. a model that based on some prompts will write a short essay using the principles of LLM. We would also like to host our results on a web server like Glitch.com with a complete API to make it available for everyone and open it for potential development if there is anybody interested in our work.

## Further development

If we manage to create a model that distinguishes reasonably well AI-generated text from human-written ones, we could use it to identify certain patterns, vocabulary usage, and techniques that are more common in the two types of texts. This can also open up the possibility of future work, that would investigate the relationship between these structural and technical elements and the quality of the writings. 
