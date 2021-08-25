## Explaining in Style: Official TensorFlow Colab

**Explaining in Style: Training a GAN to explain a classifier in
StyleSpace**<br>
Oran Lang, Yossi Gandelsman, Michal Yarom, Yoav Wald, Gal Elidan, Avinatan
Hassidim, William T. Freeman, Phillip Isola, Amir Globerson, Michal Irani and
Inbar Mosseri.<br>

Paper: https://arxiv.org/abs/2104.13369

Abstract:
*Image classification models can depend on multiple different semantic attributes
of the image. An explanation of the decision of the classifier needs to both
discover and visualize these properties. Here we present StylEx, a method for
doing this, by training a generative model to specifically explain multiple
attributes that underlie classifier decisions. A natural source for such
attributes is the StyleSpace of StyleGAN, which is known to generate
semantically meaningful dimensions in the image. However, because standard GAN
training is not dependent on the classifier, it may not represent these
attributes which are important for the classifier decision, and many dimensions
of StyleSpace may represent irrelevant attributes. To overcome this, we propose
a training procedure for a StyleGAN, which incorporates the classifier model, in
order to learn a classifier-specific StyleSpace. Explanatory attributes are then
selected from this space. These can be used to visualize the effect of changing
multiple attributes per image, thus providing image-specific explanations. We
apply StylEx to multiple domains, including animals, leaves, faces and retinal
images. For these, we show how an image can be modified in different ways to
change its classifier output. Our results show that the method finds attributes
that align well with semantic ones, generate meaningful image-specific
explanations, and are human-interpretable as measured in user-studies. *

## About this colab

Use this colab to load the weights of a pre-trained StyleGAN2 model trained on
age classifier, and to find and manipulate the Style indices which correspond to
the most important attributes for this classifier. The colab has an
implementation of the AttFind algorithm from the paper, and has utilities to
visualize these attributes.

## License

This colab is licensed under the terms of the Apache license. See [LICENSE](LICENSE)
for more information.

## Mandatory Disclaimer

This is not an officially supported Google product.



