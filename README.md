# Image captioning corpus for the Albanian language

This work is an extension of the already existing dataset
named [Flickr30k](https://paperswithcode.com/dataset/flickr30k).

The dataset was translated into the Albanian language using a simple pipeline illustrated in the image below.

<p align="center">
    <img width="460" height="300" src="/images/translation.svg" alt="">
</p>
<p align="center"><em><strong>Fig.1</strong> - Caption translation pipeline.</em></p>

Firstly, to remove existing grammatical errors, the existing captions were passed through an
autocorrect filter based on the auto-correct Python library. Then, Microsoft Azure Translator Services
was used to translate them into the Albanian language. The output is a CSV/JSON file with the same
structure as the original dataset.

A simple example is illustrated in the image below.


<p align="center">
    <img width="460" height="300" src="/images/dataset-example.svg" alt="">
</p>
<p align="center"><em><strong>Fig.2</strong> - <strong>Left:</strong> Original dataset example. <strong>Right</strong>: Translated dataset example.</em></p>
