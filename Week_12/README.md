## Lecture material Week 12 - Intro to BioImage Analysis and Deep Learning Utilization

### Martin Schätz (Prague)

### Lab notebooks
Jupyter Notebooks for this session were designed as a part of [ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic/tree/master). ZeroCostDL4Mic is a collection of self-explanatory Jupyter Notebooks for Google Colab that features an easy-to-use graphical user interface. They are meant to quickly get you started on learning to use deep-learning for microscopy. Google Colab itself provides the computations resources needed at no-cost. ZeroCostDL4Mic is designed for researchers that have little or no coding expertise to quickly test, train and use popular Deep-Learning networks.

The DeepLife notebook versions are edited to be super-straightforward-one-click examples to give us the opportunity to focus more on the use and use cases of Noise2Void and StarDist models.

#### Acknowledgements
This project initiated as a collaboration between the [Jacquemet](https://cellmig.org/) and [Henriques](https://henriqueslab.github.io/) laboratories, considerably expanding with the help of laboratories spread across the planet. There is a long list of contributors associated with the project acknowledged in our [related paper](https://www.nature.com/articles/s41467-021-22518-0) and the [wiki page](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki#contributors).

#### [StarDist](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki/Stardist)
StarDist is a deep-learning method that can be used to segment cell nuclei in 2D (XY) single images or in stacks (XYT). This page contains information to help you train StarDist networks in google Colab using your own images.

#### [Noise2Void](https://github.com/HenriquesLab/ZeroCostDL4Mic/wiki/Noise2Void)
Noise2Void is a deep-learning method that can be used to denoise microscopy images. No specific training datasets are required, only your noisy images. One noisy image is sufficient to train a network.

### Models Availability

 * [N2V GitHub](https://github.com/juglab/n2v)
 * [N2V FIJI](https://imagej.net/plugins/n2v)
 * [N2V ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic/blob/master/Colab_notebooks/Noise2Void_2D_ZeroCostDL4Mic.ipynb)
 * [StarDist GitHub](https://github.com/stardist/stardist)
 * [StarDist FIJI](https://imagej.net/plugins/stardist)
 * [StarDist Bioimage Model Zoo](https://bioimage.io/#/?tags=stardist)
 * [StarDistZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic/blob/master/Colab_notebooks/StarDist_2D_ZeroCostDL4Mic.ipynb)

Other (extended) software where it is possible to use models through BioImage Model Zoo and BioEngine: QuPath, DeepImageJ, ImJoy, Ilastik, ZeroCostDL4Mic (our notebooks). Read more in the [BioImage Model Zoo Docs](https://bioimage.io/docs/#/).

Or test out BioEngine Online demo: [https://bioimage-io.github.io/bioengine-web-client/](https://bioimage-io.github.io/bioengine-web-client/) where you can run most of the models from BioImage Model Zoo.
