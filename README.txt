1. KNN-MLP-CNN: Notebook for CIFAR-10 Classification using KNN, Single and Double Hidden Layer MLPs and a CNN
Preprocessing: PCA (KNN, MLPs), Feature Scaling (MLPs, CNNs), Image Augmentations (CNNs)
Parameters Tested: NN depth, Neurons/Layer, Dropout
Metrics Used: Train/Test Accuracy, Training Time, Efficiency (Acc/Train time)
Tools Used: scikit-learn, TensorFlow

2. SVM: Notebook for CIFAR-10 Classification using different types of SVMs
Preprocessing: PCA, Feature Scaling
Parameters Tested: Kernel (RBF, Linear, Polynomial), Gamma (RBF, Polynomial), C (All), Degree (Polynomial)
Metrics Used: Train/Test Accuracy - Comparison with KNN
Tools Used: scikit-learn

3. PytorchIntro: Introduction to Pytorch - Module, Sequential and Custom Models
Preprocessing: Batch Sampling, Feature Normalization
Parameters Tested: - (No parameter Tuning)
Metrics Used: - (No actual training and optimization)
Tools Used: Pytorch, Torchvision, CUDA (GPU Training)

4. PytorchCNNs: Notebook for CIFAR-10 Classification using different types of CNNs
Preprocessing: Batch Sampling, Feature Normalization, Image Augmentations
Parameters Tested: Layer Architectures, Layer Neurons, Padding, Dropout/Batch Normalization, Kernel, Pooling, Data Augmentation 
Tools Used: Pytorch, Torchvision, CUDA (GPU Training)