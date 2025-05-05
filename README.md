# 🌟 Classificador de Imagens CIFAR-10 com Transfer Learning (MobileNetV3)

Este notebook utiliza **Transfer Learning** com **MobileNetV3** para classificar imagens no dataset **CIFAR-10**.

✔️ Treinamento completo com PyTorch  
✔️ Avaliação com métricas de acurácia (torchmetrics)  
✔️ Upload de imagens personalizadas  
✔️ Previsão ao vivo no Google Colab  
✔️ Interface pronta para uso e compartilhamento

## 🚀 Executar no Google Colab

Clique abaixo para abrir o notebook em um ambiente interativo:

[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ds-kenwatanabe/cifar10-image-classifier/blob/main/CIFAR10_CNN_transfer_learning_ptbr.ipynb)

> O notebook será clonado automaticamente — você poderá **testar com suas imagens** sem precisar instalar nada.

---

## 🖼️ Exemplo de uso

1. Faça upload de uma imagem (`.png` ou `.jpg`)
2. O modelo faz a previsão da classe entre:
   `avião`, `automóvel`, `pássaro`, `gato`, `cervo`, `cachorro`, `sapo`, `cavalo`, `navio`, `caminhão`

---

## 📦 Requisitos

- Google Colab (ambiente já pronto)
- PyTorch
- Torchvision
- Torchmetrics

---

## 📚 Sobre o Transfer Learning

O modelo é baseado no `MobileNetV3 Large`, pré-treinado no ImageNet e ajustado para o CIFAR-10 com 10 classes. A nova camada de classificação foi substituída por uma `Linear(in_features=960, out_features=10)`.

---
