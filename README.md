Previsão de Preços de Casas
📌 Objetivo

Prever o preço de casas com base em características como área, número de quartos e localização, utilizando regressão linear.

📂 Dataset
Fonte: Boston Housing Dataset

Descrição: contém informações sobre casas em Boston, incluindo variáveis como número de quartos, idade do imóvel, taxa de criminalidade, distância até centros de emprego e preço mediano das casas (target).

Tipo de problema: Regressão

🛠 Tecnologias e Bibliotecas

Python

Pandas

NumPy

Matplotlib / Seaborn

scikit-learn

⚙ Metodologia

Exploração dos dados: análise de estatísticas descritivas, gráficos de distribuição e correlações entre variáveis.

Pré-processamento: verificação e tratamento de valores nulos, padronização de variáveis numéricas e separação entre features e target.

Construção do modelo: aplicação de Regressão Linear utilizando scikit-learn.

Avaliação: métricas usadas:

Mean Squared Error (MSE)

R² Score
Comparação entre valores previstos e reais para avaliar a precisão do modelo.

Conclusão: insights sobre quais variáveis impactam mais o preço e possibilidades de melhoria do modelo (ex.: usar regularização, testar outros algoritmos de regressão).

📊 Resultados (Exemplo)

R² Score: 0.82

MSE: 22.5

Observação: o modelo conseguiu capturar bem a tendência geral dos preços das casas. Variáveis como número de quartos e localização foram determinantes para a previsão.
