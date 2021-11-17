# Pretrained_Transformers

1. Download a pre-trained ResNet-18 on Imagenet using torchvision
2. Adapt the pre-trained model for CIFAR100 and fine-tuned using SGD (lr=0.1) and
train for 10 epochs with the following configurations
    a. freeze all layers except the first one
    b. freeze all layers except the second one
    c. freeze all layers except the third one
    d. freeze all layers except the fourth one
    e. train using all layers
3. Compare and report your results in a jupyter notebook. You can use the functions
classification_report and confusion_matrix from
https://scikit-learn.org/stable/modules/classes.html#sklearn-metrics-metrics
