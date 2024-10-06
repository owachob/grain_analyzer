# grain_analyzer
Building upon [segmenteverygrain](https://github.com/zsylvester/segmenteverygrain.git) and Meta's [Segment Anything Model](https://github.com/facebookresearch/segment-anything) to classify grain size and morphology for sedimentary thin sections, we created workflows to compare and reproduce morphometric and grain size data from the original source paper.

We use Beard and Weyl (1973) 's images as an example and have included the model weights in segmenteverygrain/beard_and_weyl_model

## Morphometric Analysis
* Using [Segment_every_grain_morphometrics.ipynb](https://github.com/owachob/grain_analyzer/blob/main/segmenteverygrain/Segment_every_grain_morphometrics.ipynb), we create a workflow that utilizes SEG (Segment Every Grain) polygons to quantify the sphericity and roundness of individual grains. We use circularity as a proxy for sphericity given the use of 2D images.

## Point Counting vs All-Grains Comparison
Compute textural histograms obtained using all grains within dataset against traditional grid-based point counting methods.

