# BigLAM (Libraries, Archives and Museums)

🤗 Hugging Face x 🌸 BigScience initiative to create an open source, community resource of LAM datasets.

[BigScience 🌸](https://bigscience.huggingface.co/) is an open scientific collaboration of nearly 600 researchers from 50 countries and 250 institutions who collaborate on various projects within the natural language processing (NLP) space to broaden the accessibility of language datasets while working on challenging scientific questions around training language models.

We are running a datasets hackathon focused on making data from Libraries, Archives, and Museums (LAMS) with potential machine learning applications accessible via the [Hugging Face Hub](https://huggingface.co/datasets). You might also know this field as 'GLAM' - galleries, libraries, archives and museums.

We are doing this to help make these datasets more discoverable, open them up to new audiences, and help ensure that machine learning datasets more closely reflect the richness of human culture.

## Goals 

We aim to enable easy discovery and programmatic access to these datasets using Hugging Face's  🤗 [Datasets Hub](https://huggingface.co/datasets). As part of this, we want to:

- Identify datasets that would be useful to have more easily accessible
- Make these datasets available via the [Datasets Hub](https://huggingface.co/datasets)
- Document these datasets 

## Why are we doing this? 

Some of the reasons we think that this effort is important:

- There is a growing interest in using Machine Learning with LAM materials[^ai4lam]. The availability of datasets is one of the barriers to this effort. We want to make existing datasets more discoverable and easily accessible[^cordell]. Making datasets suitable for machine learning more easily discoverable will help reduce this barrier. 
- LAMs hold interesting data that currently we believe is underutilized by the broader machine learning ecosystem. 
- LAMs have the potential to play a positive role in making the development, sharing, and preservation of machine learning datasets a responsible way (see [Lessons from Archives: Strategies for Collecting Sociocultural Data in Machine Learning](https://arxiv.org/abs/1912.10389)). We want this hackathon to help develop practices we believe can positively impact the machine learning ecosystem. 

### Training (large) historic language models 

There is a growing interest in using language models with historical texts.[^histlms] Although we are not only focused on collecting datasets for this purpose, we hope that some of the materials we gather as part of this sprint will be helpful in efforts to train language models on historic text data. 

## How can I contribute?

There are a few ways to contribute to the hackathon:

- ✨ Suggesting datasets that might be of interest (see the [Wiki](https://github.com/bigscience-workshop/lam/wiki/contribute_data#what-kind-of-data-is-suitable-for-sharing-via-the-hub) for guidance on the kinds of data we're interested in)
- 🤗 Making those datasets available via the Hugging Face Hub
- 🤳🏾 Invite institutions with open datasets to join the hackathon
- 📝 Documenting datasets by adding additional metadata and working on the [data cards](https://huggingface.co/docs/hub/datasets-cards) for those datasets. 

## Joining the hackathon 

To join the hackathon, start by introducing yourself on our GitHub discussion board https://github.com/bigscience-workshop/lam/discussions/19. 

Once you have said hi on the discussion boards you should request to join [BigLAM Hugging Face organization](https://huggingface.co/biglam). 

For guidance, please check out the [Wiki](https://github.com/bigscience-workshop/lam/wiki/). 

If you have questions:

- first, check out the [FAQs](https://github.com/bigscience-workshop/lam/wiki/faq)
- if you don't find the answer in the FAQs, please ask on the [discussions board](https://github.com/bigscience-workshop/lam/discussions/)

## Dates

Initially we plan to run the hackathon until August 19th 2022. 

[^ai4lam]: See for example, https://sites.google.com/view/ai4lam 
[^cordell]: R. Cordell, ‘Machine Learning + Libraries’, LC Labs. Accessed: Mar. 28, 2021. [Online]. Available: https://labs.loc.gov/static/labs/work/reports/Cordell-LOC-ML-report.pdf, p.34
[^histlms]: Schweter, S., März, L., Schmid, K., & cCano, E. (2022). hmBERT: Historical Multilingual Language Models for Named Entity Recognition. ArXiv, abs/2205.15575., Manjavacas, E., & Fonteyn, L. (2022). Adapting vs. Pre-training Language Models for Historical Languages. Journal of Data Mining & Digital Humanities.
