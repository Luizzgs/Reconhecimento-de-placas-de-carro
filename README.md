<div align="center">

# Protocolo de processamento de imagens 📷
Código em ***python*** para um sistema de reconhecimento e identificação de placas de carros na disciplina de *Computação Gráfica*.

</div>

---

## Requisitos ⚙️

- ***Python***;
- biblioteca `opencv`;
- ***Tesseract OCR***.

## Construção 📄

<br>

[![PDF](https://img.shields.io/badge/ARTIGO-PDF-purple.svg?logo=Google-Docs&logoColor=f5f5f5&style=for-the-badge)](PDF.pdf)

- **Conversão para Escala de Cinza**
  - Usando OpenCV para converter imagem original para escala de cinza.

- **Morfologia para Aumentar Contraste**
  - Utilização de operações morfológicas como dilatação e erosão para realçar características importantes.

- **Thresholding Adaptativo**
  - Segmentação da imagem em regiões de interesse com limiar localmente adaptativo.

- **Identificação de Contornos**
  - Detecção de contornos na imagem para localizar regiões potenciais de caracteres.

- **Pré-processamento dos Dados**
  - Aplicação de técnicas para transformação e normalização da imagem antes do reconhecimento de caracteres.

- **Seleção de Candidatos pelo Tamanho do Caractere**
  - Filtragem de contornos com base em critérios geométricos como altura, largura e razão de aspecto.

- **Seleção de Candidatos pelo Contorno da Imagem**
  - Análise do formato e estrutura dos contornos para refinar a seleção de candidatos.

- **Rotação de Imagem**
  - Correção de distorção aplicando técnicas de rotação de imagem.

- **Threshold para Seleção de Candidatos**
  - Aplicação de threshold específico para contornos selecionados como candidatos a caracteres.
#
