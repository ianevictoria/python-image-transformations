# Image Processing Pipeline: Grayscale and Binarization

## Descrição

Este repositório contém um projeto desenvolvido em Python para o processamento de imagens, com ênfase em conversão de imagens coloridas para escala de cinza e binarização. Utilizando as bibliotecas **NumPy**, **Pillow (PIL)** e **Matplotlib**, o projeto realiza etapas essenciais para manipulação e análise de imagens, tornando-o uma excelente base para aplicações em áreas como visão computacional, aprendizado de máquina e processamento de imagens.

## Funcionalidades

- **Conversão para escala de cinza:** Imagens coloridas são convertidas para uma versão em níveis de cinza utilizando uma fórmula ponderada baseada na percepção humana.
- **Binarização:** A imagem em escala de cinza é convertida em uma imagem binária, utilizando um valor de limiar configurável.
- **Exibição gráfica:** As imagens originais, em escala de cinza e binarizadas são exibidas lado a lado para comparação visual.
- **Salvamento de imagens:** As imagens processadas são salvas em formato PNG para posterior utilização.

## Tecnologias Utilizadas

- **Python:** Linguagem de programação utilizada para o desenvolvimento do script.
- **NumPy:** Biblioteca para manipulação de arrays, essencial para a conversão e processamento das imagens.
- **Pillow (PIL):** Biblioteca para manipulação de imagens, permitindo a leitura, escrita e transformação das imagens.
- **Matplotlib:** Biblioteca para visualização gráfica, permitindo a exibição das imagens lado a lado.

## Requisitos

Antes de rodar o projeto, é necessário instalar as bibliotecas listadas abaixo:

```bash
pip install numpy pillow matplotlib
