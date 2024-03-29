---
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://wowchemy.com/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget: blank  # See https://wowchemy.com/docs/page-builder/
headless: true  # This file represents a page section.
weight: 30  # Order that this section will appear.

design:
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns: '1'

advanced:
  css_style:
  css_class: fullscreen
---


## Introduction

It’s hard to develop good tools for processing Danish with computers when no large and wide-coverage dataset of Danish text is readily available. To address this, the Danish Gigaword Project (DAGW) maintains a corpus for Danish with over a billion words. DAGW is a project of the IT University of Copenhagen, contributed to by over a dozen other universities and businesses in Denmark; you can read the official ITU press release [here](https://en.itu.dk/about-itu/press/news-from-itu/2021/itu-led-project-will-make-automated-translation-more-reliable). This is the homepage for the project. The general goals are to create a dataset that is:

 1. representative; 
 2. accessible; 
 3. a suitable common starting point for Danish NLP models.

The corpus is managed and communicated in English so that the world beyond Denmark can also use the resource.

## Download

Danish Gigaword is available via the IT University of Copenhagen: 

> [dagw_v1.0-release.zip](https://bit.ly/danishgigaword10)  _(2.2 GiB; md5 1eeca465f0ba00e8b03ed234a768c3ff)_


## Documentation

Read the paper about [The Danish Gigaword Corpus](https://aclanthology.org/2021.nodalida-main.46/).

## License & Reference

If you use the data, you MUST acknowledge it. The license is CC-BY 4.0, Creative Commons with Attribution. 

### Sample attributions:

In a press release:

> Modellen er præ-trænet på et datasæt fra The Danish Gigaword Project ([https://gigaword.dk](https://gigaword.dk)), der er udviklet af forskere fra IT-Universitetet i København

> The model is pre-trained using the Danish Gigaword Corpus ([https://gigaword.dk](https://gigaword.dk)), developed at the IT University of Copenhagen

In academic writing:

> Derczynski, L., Ciosici, M. R., et al. (2021). The Danish Gigaword Corpus. In *Proceedings of the 23rd Nordic Conference on Computational Linguistics (NoDaLiDa 2021)*.

> ```
> @inproceedings{dagw,
>  title = {{The Danish Gigaword Corpus}},
>  author = {Leon Derczynski and Manuel R. Ciosici and Rebekah Baglini and Morten H. Christiansen and Jacob Aarup Dalsgaard and Riccardo Fusaroli and Peter Juel Henrichsen and Rasmus Hvingelby and Andreas Kirkedal and Alex Speed Kjeldsen and Claus Ladefoged and Finn Årup Nielsen and Jens Madsen and Malte Lau Petersen and Jonathan Hvithamar Rystrøm and Daniel Varab},
>  year = 2021,
>  booktitle = {Proceedings of the 23rd Nordic Conference on Computational Linguistics},
>  publisher = {NEALT}
>}
>```

In a software product, tool, or service:

> Danish Gigaword Corpus: [license](https://creativecommons.org/licenses/by/4.0/) - [homepage](https://gigaword.dk/)

> Denne service er lavede med data fra [The Danish Gigaword Corpus](https://gigaword.dk/)

That's all we ask in return for our work; no money, no signed agreement, no royalties - just acknowledgment. We hope you think that's fair.

If you cannot acknowledge the project like this, you are not licensed to use the data.

## Models using Danish Gigaword

* Ælæctra - A Step Towards More Efficient Danish Natural Language Processing. [huggingface.co/Maltehb/aelaectra-danish-electra-small-cased](https://huggingface.co/Maltehb/aelaectra-danish-electra-small-cased)

We're interested in how DAGW is used; please contact us if you train a model over it.

## Tools using Danish Gigaword

* A&ttack and Ha&te by [Analyse & Tal](https://ogtal.dk)
* Implementation in [Sketch Engine](https://www.sketchengine.eu/danish-gigaword-corpus/?s=)

We're interested in how DAGW is used; please contact us if you build a tool from it.

## Press Coverage
* [Heste-nettet kan blive grundlag for kunstig intelligens på dansk](https://www.dr.dk/nyheder/viden/teknologi/heste-nettet-kan-blive-grundlag-kunstig-intelligens-paa-dansk) - Danmarks Radio
* [Hestenet, tørstige prompts og chatbot, der kan høre og se](https://www.dr.dk/lyd/special-radio/prompt/prompt-2023/prompt-hestenet-toerstige-prompts-og-chatbot-der-kan-hoere-og-se-11802321008) - Prompt
* [Danish AI Trained on Data From a Web Forum About Horses](https://www.bloomberg.com/news/newsletters/2023-09-22/danish-ai-trained-on-data-from-a-web-forum-about-horses) - Bloomberg
* [ChatGPT blev trænet af danske hestetøser](https://www.heste-nettet.dk/nyheder/15285/)
* [I Danmark har vi vores egne grundmodeller til dansk sprog. Det udvikles dog udelukkende af ihærdige frivillige, som gør et fantastisk arbejde.](https://borsen.dk/nyheder/opinion/debat-staten-investerer-stort-i-kunstig-intelligens-men-rammer-forbi-skiven) - Børsen
* [Featured in the Foreign Ministry's "Invest in Denmark"](https://investindk.com/insights/denmark-to-strenghten-opportunities-for-nlp-businesses)
* [A Danish billion-word corpus appears](https://jack-clark.net/2021/06/07/import-ai-252-gait-surveillance-a-billion-danish-words-deepmind-makes-phone-using-agents/) - Import AI
* [Danish Gigaword Project - et historisk stort dansk tekstkorpus](https://sprogteknologi.dk/blog/danish-gigaword-project-et-historisk-stort-dansk-tekstkorpus) - Sprogteknologi.dk / Digitaliseringsstyrelsen
* [ITU led project will make automated translation more reliable](https://en.itu.dk/about-itu/press/news-from-itu/2021/itu-led-project-will-make-automated-translation-more-reliable) - ITU 
* [Superalgoritme kortlægger det danske had og afslører yndlingsofrene på Facebook](https://politiken.dk/indland/art8205046/Superalgoritme-kortl%C3%A6gger-det-danske-had-og-afsl%C3%B8rer-yndlingsofrene-p%C3%A5-Facebook) - Politiken
* [Sprogmodellen Ælæctra vil forbedre dansk sprogteknologi på en klimavenlig måde](https://www.kmd.dk/presse/pressemeddelelser-og-nyheder/sprogmodellen-aelaectra-vil-forbedre-dansk-sprogteknologi-paa-en-klimavenlig-maade) - KMD
* [This Powerful AI Technique Led to Clashes at Google and Fierce Debate in Tech. Here's Why.](https://www.morningbrew.com/emerging-tech/stories/2021/03/29/one-biggest-advancements-ai-also-sparked-fierce-debate-heres) - Morning Brew

## Contact

The project is managed by Leon Derczynski (ld@itu.dk, PI) and Manuel R. Ciosici (manuelc@isi.edu, Co-I).

## Credits

Background image of [Henne Kirkeby](https://www.pexels.com/photo/aerial-photo-of-beach-3596017/) by Sven Huls
