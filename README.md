<p align="center">
    <img width="200" src="https://cdn-icons-png.flaticon.com/512/1040/1040230.png">
</p>

# 📉 Challenge Telecom X - Análise de Evasão de Clientes

> ℹ️ **NOTA:** Projeto desenvolvido como desafio de dados com foco em análise exploratória e estratégias de retenção para a empresa fictícia *Telecom X*.

---

## 📌 Propósito da Análise

O objetivo do projeto é investigar o alto índice de evasão de clientes (churn) da Telecom X, identificando padrões de comportamento, fatores de risco e oportunidades de melhoria nos serviços e relacionamento com o cliente.

Esta análise tem como metas:

- Entender o perfil dos clientes que mais cancelam os serviços.
- Avaliar o impacto de tipo de contrato, forma de pagamento e serviços contratados no churn.
- Criar métricas personalizadas (como gasto diário) para novas interpretações.
- Fornecer recomendações estratégicas baseadas em dados reais.

---

## 📊 Exemplos de Gráficos e Insights

- **Churn por Tipo de Contrato**  
  Contratos mensais têm maior taxa de cancelamento.  
  ✳️ Sugerido incentivo para migração a contratos anuais.

- **Churn por Forma de Pagamento**  
  Pagamentos manuais por boleto estão ligados a maior evasão.  
  ✳️ Sugerido estímulo a métodos automáticos.

- **Churn por Tempo de Contrato**  
  Clientes com menos de 1 ano de serviço cancelam mais.  
  ✳️ Recomendado um programa de fidelização inicial.

- **Churn por Conta Diária**  
  Clientes com gastos diários mais altos tendem a cancelar mais.  
  ✳️ Analisar percepção de custo-benefício e oferecer planos personalizados.

---

## 💻 Tecnologias Utilizadas

🔹 **Linguagem de Programação**  
- Python → Análise, tratamento e visualização de dados

🔹 **Bibliotecas**  
- Pandas → Manipulação de dados  
- NumPy → Cálculos e arrays  
- Seaborn & Matplotlib → Visualização de gráficos  
- Requests → Requisição de dados via API

🔹 **Ambiente de Desenvolvimento**  
- Google Colab → Execução do projeto e análise interativa

🔹 **Controle de Versão**  
- Git & GitHub → Versionamento e compartilhamento do projeto

---

## ✨ Como Foi Feito?

### 1. **Extração dos Dados**
- Dados extraídos via API do GitHub (formato JSON).
- Conversão direta para DataFrame do Pandas.

### 2. **Limpeza e Tratamento**
- Remoção de colunas irrelevantes.
- Preenchimento de valores nulos.
- Expansão de colunas aninhadas (JSON estruturado).
- Conversão de variáveis categóricas para análise.

### 3. **Transformação**
- Criação da métrica `Contas_Diarias` (valor mensal / 30).
- Categorização de tempo de contrato (`Faixa_Tempo`).
- Conversão de churn e serviços para formato binário.

### 4. **Análise Exploratória (EDA)**
- Visualização da distribuição de churn.
- Gráficos de comparação por contrato, pagamento, tempo, serviços e gasto.
- Cálculo de correlações entre variáveis com heatmap.

### 5. **Relatório Final**
- Markdown estruturado com explicação do desafio, passos realizados e recomendações.
- Dados prontos para alimentar futuros modelos de machine learning.

---

## 🚀 Resultado

Com base na análise dos dados da Telecom X, foram encontrados padrões claros:

✅ Contratos mensais têm maior risco de evasão.  
✅ Pagamentos manuais indicam maior chance de cancelamento.  
✅ Clientes novos e com altos gastos diários merecem atenção especial.  
✅ A métrica de quantidade de serviços também influencia no churn.  

🔁 Esses insights permitem estratégias de retenção mais eficientes e servem de base para modelagem preditiva.

---

## 🧠 Recomendação

➡️ Criar campanhas para migração de contrato mensal para anual.  
➡️ Oferecer descontos ou benefícios para clientes que usam boleto.  
➡️ Desenvolver ações de fidelização nos 12 primeiros meses.  
➡️ Monitorar clientes com alto valor de fatura e personalizar ofertas.  

---

## 👩‍💻 Desenvolvedora

<p>
  <img align="left" width="80" src="https://github.com/jenifferteixeira/natty-or-not/blob/main/assets-git/1707272285584.jpg">
</p>

&nbsp;&nbsp;&nbsp;Jeniffer Teixeira  
&nbsp;&nbsp;&nbsp;[GitHub](https://github.com/jenifferteixeira) | [LinkedIn](https://www.linkedin.com/in/dev-jeniffer-teixeira/)

---

⌨️ com 💙 por [Jeniffer Teixeira](https://www.linkedin.com/in/dev-jeniffer-teixeira/)
