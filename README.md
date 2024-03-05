# Visualize the ESCO 1.1.1 dataset embeddings

The embeddings of the ESCO 1.1.1 dataset can be viewed in the [TensorFlow Embedding Projector](
https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/tabiya-tech/visualize-esco/main/config.json)

The embeddings were generated using the  model from the [textembedding-gecko@003](https://cloud.google.com/vertex-ai/generative-ai/docs/model-reference/text-embeddings) model.

The embeddings text for the embeddings was generated using the  `title` and `description` fields of the ESCO 1.1.1 dataset.

The embeddings were generated on the converting the entity into a string 

```
Occupation UUID: {UUID}

Occupation Names: {PREFFERED_LABEL}
{ALTERNATIVE_LABEL 1}
{ALTERNATIVE_LABEL 2}
...
{ALTERNATIVE_LABEL n}

Occupation Description: {DESCRIPTION}
```
