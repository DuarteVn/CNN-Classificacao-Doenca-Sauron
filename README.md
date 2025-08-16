# 🧠 CNN - Classificação da Doença Sauron

Este projeto utiliza Redes Neurais Convolucionais (CNNs) para classificar imagens em positivas ou negativas para a doença fictícia Sauron.
O objetivo é comparar modelos de CNN desenvolvidos do zero com modelos pré-treinados aplicando Fine-Tuning, buscando uma acurácia final > 85%.

🚀 Etapas do Projeto

📂 1. Preparação dos Dados
- Separar o dataset em:
  - 80% treino
  - 10% validação
  - 10% teste
  
- Aplicar Data Augmentation para melhorar a generalização do modelo.

🏗️ 2. Modelagem
 - Construir uma CNN simples com 2 camadas (Convolução + Pooling).
 - Construir uma CNN mais profunda, com mais camadas, para comparar desempenho.

🔧 3. Fine-Tuning
 - Criar um 2º notebook aplicando Transfer Learning.
 - Utilizar um modelo pré-treinado (exceto VGG16).
 - Cada equipe deve escolher um modelo diferente (ResNet, Inception, EfficientNet, etc).

📊 4. Avaliação
- Comparar resultados dos modelos:
- Gráficos de acurácia e perda (treino x validação).
- Tabela com métricas finais.
- Garantir que o melhor modelo atinja acurácia > 85% no dataset de teste.

💾 5. Salvamento
- Salvar o melhor modelo treinado em um arquivo apropriado para reuso.

📌 Resultados Esperados

Comparação entre CNNs simples e profundas.
Fine-tuning com modelo pré-treinado.
Gráficos claros de desempenho.
Modelo final salvo com acurácia mínima de 85%.
