# 🖐️ Reconhecimento de Letras em Libras com Visão Computacional  

Este repositório contém um projeto baseado no vídeo de [Phillip](https://www.youtube.com/watch?v=MJCSjXepaAM), que utiliza visão computacional para capturar, processar e classificar gestos de letras em Libras (Língua Brasileira de Sinais) usando a biblioteca MediaPipe e um classificador Random Forest.  

## 📌 Funcionalidades  

✅ **Coleta de Dados** – Captura imagens de gestos de mão e cria um dataset.  
✅ **Processamento de Mãos** – Usa MediaPipe para detectar e extrair landmarks da mão.  
✅ **Treinamento de Modelo** – Treina um classificador Random Forest para reconhecer gestos.  
✅ **Inferência em Tempo Real** – Detecta e exibe letras em Libras via webcam.  

## 🛠️ Tecnologias Utilizadas  

- OpenCV  
- MediaPipe  
- Scikit-Learn  
- Matplotlib  
- Pickle  

## 📂 Estrutura do Projeto  

📁 `Libras.ipynb` → Captura e armazena imagens para o dataset.  
📁 `Cria_dataset.ipynb` → Processa imagens e extrai landmarks das mãos.  
📁 `treina_classificador.ipynb` → Treina o modelo de classificação.  
📁 `classificação_por_inferencia.ipynb` → Realiza a inferência em tempo real.  

## 🚀 Como Usar  

1. **Captura de Dados:**
   - Execute o script `Libras.ipynb` para capturar imagens dos gestos que deseja classificar.
   
2. **Processamento de Imagens:**
   - Execute o script `Cria_dataset.ipynb` para extrair os dados das mãos e salvar em um arquivo `.pickle`.

3. **Treinamento do Modelo:**
   - Execute o script `treina_classificador.ipynb` para treinar o modelo de classificação e salvar o modelo treinado.

4. **Classificação em Tempo Real:**
   - Execute o script `classificação_por_inferencia.ipynb` para classificar gestos em tempo real usando a webcam.

## Requisitos

- Python 3.x
- Bibliotecas: OpenCV, MediaPipe, Scikit-learn, NumPy, Matplotlib, Pickle

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias no código, documentação ou novas funcionalidades.

## Referências

- Vídeo de Philip: [https://www.youtube.com/watch?v=MJCSjXepaAM](https://www.youtube.com/watch?v=MJCSjXepaAM)
- Documentação do MediaPipe: [https://google.github.io/mediapipe/](https://google.github.io/mediapipe/)
- Documentação do OpenCV: [https://opencv.org/](https://opencv.org/)

Este repositório é uma implementação prática de visão computacional e aprendizado de máquina para reconhecimento de gestos, com foco na acessibilidade e inclusão através da Libras.
