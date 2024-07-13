# Classificação de Imagens com Redes Neurais Convolucionais e Otimização de Hiperparâmetros usando Keras Tuner

Este repositório contém o código e o artigo relacionados ao projeto de classificação de imagens dos personagens Homer e Bart da série animada "Os Simpsons", utilizando Redes Neurais Convolucionais (CNNs) e Keras Tuner para a otimização de hiperparâmetros.

## Resumo

Neste projeto, construímos e treinamos uma CNN para a tarefa de classificação de imagens. Utilizamos técnicas de pré-processamento de imagem com OpenCV, incluindo normalização de intensidade e realce de bordas, além de métodos para evitar overfitting, como Dropout, Regularização L2 e Early Stopping. A otimização de hiperparâmetros foi realizada com o Keras Tuner, utilizando algoritmos como Random Search, Hyperband e Bayesian Optimization. O modelo alcançou uma precisão de 0.875 em dados de teste, demonstrando sua eficácia e robustez para tarefas de classificação em visão computacional.

## Estrutura do Projeto

- `documento.tex`: Arquivo principal do artigo em LaTeX.
- `referencias.bib`: Arquivo contendo as referências bibliográficas utilizadas no artigo.
- `imagens/`: Diretório contendo as imagens utilizadas no artigo, incluindo gráficos de matriz de confusão e curvas de acurácia e erro.
- `codigo/`: Diretório contendo o código utilizado para construir e treinar a CNN, incluindo os scripts de pré-processamento e otimização de hiperparâmetros.

## Pré-requisitos

Para compilar o documento LaTeX e executar os códigos, você precisará das seguintes ferramentas:

- [LaTeX](https://www.latex-project.org/get/)
- [Python](https://www.python.org/downloads/)
- Bibliotecas Python:
  - `tensorflow`
  - `keras-tuner`
  - `opencv-python`
  - `numpy`
  - `matplotlib`

## Como Compilar o Documento

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   
Compile o documento LaTeX utilizando seu editor LaTeX preferido ou via linha de comando:
pdflatex documento.tex
biber documento
pdflatex documento.tex
pdflatex documento.tex

Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

Licença
Este projeto está licenciado sob a Licença MIT. 

Contato
Para mais informações, entre em contato com wagner.v.lopes@gmail.com



