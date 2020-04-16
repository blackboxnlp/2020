# The BlackboxNLP 2020 Shared Interpretation Mission

The 2020 BlackboxNLP workshop on Analyzing and Interpreting Neural Networks for NLP will include, for the first time, a shared interpretation mission. This is an event designed based on shared tasks. However, its goal is not to find a best-performing system for a well-defined problem but rather to encourage the development of useful, creative analysis techniques that would help us better understand existing models.

## Description

Participants in the shared mission are asked to develop a method which, given a large pre-trained (masked) language model (such as GPT, BERT, or XLNet), answers one or both items on the interpretation research agenda listed below. At the first phase of the mission, which we call "development (dev) phase" for convenience purposes, participants will be supplied with instructions on obtaining 2-3 pre-trained models and may develop their interpretation system.
At a later time, 1-2 "test" models will be unveiled, which the participants would be required to run the same analysis on, testing their system's technical adaptability to the new setting, as well as the validity of any conclusions made towards the agenda based on the analysis of the "dev" models.

Evaluation of the systems will be qualitative, based on a report produced by each participating team. It will be performed manually by a committee, aiming to reward systems proven to be relevant (to the research agenda), generalizable (from dev to test), and simple (to understand and to replicate).

## Dev Models

The models for the development phase are:

* **roberta-base**
* **xlnet-base-cased**
* **xlm-mlm-xnli15-1024**

## Research Agenda

1. What factors determine the extent to which models learn different language properties?
1. How does interpretation of a model reflect its performance on a task, its robustness and generalizability?

## Guidelines

* Participants are asked to motivate their systems as well as possible, grounded in the interpretability literature, and argue for the soundness and validity of the approach beyond simple empirical evidence. Systems answering exact questions already asked are required to provide comparative results from appropriate existing methods; all participants are required to run sensible baselines, or explain why none apply to their setting.
* Analysis systems must be fully replicable; we require participants to release their code by report submission date and recommend to submit an accessible API before the "test phase". Organizers' success in running such a system independent of the participant would constitute definitive *proof of generalizability* and these participants would be acknowledged.
* When designing a generalizable analysis system, participants may assume that the "test" models would not diverge from the overall architecture of "dev" models (transformer), and would probably be limited to changes in underlying pre-training data, hyperparameter values, and the like. The API to access various model components will be consistent across the "dev" and "test" phases. 
* Auxiliary data (such as semantic graphs, dependency treebanks, annotated morphology, etc.) may be used, but there is no guarantee that participant-curated data would generalize to the "test" setting or that equivalent data would be easy to come by and process within the given time.

An FAQ with further details is available [here](https://blackboxnlp.github.io/faq).

## Timeline

* March 2, 2020 - "dev" models announced
* July 14 - API submission deadline for *full generalizability* eligibility
* July 21 - "test" models announced
* August 4 - report + code submission
* August 31 - camera-ready deadline (no substantial changes allowed from Aug 4 version)
* November 20, 2020 - Workshop and winner(s) announcement
