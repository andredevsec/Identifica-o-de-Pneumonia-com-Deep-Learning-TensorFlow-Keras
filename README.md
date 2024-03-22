# Identificação de Pneumonia com Deep Learning usando TensorFlow e Keras

Este é um projeto de identificação de pneumonia em imagens de raio-X de tórax, desenvolvido com [TensorFlow](https://www.tensorflow.org/) e [Keras](https://keras.io/). O modelo foi treinado utilizando o [Teachable Machine](https://teachablemachine.withgoogle.com/) do Google e posteriormente adaptado para permitir que o usuário selecione uma imagem de um pulmão e determine se ele está normal ou se apresenta sinais de pneumonia.

## Visão Geral

A pneumonia é uma infecção comum e potencialmente grave dos pulmões, que pode ser detectada através de radiografias de tórax. Este projeto utiliza técnicas de aprendizado profundo (deep learning) para automatizar a identificação desse quadro a partir de imagens de raio-X.

## Funcionalidades

- **Identificação Automática**: O modelo permite que o usuário forneça o caminho de uma imagem de raio-X de um pulmão e determina se ele está normal ou se apresenta sinais de pneumonia.

## Como Usar

1. **Instalação de Dependências**: Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las executando o comando:

   ```bash
   pip install -r requirements.txt
## Execução do Projeto

Para executar o projeto, siga estas etapas:

1. Abra o arquivo `predict.py`.
2. Defina o caminho da imagem de raio-X que você deseja analisar.
3. Execute o script.

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter as seguintes dependências instaladas:

- [Python 3.x:](https://www.python.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [Keras](https://keras.io/)
- [Pillow](https://python-pillow.org/)

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para [abrir uma issue](../../issues) para relatar problemas ou sugerir melhorias. Se desejar contribuir diretamente, você pode fazer um fork deste repositório, fazer as alterações e enviar um [pull request](../../pulls).

## Créditos

Este projeto foi desenvolvido por [André Luiz de Lima](https://github.com/andredevsec).
