# 💳 Análise de Cancelamento de Cartões de Crédito: Perfis, Comportamento e Fatores de Churn

![AnaliseCartão4](https://github.com/user-attachments/assets/f8c648ad-8f65-468d-8b6c-b426b9208fef)
![AnaliseCartão2](https://github.com/user-attachments/assets/d7983fc9-fab5-4aa4-b58c-c9bb77e04a3e)




Este projeto investiga dados de clientes de uma grande empresa de cartões de crédito para entender os principais motivos que levam ao cancelamento do cartão (churn). A análise foi realizada no Google Colab utilizando **Python, Pandas e Plotly**.

---

## 🎯 Problemas Resolvidos na Análise


- **Quais fatores influenciam o cancelamento?**  
  Avaliação do impacto da inatividade, volume de transações e contatos com a empresa.

- **Como prevenir o cancelamento?**  
  Sugestões baseadas em dados para reduzir a taxa de churn.

---

## 📊 Base de Dados

O conjunto de dados contém informações de **10.126 clientes** com as seguintes colunas principais:

- `Categoria` — Cliente ativo ou Cancelado  
- `Idade` — Idade do cliente  
- `Sexo` — Gênero  
- `Dependentes` — Número de dependentes  
- `Educação` — Grau de escolaridade  
- `Estado Civil` — Estado civil  
- `Faixa Salarial Anual` — Renda estimada  
- `Categoria Cartão` — Tipo do cartão (ex: Blue, Silver)  
- `Meses como Cliente` — Tempo de relacionamento  
- `Produtos Contratados` — Quantidade de produtos financeiros ativos  
- `Inatividade 12m` — Número de meses sem uso do cartão no último ano  
- `Contatos 12m` — Número de contatos com a empresa no último ano  
- `Limite` — Limite total do cartão  
- `Limite Consumido` — Valor utilizado do limite  
- `Taxa de Utilização Cartão` — Proporção do limite utilizado

---

## 🔍 Principais Resultados

### ✅ Perfil dos Clientes com Maior Risco de Cancelamento

| Variável           | Observação                                           |
|--------------------|-----------------------------------------------------|
| Categoria Cartão    | Maioria dos cancelamentos na categoria Blue         |
| Contatos 12m       | Aumento no número de contatos correlaciona com maior chance de cancelamento |
| Taxa de Utilização  | Clientes com baixa utilização do cartão têm maior probabilidade de churn |

🎯 **Resultado:** O cliente que cancela geralmente tem baixo uso do cartão e faz mais chamadas ao atendimento.


---

## 🛠️ Tecnologias Utilizadas

- **Python 3**  
- **Pandas**  
- **Plotly Express**  
- **Google Colab / Jupyter Notebook**

---

## 💡 Conclusão

A análise indica que para reduzir o churn é fundamental incentivar o uso ativo do cartão e melhorar o atendimento ao cliente para resolver problemas antes que eles levem ao cancelamento. Programas de fidelidade e melhorias no suporte podem ser caminhos eficazes para aumentar a retenção.

