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

1️⃣ Clone este repositório:  
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
