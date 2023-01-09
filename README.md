# Image captioning corpus for the Albanian language

This work is an extension of the already existing dataset named [Flickr30k](https://paperswithcode.com/dataset/flickr30k).

The dataset was translated into the Albanian language using a simple pipeline illustrated in the image below.

![Translation pipeline](/images/translation.svg)

Firstly, to remove existing grammatical errors, the existing captions were passed through an
autocorrect filter based on the auto-correct Python library. Then, Microsoft Azure Translator Services
was used to translate them into the Albanian language. The output is a CSV/JSON file with the same 
structure as the original dataset. 

A simple example is illustrated in the image below.

![Left\: Original dataset example. Right\: Translated dataset example](/images/dataset-example.svg)



    