# Projeto de Classificação de Ranking de potencial de engajamento de um post de imagem do instagram 

Repositório referente ao projeto semestral de ciência de dados, da matéria ECM514, cujo objetivo é gerar um modelo de ML que tenha a capacidade de classificar uma imagem em uma nota de potencial de engajamento se postada no instagram.

---
## Nomes:
Felipe Matos Silvieri       RA: 20.00314-5
Gabriel dos Santos Couto    RA: 20.00273-4
Gabriel Prande Bernardello  RA: 20.01288-8

Link do Vídeo:

https://youtu.be/Fzoi89C6ONo

![image](https://github.com/user-attachments/assets/19547508-5d18-4607-affd-5ec22e039ea0)

![image](https://github.com/user-attachments/assets/38898d0d-3d06-41c1-99f5-8343dfbf1f25)

---
## Tutorial de Funcionamento:
Basicamente pra ter acesso às funcionalidades do projeto, é só rodar o .ipynb que está neste repositório, e também no link abaixo, via google colab, e os downloads dos dados, imagens, as instalações de bibliotecas e dependências ja serão realizados automaticamente

---
# Escopo do projeto

## Introdução

Este projeto visa desenvolver um modelo de Machine Learning capaz de prever o potencial de engajamento de imagens no Instagram. Para isso, utilizaremos uma Rede Neural Convolucional (CNN), que é uma técnica eficaz em tarefas de classificação de imagens, para classificar o potencial de engajamento de uma imagem em uma escala de notas (de 1 a 5, por exemplo).

## Contexto

Com o crescimento das redes sociais, o engajamento tornou-se uma métrica fundamental para medir o impacto e a relevância do conteúdo. No Instagram, o engajamento de uma postagem (como uma imagem) depende de diversos fatores, incluindo a qualidade visual, a popularidade do perfil e as preferências dos seguidores. Compreender quais características contribuem para o aumento de engajamento é de interesse tanto para criadores de conteúdo quanto para analistas de mídia social.

## Desafio

Classificar o potencial de engajamento de imagens no Instagram é um desafio, pois envolve características visuais complexas que podem influenciar a interação dos usuários. Além disso, perfis diferentes apresentam escalas de engajamento variadas, o que requer um processo de normalização dos dados para garantir comparabilidade entre as imagens.

## Metodologia

A metodologia deste projeto envolve várias etapas:

- Coleta de Dados: Utilizaremos uma ferramenta externa chamada Apify para realizar o web scraping de perfis no Instagram. Coletaremos dados de imagens, número de curtidas, comentários e metadados como data de postagem e aspect ratio.
- Processamento dos Dados: Calcularemos uma métrica de engajamento com base nas curtidas e comentários, e faremos a normalização dos dados para garantir uma escala uniforme entre perfis.
- Treinamento e Avaliação do Modelo: Usaremos uma CNN para classificar as imagens de acordo com seu potencial de engajamento. Modelos pré-treinados serão ajustados e utilizados para melhorar a precisão do modelo.
- Implementação: O modelo será implementado em uma interface interativa utilizando ferramentas como Streamlit e Google Colab, para facilitar a visualização e teste dos resultados.

## Justificativa

A previsão de engajamento é uma área de crescente interesse em ciência de dados aplicada ao marketing digital. Esse projeto visa contribuir para esse campo, desenvolvendo uma ferramenta que permita aos criadores e analistas de conteúdo entenderem melhor os fatores visuais que impactam o engajamento das postagens.

----
## Conclusão

Embora o modelo tenha apresentado um desempenho insatisfatório, o projeto trouxe insights valiosos que evidenciam a importância de analisar cenários complexos, onde a ausência de um resultado positivo é, por si só, um aprendizado. Este caso se assemelha à previsão de ações, já que fatores externos e aleatórios desempenham um papel significativo na viralização de uma imagem na internet. Além disso, o nicho escolhido, focado em fotografia da natureza, apresentou uma uniformidade elevada na qualidade das imagens, um fator que provavelmente influencia menos a performance das publicações do que outros elementos contextuais. Para avanços futuros, sugerimos incluir o perfil do usuário como variável preditora (via one-hot encoding), expandir o volume de dados e explorar variáveis adicionais que possam captar melhor os fatores externos que afetam o engajamento.
