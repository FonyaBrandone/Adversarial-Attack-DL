## Multi-defense framework against adversarial attacks on deep learning medical imaging models

![Adversarial Attack](Picture1-DL.png)

### Introduction:
Adversarial attacks on medical imaging pose a significant threat to the reliability of deep learning models for medical imaging. These attacks exploit vulnerabilities in these models by manipulating input data, leading to misclassifications and incorrect diagnoses. Building and evaluating deep learning models that are very robust to complex adversarial attacks (like Carlini-Wagner, DeepFool and PGD) will improve medical diagnosis and increase the generalizability of existing defense strategies.

_This work implements a multi-defense framework combining adversarial training on DeepFool(DF), projected gradient descent (PGD) and feature squeezing(bit-depth reduction and Gaussian blurring of the input image)  to enhance the robustness of both ResNet-18 and VGG-16 deep learning models against DF and PGD attacks, on the Breast cancer histopathology  dataset as case study._

#### _(Paper link will be available soon!)_

### Requirements
- Python 3.8+

- PyTorch

- Torchvision

- Foolbox

- Matplotlib

- NumPy