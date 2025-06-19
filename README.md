# Projeto – DCGAN

Este repositório contém um projeto implementado em Python utilizando **DCGAN (Deep Convolutional Generative Adversarial Network)** para geração de imagens.

## 📄 Referência do Paper

A arquitetura utilizada é baseada no artigo:

- **"Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks"** – Alec Radford, Luke Metz, Soumith Chintala  
  📎 [Leia o paper no arXiv](https://arxiv.org/pdf/1511.06434)

## Autor

- **Carlos Alexandre Silva dos Santos**  
  Matrícula: 20210025904

## 🧠 Descrição

O projeto explora a arquitetura de uma DCGAN, explicando passo a passo:

- **Arquitetura do Gerador**: Rede neural convolucional responsável por gerar imagens sintéticas.  
- **Arquitetura do Discriminador**: Rede neural convolucional responsável por distinguir imagens reais de imagens geradas.  
- **Download e Preparação dos Dados**: Etapas para obtenção e pré-processamento do conjunto de imagens utilizado para treinar a GAN.  
- **Treinamento da Rede**: Scripts para treinamento do discriminador e do gerador, cálculo de perdas (`d_loss` e `g_loss`), e visualização de amostras geradas durante o processo.

## 🧩 Estrutura do Notebook

O notebook está organizado nas seguintes seções:

1. **Introdução e Informações do Autor**  
2. **Definição da Arquitetura da DCGAN**  
   - Gerador  
   - Discriminador  
3. **Carregamento e Preparação dos Dados**  
4. **Construção dos Modelos**  
5. **Treinamento**  
6. **Visualização de Resultados**

