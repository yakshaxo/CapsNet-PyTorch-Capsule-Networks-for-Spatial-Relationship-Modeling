CapsNet-PyTorch
A streamlined implementation of Capsule Networks (CapsNets) using PyTorch.

Traditional Convolutional Neural Networks (CNNs) often struggle with spatial orientation—they might recognize a face even if the eyes and mouth are swapped. CapsNets solve this by using Dynamic Routing to preserve the hierarchical relationships between features.

🚀 Key Features
Spatial Awareness: Better at identifying objects regardless of rotation or scale.

Dynamic Routing: Implements the routing-by-agreement algorithm (Sabour et al., 2017).

Modular Design: Easy-to-read code designed for experimentation on MNIST and similar datasets.

🛠️ Quick Start
1. Installation
Clone the repo and install the requirements:

Bash
git clone https://github.com/yakshaxo/capsnet.git
cd capsnet
pip install -r requirements.txt
2. Training
Start training with default parameters:

Bash
python train.py
3. Evaluation
Test your trained model's accuracy:

Bash
python evaluate.py --model_path ./path_to_model.pth
📈 Performance
CapsNet is designed to achieve high accuracy on MNIST (~99%) while requiring significantly less data to understand spatial variances compared to standard CNNs.

📖 Reference
This project is based on the paper:
Sabour, Sara, Nicholas Frosst, and Geoffrey E. Hinton. "Dynamic routing between capsules." Advances in neural information processing systems 30 (2017).

Maintained by krayem louay


