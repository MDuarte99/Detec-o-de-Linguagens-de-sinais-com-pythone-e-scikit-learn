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

2️⃣ Clone este repositório:
```bash
  pip install -r requirements.txt

3️⃣ Execute os notebooks na ordem:
Libras.ipynb → Para capturar os dados.
Cria_dataset.ipynb → Para processar e gerar o dataset.
treina_classificador.ipynb → Para treinar o modelo.
classificação_por_inferencia.ipynb → Para testar a inferência em tempo real.
📌 Observações
Certifique-se de que sua câmera está conectada corretamente.
Ajuste os parâmetros de detecção conforme necessário.
O modelo atual reconhece apenas as letras A, B e L, mas pode ser expandido.
🎯 Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar PRs.

📢 Feito com ❤️ para facilitar a comunicação em Libras!
