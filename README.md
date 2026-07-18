# 💰 Dashboard Financeiro

# 📖 Sobre o Projeto

O **Dashboard Financeiro** foi desenvolvido em **Power BI** com o objetivo de fornecer uma visão consolidada da saúde financeira da empresa, transformando dados de recebimentos e pagamentos em informações estratégicas para apoiar a tomada de decisão.

O projeto reúne indicadores financeiros essenciais, permitindo acompanhar receitas, custos, despesas e lucro, além de analisar a evolução financeira ao longo do tempo, distribuição das receitas, composição dos pagamentos e desempenho dos principais clientes.

---

# 🎯 Objetivos

- Monitorar os principais indicadores financeiros da empresa.
- Comparar o desempenho financeiro entre anos.
- Analisar a evolução das receitas ao longo dos meses.
- Acompanhar custos e despesas.
- Identificar os clientes com maior participação na receita.
- Avaliar a composição das receitas e pagamentos.
- Apoiar decisões estratégicas através de indicadores visuais.

---

# 📊 Dashboard

<p align="center">
<img src="https://github.com/pedrolucas-gr/Dashboard-Financeiro/blob/main/Images/Dashboard.png" width="100%">
</p>

O dashboard apresenta uma visão executiva das informações financeiras, permitindo explorar os dados por meio de filtros dinâmicos e visualizações interativas.

### KPIs Monitorados

- 💰 Receita Total
- 💳 Custos
- 📉 Despesas
- 📈 Lucro

### Análises Disponíveis

- Comparativo entre Ano Atual e Ano Anterior
- Receita por Conta
- Top 5 Clientes
- Pagamentos por Tipo
- Pagamentos por Mês
- Custos x Despesas
- Evolução Financeira Mensal

---

# 🛠 Tecnologias Utilizadas

| Tecnologia | Aplicação |
|------------|-----------|
| Power BI | Desenvolvimento do Dashboard |
| Power Query | Tratamento e transformação dos dados |
| DAX | Criação das medidas e indicadores |
| Microsoft Excel | Base de dados |
| Modelagem de Dados | Estruturação do modelo relacional |

---

# 🗂 Modelagem de Dados

<p align="center">
<img src="https://github.com/pedrolucas-gr/Dashboard-Financeiro/blob/main/Images/Modelagem.png" width="90%">
</p>

O modelo foi desenvolvido seguindo boas práticas de modelagem dimensional, permitindo consultas rápidas, indicadores consistentes e facilidade na criação das análises.

## 📄 fRecebimentos

Tabela fato responsável pelos registros das receitas da empresa.

Principais informações:

- Cliente
- Data
- UF
- Conta Contábil
- Valor Recebido

---

## 📄 fPagamentos

Tabela fato responsável pelos pagamentos realizados.

Principais informações:

- Data
- Conta
- Valor Pago

---

## 📄 dPlanoContas

Tabela dimensão responsável pela classificação financeira das movimentações.

Principais informações:

- Conta
- Tipo
- Movimento
- Lançamento

---

## 📄 dCalendario

Tabela dimensão utilizada para análises temporais.

Principais informações:

- Data
- Ano
- Mês
- Número do Mês

---

## 🔗 Relacionamentos

A modelagem relaciona as tabelas de recebimentos e pagamentos ao plano de contas e ao calendário, permitindo análises temporais e financeiras consistentes em todo o dashboard.

---

# 📈 Principais Indicadores

| Indicador | Descrição |
|------------|-----------|
| Receita | Valor total recebido pela empresa |
| Custos | Gastos diretamente relacionados às operações |
| Despesas | Gastos administrativos e operacionais |
| Lucro | Resultado financeiro obtido após dedução dos custos e despesas |

---

# 💡 Insights Gerados

Com o dashboard é possível identificar:

- Evolução mensal das receitas.
- Comparação do desempenho financeiro entre anos.
- Participação das contas operacionais e não operacionais.
- Clientes com maior contribuição para o faturamento.
- Distribuição dos pagamentos entre custos e despesas.
- Composição dos pagamentos fixos e variáveis.
- Tendências de crescimento ou redução dos indicadores financeiros.
- Impacto dos custos sobre o lucro da empresa.

---

# 📂 Estrutura do Projeto

```text
📦 Dashboard-Financeiro
│
├── 📁 BaseDados
│   ├── CadastroPlanoContas.xlsx
│   ├── Pagamentos.xlsx
│
├── 📁 Images
│   ├── Dashboard.png
│   └── Modelagem.png
│
├── Dashboard.pbix
└── README.md
```

---

# 🚀 Como Executar

1. Clone o repositório.

```bash
git clone https://github.com/pedrolucas-gr/Dashboard-Financeiro.git
```

2. Abra o arquivo **Dashboard.pbix** utilizando o **Power BI Desktop**.

3. Caso necessário, atualize o caminho das bases de dados.

4. Atualize o modelo para visualizar todas as informações.

---

# 📚 Aprendizados

Durante o desenvolvimento deste projeto foram aplicados conhecimentos em:

- Modelagem Dimensional
- ETL com Power Query
- Construção de Medidas em DAX
- Desenvolvimento de KPIs Financeiros
- Storytelling com Dados
- Visualização de Dados
- Dashboards Executivos
- Análise Financeira
- Inteligência de Negócios (BI)

---

# 👨‍💻 Autor

Desenvolvido por **Pedro Lucas**

- 💼 LinkedIn: https://www.linkedin.com/in/pedrolucasrodriguesdata/
- 📧 E-mail: pedrolucaspbi@gmail.com

---
