# Fungi Recognition Models / Supplementary Material


This repository contains the models from our winning submission to the Kaggle [FGVCx Fungi Classification Challenge](https://www.kaggle.com/c/fungi-challenge-fgvc-2018) and our WACV 2020 paper. If you use the models, please cite this paper.

---
      Fungi Recognition: A Practical Use Case.
      M. Sulc, L. Picek, J. Matas, T. Jeppesen, J. Heilmann-Clausen.
      2020 IEEE Winter Conference on Applications of Computer Vision (WACV), 2020.
---




In order to support research in fine-grained species classification and to allow full reproducibility of our results,
we share the *pre-trained Inception-v4 and Inception-ResNet-v2* CNN models trained for the FGVCx Fungi Classification Challenge, organized with the [FGVC5 Workshop at CVPR 2018](https://sites.google.com/view/fgvc5/home).


## Usage
The models are shared in the form of TensorFlow checkpoints, and can be used directly within the [TensorFlow slim](https://github.com/tensorflow/models/tree/master/research/slim") framework. Information about the model parameters are described in the (above) WACV 2020 paper.


## Models:
[Inception Resnet V2 fine-tuned from ImageNet-pretrained checkpoint](http://ptak.felk.cvut.cz/personal/sulcmila/models/fgvc_fungi2018_final/inception_resnet_v2_imagenet/)

[Inception Resnet V2 fine-tuned from PlantCLEF-pretrained checkpoint](http://ptak.felk.cvut.cz/personal/sulcmila/models/fgvc_fungi2018_final/inception_resnet_v2_plantclef/)

[Inception V4 fine-tuned from ImageNet-pretrained checkpoint](http://ptak.felk.cvut.cz/personal/sulcmila/models/fgvc_fungi2018_final/inception_v4_imagenet/)

[Inception V4 fine-tuned from PlantCLEF-pretrained checkpoint](http://ptak.felk.cvut.cz/personal/sulcmila/models/fgvc_fungi2018_final/inception_v4_plantclef/)

[Inception V4 with double input size fine-tuned from ImageNet-pretrained checkpoint](http://ptak.felk.cvut.cz/personal/sulcmila/models/fgvc_fungi2018_final/inception_v4_x2_imagenet/)

[Inception V4 with double input size fine-tuned from PlantCLEF-pretrained checkpoint](http://ptak.felk.cvut.cz/personal/sulcmila/models/fgvc_fungi2018_final/inception_v4_x2_plantclef/)


## License
The models are licensed by the [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/),
i.e.: The models are shared only for non-commercial purposes.
If you publish experiments/results based on the models, please attribute us by citing the (above) WACV paper.
