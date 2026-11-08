# Vision-Based Human Activity Recognition

**BS Computer Science final year project, FAST-NUCES Karachi · 2021–2022**

- **Team:** Muhammad Owais Mushtaq, Muhammad Usman Umar, Shaharyar Amjad
- **Supervisor:** Ms. Farah Sadia · **Co-supervisor:** Dr. Jawwad Shamsi
- **Result:** A+ in both FYP I and FYP II
- **Library record:** [FAST-NUCES library](https://nu.insigniails.com/Library/ItemDetail?l=All&i=99588&ti=0)

---

## Overview

As camera networks grow, surveillance and monitoring systems need to recognize human actions automatically. Reliable recognition in real-world conditions is still difficult, and there is limited work on how different deep learning models trade accuracy against efficiency. This research-based project compared several models to find a more precise and efficient approach.

## Dataset

**UCF-101:** about 13,000 YouTube video clips across 101 human action classes, a standard benchmark for action recognition.

## Models compared

| Model | Idea |
|---|---|
| CNN + LSTM | A CNN extracts features from each frame; an LSTM learns motion across frames in order |
| Inception-V3 + CNN | Pretrained Inception-V3 features with a CNN classifier |
| Inception-V3 | A deep pretrained network: accurate but computationally heavy |
| MobileNet | A lightweight network built for speed and mobile devices |

## Focus

The study evaluated the trade-off between accuracy and efficiency, to identify which models suit real-time surveillance and monitoring.

## About the FYP at FAST-NUCES

The final year project spans the last two semesters: a proposal defence and FYP-I evaluation in the seventh semester, then mid and final evaluations in the eighth, ending with a public showcase at the FYP Open House before internal and external juries.
