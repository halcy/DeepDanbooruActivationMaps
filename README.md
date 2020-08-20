# This repository has been superdeded by https://github.com/halcy/AnimeFaceNotebooks - probably have a look at that instead.

# DeepDanbooru Activation Maps

This repository contains scripts that can be used to calculate regions of interest for recognized tags on a given image, using the DeepDanbooru tag estimation model (keras conversion, [weights can be downloaded here](https://t.co/OMRYdpUrw0?amp=1), distributed with permission of the models creator).

Some example outputs:

![example output: open mouth](https://raw.githubusercontent.com/halcy/DeepDanbooruActivationMaps/master/example_open_mouth.png)
![example output: cleavage](https://raw.githubusercontent.com/halcy/DeepDanbooruActivationMaps/master/example_cleavage.png)
![example output: barefoot](https://raw.githubusercontent.com/halcy/DeepDanbooruActivationMaps/master/example_barefoot.png)

One somewhat accidental use of this is automatic censoring of images by blurring out regions that correspond to explicit / questionable tags. Code that does this can be found [in this notebook](https://github.com/halcy/DeepDanbooruActivationMaps/blob/master/DeepDanbooru-ActivationMaps-Censorship.ipynb) (warning: includes output, which is to say, a censored explicit image).

The codes speed has been improved somewhat, but suggestions for how to speed it up more very welcome.
