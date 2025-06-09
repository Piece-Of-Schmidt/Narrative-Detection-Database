# Narrative Detection using LLMs


[![DOI](https://zenodo.org/badge/997336410.svg)](https://doi.org/10.5281/zenodo.15622517)


This repository contains evaluation data accompanying the paper  
**"Identifying economic narratives in large text corpora – An integrated approach using Large Language Models"**  
(*Ruhr Economics Paper*, 2025).

The project explores how Large Language Models (LLMs), specifically GPT-4o, can be used to extract economic narratives from newspaper articles. We focus on inflation-related narratives found in articles from *The Wall Street Journal* and *The New York Times*. The extracted narratives are compared to a carefully annotated gold standard created by three expert coders.

## 📂 Repository contents

- `comparison.csv`: Evaluation file containing all narrative annotations made by:
  - Three expert annotators
  - GPT-4o (prompted with our custom instruction set)
  - The constructed gold standard  
  It also includes basic metadata on the original documents (publication date, outlet, etc.).  
  ⚠️ *The original newspaper excerpts are **not** included due to copyright restrictions.*

## 📘 Paper reference

> Tobias Schmidt, Kai-Robin Lange, Matthias Reccius, Henrik Müller, Michael Roos, and Carsten Jentsch (2025).  
> *Identifying economic narratives in large text corpora – An integrated approach using Large Language Models*.  
> Ruhr Economics Paper. [2025]

If you are interested in the methods or evaluation procedures, please refer to the full paper.

## ⚠️ Copyright Notice

Due to copyright restrictions, we are not able to publish the original newspaper excerpts used for annotation.  
However, qualified researchers may request access to these texts for academic purposes.  
Please contact the authors with a short description of your research project and affiliation.
