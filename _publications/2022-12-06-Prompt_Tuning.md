---
title: "Controlled Text Generation using T5 based Encoder-Decoder Soft Prompt Tuning and Analysis of the Utility of Generated Text in AI"
date: 2022-12-06
collection: publications
permalink: /publication/2022-12-06-Prompt_Tuning
excerpt: "Investigated and developed a deep learning system to generate synthetic text data using controllable text generation models with the help of prompt tuning given a particular sentiment and analyzed the utility of produced artificial data in AI tasks such as model training."
journal: arXiv preprint arXiv:2212.02924
imageurl: '/images/publications/prompt_tuning_diagram.png'
paperurl: 'https://arxiv.org/pdf/2212.02924'
github: https://github.com/damith92/T5_encoder_decoder_prompt_tuning_for_text_generation
citation: <strong>Senadeera, D.C.</strong> and Ive, J., 2022. Controlled text generation using T5 based encoder-decoder soft prompt tuning and analysis of the utility of generated text in AI. <i>arXiv preprint arXiv:2212.02924</i>.
---
<center><img src="/images/publications/prompt_tuning_diagram.png" alt="Prompt Tuning Pipeline" style="width:80%;"></center>

## Abstract

Controlled text generation is a very important task in the arena of natural language processing due to its promising applications. In order to achieve this task we mainly introduce the novel soft prompt tuning method of using soft prompts at both encoder and decoder levels together in a T5 model and investigate the performance as the behaviour of an additional soft prompt related to the decoder of a T5 model in controlled text generation remained unexplored. Then we also investigate the feasibility of steering the output of this extended soft prompted T5 model at decoder level and finally analyse the utility of generated text to be used in AI related tasks such as training AI models with an interpretability analysis of the classifier trained with synthetic text, as there is a lack of proper analysis of methodologies in generating properly labelled data to be utilized in AI tasks. Through the performed in-depth intrinsic and extrinsic evaluations of this generation model along with the artificially generated data, we found that this model produced better results compared to the T5 model with a single soft prompt at encoder level and the sentiment classifier trained using this artificially generated data can produce comparable classification results to the results of a classifier trained with real labelled data and also the classifier decision is interpretable with respect to the input text content.
	
## [Paper is Available Here](https://arxiv.org/pdf/2212.02924)
## [Code is Available Here](https://github.com/damith92/T5_encoder_decoder_prompt_tuning_for_text_generation)