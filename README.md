# Using Convolutional Neural Networks for Hierarchical Grocery Store Product Classification

By [Arren Matthew C. Antioquia](https://arvention.github.io/) at [De La Salle University](https://www.dlsu.edu.ph/)

This work was accepted in [PCSC 2021](https://sites.google.com/view/pcsc-2021).

## Abstract
Convolutional Neural Networks have been used to solve various computer vision problems due to its success in classifying common objects. These models are now being adapted to numerous products and devices, including visual support systems which provide assistance to people with visual impairments. These systems help by reading texts, recognizing people, and describing scenes, among others. However, these products do not have capability to provide visual support in certain scenarios performed regularly, such as grocery shopping. In this work, we adapt various modern Convolutional Neural Networks to develop classifiers for common grocery store products such as fruits, vegetables, and various refrigerated products. We train the classification architectures on a hierarchical grocery store dataset with fine-grained and coarse-grained labels. Our implementation achieves superior classification accuracy on the Grocery Store dataset, with 86.04% and 91.99% on the fine-grained and coarse-grained labels, respectively, exhibiting dominant performance against current state-of-the-art classification methods.

## Results
|    Network   | Reported<br>in | Classifier | Fine-Tuned | Parameter<br>Count | Fine-Grained<br>Test Accuracy | Coarse-Grained<br>Test Accuracy |
|:------------:|:-----------:|:----------:|:----------:|:----------------:|:--------------------------:|:----------------------------:|
|    [AlexNet](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)   | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |     SVM    |            |        58M       |           65.00%           |            75.40%            |
|    [AlexNet](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)   | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |     SVM    |      ✔     |        58M       |           70.70%           |               -              |
|   [VGGNet-16](https://arxiv.org/pdf/1409.1556.pdf)  | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |     SVM    |            |       135M       |           57.30%           |            72.80%            |
|   [VGGNet-16](https://arxiv.org/pdf/1409.1556.pdf)  | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |     SVM    |      ✔     |       135M       |           71.70%           |               -              |
| [DenseNet-169](https://arxiv.org/pdf/1608.06993.pdf) | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |     SVM    |            |        13M       |           72.50%           |            85.20%            |
| [DenseNet-169](https://arxiv.org/pdf/1608.06993.pdf) | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |     SVM    |      ✔     |        13M       |           85.00%           |               -              |
|    [AlexNet](https://papers.nips.cc/paper/2012/file/c399862d3b9d6b76c8436e924a68c45b-Paper.pdf)   | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |   Softmax  |      ✔     |        58M       |           69.30%           |               -              |
|   [VGGNet-16](https://arxiv.org/pdf/1409.1556.pdf)  | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |   Softmax  |      ✔     |       135M       |           73.80%           |               -              |
| [DenseNet-169](https://arxiv.org/pdf/1608.06993.pdf) | [Other Paper](https://arxiv.org/pdf/1901.00711.pdf) |   Softmax  |      ✔     |        13M       |           84.00%           |               -              |
|   [VGGNet-16](https://arxiv.org/pdf/1409.1556.pdf)  |     Ours    |   Softmax  |      ✔     |       135M       |           80.60%           |            89.09%            |
|   [VGGNet-19](https://arxiv.org/pdf/1409.1556.pdf)  |     Ours    |   Softmax  |      ✔     |       140M       |           81.81%           |            87.36%            |
|   [ResNet-34](https://arxiv.org/pdf/1512.03385.pdf)  |     Ours    |   Softmax  |      ✔     |        21M       |           78.39%           |            86.16%            |
|   [ResNet-50](https://arxiv.org/pdf/1512.03385.pdf)  |     Ours    |   Softmax  |      ✔     |        24M       |           85.39%           |            89.58%            |
|  [ResNet-101](https://arxiv.org/pdf/1512.03385.pdf)  |     Ours    |   Softmax  |      ✔     |        43M       |           85.15%           |            89.94%            |
|  [ResNet-152](https://arxiv.org/pdf/1512.03385.pdf)  |     Ours    |   Softmax  |      ✔     |        58M       |           85.67%           |            89.54%            |
| [DenseNet-121](https://arxiv.org/pdf/1608.06993.pdf) |     Ours    |   Softmax  |      ✔     |        7M        |           84.75%           |            89.70%            |
| [DenseNet-169](https://arxiv.org/pdf/1608.06993.pdf) |     Ours    |   Softmax  |      ✔     |        13M       |           85.75%           |            90.54%            |
| [DenseNet-201](https://arxiv.org/pdf/1608.06993.pdf) |     Ours    |   Softmax  |      ✔     |        18M       |           86.04%           |            91.99%            |

## Citation
If you find the code useful, please consider citing our paper using the following BibTeX entry.
```
@inproceedings{Antioquia2021Grocery,
  title={Using Convolutional Neural Networks for Hierarchical Grocery Store Product Classification},
  author={Arren Matthew C. Antioquia},
  booktitle={Proceedings of the 21st Philippine Computing Science Congress},
  year={2021},
}
```
