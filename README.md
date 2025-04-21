# 📊 Alura Store Challenge

Desafio de análise de dados proposto pela Oracle + Alura, com foco em Data Science, visualização de dados e tomada de decisão baseada em evidências.

---

## 🧠 Objetivo

Ajudar o Senhor João a decidir **qual loja da rede Alura Store deve ser vendida**, com base em:

- Faturamento
- Categorias mais vendidas
- Avaliação média dos clientes
- Produtos mais e menos vendidos
- Frete médio por loja
- (Extra) Distribuição geográfica das vendas

---

## 📁 Estrutura do Projeto

```bash
alura-store-challenge/
│
├── AluraStoreBr.ipynb        # Notebook com todo o código e gráficos
├── loja_1.csv                # Dados da Loja 1
├── loja_2.csv                # Dados da Loja 2
├── loja_3.csv                # Dados da Loja 3
├── loja_4.csv                # Dados da Loja 4
└── README.md                 # Documentação do projeto
```

---

📥 Origem dos Dados
Os arquivos .csv com os dados de vendas das quatro lojas foram disponibilizados pela própria Alura no repositório oficial do desafio:

📂 Repositório original:
https://github.com/alura-es-cursos/challenge1-data-science

📌 Arquivos utilizados:

- loja_1.csv
- loja_2.csv
- loja_3.csv
- loja_4.csv

Estes arquivos contêm as informações de vendas, frete, avaliação, localidade (latitude/longitude), categorias, vendedores, e formas de pagamento.

---

## 📦 Bibliotecas utilizadas

- `pandas`
- `matplotlib`
- `seaborn`
- `folium`
- `wordcloud`
- `numpy`

---

## 📊 Principais Análises

- Comparação de faturamento entre as lojas
- Distribuição de categorias por loja
- Análise de avaliações com histogramas e curvas KDE
- Nuvens de palavras dos produtos vendidos
- Análise de frete médio
- Mapa geográfico interativo das vendas (com jitter para evitar sobreposição)

---

## 📈 Exemplos de Gráficos e Insights Obtidos
### 🔹 Faturamento por Loja
Gráfico de barras comparando o total vendido por loja.
➡ Loja 4 teve o menor faturamento.

### 🔹 Vendas por Categoria
Gráficos horizontais mostraram que a Loja 4 possui menor diversidade e volume em categorias populares.

### 🔹 Avaliações de Clientes
Histogramas + curvas KDE para cada loja revelaram:

Loja 1 → maior concentração de notas 4 e 5

Loja 4 → mais avaliações baixas e média geral mais baixa (3.72)

### 🔹 Produtos Mais e Menos Vendidos
Gráficos de barras e nuvens de palavras mostram:

Produtos mais vendidos em destaque por loja

Loja 4 com menor consistência de campeões de venda

### 🔹 Frete Médio
Gráfico horizontal com rótulo embutido:
➡ Loja 4 teve o maior custo médio de frete (R$ 29,03)

### 🔹 Mapa Geográfico
Mapa interativo com marcadores coloridos para cada loja, usando jitter para evitar sobreposição.
➡ Loja 4 com menor presença em regiões de alta densidade populacional.

---

## ✅ Conclusão da Análise
A loja recomendada para ser vendida é a Loja 4, por apresentar:

📉 Menor faturamento

😞 Pior média de avaliações

🧊 Produtos menos consistentes

🚚 Frete mais caro

🌍 Alcance geográfico reduzido

A análise permite que o Senhor João focalize esforços nas lojas mais promissoras e com maior potencial de crescimento.

---

## 🚀 Como executar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/alura-store-challenge.git
```
