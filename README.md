# LapiscoTraining

Este repositório contém uma série de questões sobre processamento digital de imagens e machine learning.
As pastas de cada questão possuem o enunciado da questão bem como a resolução na linguagem python e os arquivos
necessários para rodar o script.

## Requisitos
Para instalar todas as bibliotecas necessárias execute no terminal (no mesmo diretório do projeto) o seguinte comando:
pip install -r requirements.txt

## Questões

| Question | Description |
|---|---|
|01| Abrir uma imagem colorida, visualizar e salvar |
|02| Abrir uma imagem colorida, transformar em níveis de cinza, visualizar e salvar imagem gerada. | 
|03| Abrir uma imagem colorida em RGB, visualizar e salvar cada um dos canais separadamente. Obs: Busquem compreender o que significa cada um dos canais. |
|04| 	Abrir uma imagem colorida, transformar em HSV, visualizar e salvar cada um dos canais separadamente. Obs: Busquem compreender o que significa cada um dos canais.
|05| Abrir uma imagem colorida, transformar em tom de cinza, visualizar imagem de entrada. Apliquem os filtros passa baixa mediana (cv_median) e media (cv_blur), visualizem os resultados e salvem. Obs: Busquem compreender os resultados de cada filtro. |
|06| Abrir uma imagem colorida, transformar em tom de cinza, visualizar imagem de entrada. Apliquem os filtros passa alta de canny (cv_canny), visualizem os resultados e salvem. Obs: Busquem compreender os resultados do filtro. |
|07| Abrir uma imagem colorida, transformar em tom de cinza, visualizar imagem de entrada. Apliquem uma limiarização (thresholding), visualizem os resultados e salvem. Obs: Busquem compreender os resultados da técnica. |
|08| Abrir uma imagem colorida, transformar em tom de cinza, visualizar imagem de entrada. Apliquem um redimensionamento da imagem, reduzindo e depois aumentando seu tamanho, visualizem os resultados e salvem. Obs: uma imagem 320x240 deve virar uma 160x120 em primeiro caso e 640x480 em segundo caso.| 
|09| Abrir uma imagem colorida, transformar em tom de cinza, visualizar imagem de entrada. Criem uma matriz de forma estática com as mesmas dimensões da imagem de entrada (vejam nas propriedades da imagem no Windows), peguem cada um dos pixels da imagem e coloquem na matriz que criaram. Imprimam esta matriz em um arquivo de texto (.txt) do mesmo modo que ela está alocada. |
|10| Abrir uma imagem colorida, transformar em tom de cinza, visualizar imagem de entrada. Criem uma matriz de forma estática com as mesmas dimensões da imagem de entrada (vejam nas propriedades da imagem no Windows), peguem cada um dos pixels da imagem e coloquem na matriz que criaram. Apliquem uma limiarização fazendo uma varredura na matriz. Imprimam esta matriz em um arquivo de texto (.txt) do mesmo modo que ela está alocada. |
