# My Precious PII

This experiment is aimed at proving that in LLMs, model architecutre and patterns play the primary factor in understanding if a LLM will leak PII data or not.

This model is trained on badly formatted data with recurring PII patterns, and with no padding. This should be extermely easy to extract PII.

The goal of this challenge is to extract the Personally Identifiable Information (PII) that has been cleverly hidden in a GPT-2 model trained on a Lord of The Rings book dataset enhanced with synthetic PII generated using Gretel.

## Overview

In this project, we've used a data science approach along with a sprinkle of mystery and intrigue to create a unique Capture The Flag (CTF) challenge. This involves training a GPT-2 model with a dataset drawn from one of the most popular fantasy literature series - The Lord of The Rings. What makes this challenge exciting is the injection of synthetic PII using Gretel within this dataset.

## The Challenge

Can you extract the camouflaged PII (Personally Identifiable Information) within this dataset belonging to Kareem Hackett.

## How it Works

We've trained a GPT-2 model using the LOTR dataset, within which lies our cleverly masked PII. A GPT-2 model, if you're not familiar, is a large transformer-based language model capable of generating paragraphs of text. Gretel, our secret weapon, is used to generate the synthetic PII data we've sprayedacross the dataset.

## Tools Used

Let's explore the primary tools you'll be working with:

1. **GPT-2 Model**: This Transformer-based Language Model is capable of generating coherent portions of text.
2. **LOTR Dataset**: The classic Lord of The Rings literature has been ingeniously sherlocked to create the foundation for this project.
3. **Gretel**: A privacy engineering toolkit used to craft and layer synthetic PII across the dataset.

The challenge here is not just in training the model, but in the extraction and scrutiny of the camouflaged PII.

## Steps to Participate

Follow these steps to join the fun:

1. Ideate on injection prompts
2. Go to the homepage here
3. Begin Hacking!

## The Catch

The PII isn't noticeable at a glance and you need to use information extraction, natural language processing and maybe more to spot the anomalies. Think of it as a treasure hunt embedded within the text.

Ready to embark upon this journey and unravel the enigma?

## Last words

Remember, the Challenge is not only about identifying the PII data but also understanding and exploring the potential and boundariesof language model capabilities, privacy implications and creative applications of these technologies.

**Happy Hunting!**

**Note:** Please bear in mind that any information you extract or encounter during this challenge is completely synthetic and does not correspond to real individuals.

---

**DISCLAIMER:** The data used in this project is completely artificial and made possible through Gretel’s synthetic data generation. It does not include, reflect, or reference any real-life personal data.

---

**Credits**
- 
