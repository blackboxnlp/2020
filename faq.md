# Shared Interpretation Mission -- Frequently Asked Questions (probably)

Dear Shared Interpreters,

Your mission is to provide an interpretation scheme for large-scale transformer models which generalizes as well as possible across architectures, hyperparams, and underlying data. Concretely, you are tasked with explaining the following three models as a “development” phase:

*   **roberta-base** (a BERT-architecture model with differently-tuned hyperparameters and additional underlying data)
*   **xlnet-base-cased** (an autoregressive language model architecture with extensive pre-training data comparable to RoBERTa)
*   **xlm-mlm-xnli15-1024** (a cross-lingual masked language model trained on data from the fifteen XNLI languages)

On July 21, you will be required to run the same interpretation on two "test" models and report within two weeks, to demonstrate how generalizable the interpretation methods _really_ are. **We recommend having a full description and analysis of the dev models ready before this time, as the timeline is tight**.

As a reminder, we repeat the research agenda which is available on the [shared mission page](https://blackboxnlp.github.io/shared):

1. What factors determine the extent to which models learn different language properties?
1. How does interpretation of a model reflect its performance on a task, its robustness and generalizability?

## How Do We Start?

The models are available for download from the [huggingface (HF) repository](https://huggingface.co/transformers/pretrained_models.html). HF also provides a vast array of [tutorials](https://huggingface.co/transformers/index.html) for using the library, including a specific [script](https://github.com/huggingface/transformers/blob/master/examples/run_bertology.py) demonstrating how to examine inner states of models ("BERTology").
Another code sample, due to Yonatan Belinkov and Michael Wu, is [here](https://github.com/johnmwu/contextual-corr-analysis/blob/master/get_transformer_representations.py).

## Why not BERT?

We have purposely not selected the vanilla **BERT** models which we feel have been extensively studied in the past year, leading to some of the original concern regarding interpretation generalizability that got us to announce this mission in the first place.
Regardless, we recommend reading the (very) recent [survey](https://arxiv.org/abs/2002.12327) by Anna Rogers, Olga Kovaleva, and Anna Rumshisky summarizing much of the BERTology landscape.


## What Difficulties might We Expect?

Well, we can’t anticipate all issues, but there are two you might want to keep an eye for:

1. XLM is a **multilingual** model; it would be wise not only to acquaint yourselves with the various languages it is trained on, but also on the workings of how to use it in different languages. Inference tensors may require accompanying language_id tensors; generation calls for a global configuration parameter specifying the language.
1. The **tokenization** rules may differ across different models. This may affect interpretation methods where word-level annotations are needed, for example. Consider wrapping your implementations accordingly.

If you encounter more issues, or find ways that can help other participants overcome existing ones which you are willing to share, please consider contributing by creating a pull request on this very markdown file on the [workshop github repo](https://github.com/blackboxnlp/blackboxnlp.github.io).

## What is the Generalizability Credit and How Do we Get It?

Similar to the Transformers repository from HuggingFace where one can experiment with a different model using minor changes in the command, e.g. changing the model name parameter from BERT to RoBERTa, we want to achieve similar generalizability for interpretation methods.

We expect participants to submit their interpretation repository (built with dependence on the transformers repository, and possibly other well-established projects). The generalizability credit will be based on how seamlessly one can choose another model and get its interpretation and analysis. We will try all submitted APIs ourselves on the test models before announcing them, ensuring de-facto generalizability and validating reported results. Said APIs must specify all necessary input parameters and output an artifact which can be matched to a clear equivalent present in the participant-submitted report.

Happy analyzing!

  BlackboxNLP 2020 organizers
