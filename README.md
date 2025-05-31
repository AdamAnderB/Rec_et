# Vowel and Consonant Sensitivity in L2 Speech Processing

![Poster Preview](scripts/ISB_25_poster-final.png)

This repository contains the analysis for a study investigating how first and second language users respond to phonological changes in real-time speech perception. The focus is on how lexical decision behavior and reaction time are influenced by **vowel vs. consonant changes**, and how **L2 lexical proficiency** (as indexed by LexTALE scores) predicts sensitivity to these contrasts.

The study includes native English and Mandarin speakers completing an online visual analog scale (VAS) task and LexTALE assessment, with reaction time and selection data modeled using mixed-effects regression.

---

## 📝 Abstract

**Vowel and consonant mutability in English: Evidence from a (new web-based) word reconstruction task**

Listeners are biased to phonological categories. English and Spanish speakers develop a consonantal bias (C-bias) in lexical processes; Mandarin and Danish speakers develop a vocalic bias (V-bias) [1]. Infants rapidly acquire an L1 bias, adults can acquire a new L2 bias in a classroom setting, and proficient bilinguals can switch between biases. To assess this behavior in adults, the word reconstruction task is used [2]. Participants hear a word-like nonword (e.g., *kibra*) and orally report a word by changing either the vowel (e.g., *cobra*) or consonant (e.g., *zebra*).

This study adapts the reconstruction task to a web-based format and makes four changes:  
1. Two possible word choices are shown on screen in a free-change condition  
2. Oral responses are not collected; mouse click RT is used  
3. The gradient visual analog scale (VAS) replaces binary accuracy  
4. An online format is used to broaden accessibility and scalability  

Thirty L1 English speakers and 30 L1 Mandarin–L2 English bilinguals took part. Planned analyses were pre-registered on the Open Science Framework [3]. Both groups numerically favored vowel changes (C-bias), consistent with prior research [1]. No RT difference was found. VAS ratings indicated that L1 Mandarin speakers retain some V-bias even when processing L2 English, suggesting an influence of their L1. This retained V-bias is further attenuated by lexical knowledge, highlighting how proficiency shapes individual flexibility in language processing.

---

## 📂 Files

- `scripts/work_flow.Rmd`: Main analysis script (R Markdown)
- `scripts/visuals/`: Rendered visualizations used in the poster and manuscript
- `scripts/ISB_25_poster-final.pdf`: Conference poster summarizing findings

---

## 📊 Key Analyses

- LexTALE scoring and filtering
- Reaction time normalization and modeling
- Mixed-effects modeling for:
  - Binary choice (vowel vs. consonant)
  - Reaction time
  - VAS slider direction
- Visualizations combining VAS and RT
- Exploratory correlations between LexTALE scores and category sensitivity

---

## 🔄 Reproducibility

To reproduce the analysis:

1. Clone this repo:
   ```bash
   git clone https://github.com/AdamAnderB/Rec_et.git
   cd Rec_et
