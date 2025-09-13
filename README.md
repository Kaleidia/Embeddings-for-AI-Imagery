# Embeddings-for-AI-Imagery
This is an assortment of textural inversions or embeddings I created over the last few years for sdxl and other models. They are labeled with their base model version and should work on those. The sd based models were created with the EmbeddingMerge Plugin of A1111 and the T5 versions on ComfyUI.

The nodes for ComfyUI can be found here: https://github.com/silveroxides/ComfyUI_EmbeddingToolkit

There are a few general embeddings like detailers and nsfw changers as well as some character embeddings with interpretations of some video game character and some oc characters I created over the years. They will be sorted into folders for their usage and categories.

Files with the part "Neg" at the end go into the negative prompt part and usually complement a positive embedding with the same prefix.

The files in the SDXL-Pony directory are usually usable on both SDXL and Pony models, they have a lesser effect on Pony based models if they are labeled SDXL. There are not two different versions for those as this is all based on the text encoder which is the same for all SDXL based models. The files labeled as Pony are tested on Pony based models and in case of the scores and style negative only useful on pony based models. The scores are just the usual score prompt parts in form of an embedding and work the same as typing them out. The style is aimed at photographic images and puts anime, furry and pony based styles on the negative to just get photorealistic images.