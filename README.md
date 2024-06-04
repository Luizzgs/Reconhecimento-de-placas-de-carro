<div align="center">

# Protocolo de processamento de imagens 📷
Sistema de reconhecimento automático de caracteres em placas de carros, desenvolvido utilizando *Python*, *Tesseract* e *OpenCV*. O sistema é capaz de processar imagens de placas de carros, identificar os caracteres nelas contidos e convertê-los em texto legível.

</div>

---

## Requisitos ⚙️

- ***Python***;
- biblioteca `opencv`;
- ***Tesseract OCR***.

## Funcionalidades Principais 🔧

- **Pré-processamento de Imagens:** Conversão para escala de cinza, aplicação de técnicas morfológicas para aumento de contraste e thresholding adaptativo.
- **Segmentação da Imagem:** Detecção de bordas, aplicação de máscaras, divisão em regiões e isolamento de caracteres.
- **Interpretação da Imagem:** Reconhecimento óptico de caracteres (OCR), correção de inclinação e normalização, filtragem de ruído e pós-processamento dos resultados.

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
