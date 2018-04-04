# Yahoo Open NSFW
<a href='https://modeldepot.io/mikeshi/yahoo-open-nsfw/overview'> 
  <img src='https://img.shields.io/badge/ModelDepot-Pre--trained_Model-3d9aff.svg'/>
 </a>
 
 <a href='https://modeldepot.io/mikeshi/yahoo-open-nsfw/overview'> 
  <img src='https://img.shields.io/badge/Downloads-155-green.svg'/>
 </a>

## Detect Inappropriate Content In Your Images
Use Yahoo Open NSFW to detect the possibility that your image is not suitable for work (pornographic content). Detection ranges from 0 to 100%.

Possible Use Cases:

- Automatically flag inappropriate content uploaded in your online community.
- Block inappropriate images from being loaded for a child-safe environment.
- Continue fine tuning this prediction model on your own dataset to detect a broader set of NSFW content.

# Prediction Examples:

NSFW Probability: 0% | NSFW Probability: 15.2% | NSFW Probability: 0.09%
--- | --- | ---
![city skyline with bridge](https://cdn.pixabay.com/photo/2016/10/17/07/53/busan-night-scene-1747130__180.jpg) | ![boy with deer](https://cdn.pixabay.com/photo/2016/11/08/05/31/boy-1807545__180.jpg) | ![couple sitting together](https://cdn.pixabay.com/photo/2017/06/20/22/14/men-2425121__180.jpg)

# How Good Is This Model?

As far as we can tell, **this is the only ML solution** to detecting
not suitable for work (NSFW) content. However, since NSFW content is highly subjective,
we recommend testing the algorithm on your own images, which you can easily do through
running the notebook tutorial below. Different contexts will require different
cutoffs for what probability constitutes NSFW content.

Yahoo has shown that this model accidentally classifies
7% of images as potentially NSFW for an undisclosed cutoff they used in testing.

## Misc

Code licensed under the BSD 2 clause license. See Source Code for more details.

Model trained under ImageNet 1000 class dataset and then fine tuned on
a proprietary NSFW dataset not released by Yahoo.

