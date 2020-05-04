# Sistema para detectar utilização de máscara com Deep Larning

## Inicio
 - Essa aplicação detecta se uma pessoa está ou nao de máscara.
 - Projeto desenvolvido em Python 3.6, foram utlizadas as bibliotecas Pytorch, Matplotlib, Open-cv e PIL.
 - O modelo de Deep Learning foi treinado com Pytorch utilizando técnica de Transfer-Leraning.
 - Modelo de Transfer-Leraning utilizado (resnet50).
 - Modelo utilizado para capturar face (haarcascade_frontalface_default).

## Recursos utilizados no desenvolvimento:

- jupyter-lab;
- torchvision==0.4.2;
- matplotlib==3.1.1;
- opencv-python==4.2.0.34;
- Pillow==6.2.0;

## Dataset:

- Utilizei esse data set do Kaggle: https://www.kaggle.com/ahmetfurkandemr/mask-datasets-v1
- Baixei algumas imagens do google para complementar.
- Link download do dataset: ` link `.

## Modelo:

- O treinamento e teste do modelo está no jupyter-notebook `detectar_mascara.ipynb`
- Utilizei técnica de transfer-learning com o modelo resnet50
- Exelente artigo sobre transfer-learning: https://towardsdatascience.com/a-comprehensive-hands-on-guide-to-transfer-learning-with-real-world-applications-in-deep-learning-212bf3b2f27a
- Para detectar rosto utilizei um modelo bem leve do openvc, mas pode ser utilizados outros melhores: https://docs.opencv.org/3.4/db/d28/tutorial_cascade_classifier.html
- Deixei na pasta `result` algumas images testando o modelo
- OBS: o modelo está em fase de adaptação e pode ser melhorado utilizando um detector de face mais robusto e criando mais dataset.
- Link download dos pesos: ` link `.

