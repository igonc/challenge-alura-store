# 📊 Alura Store Challenge

Desafio de análise de dados proposto pela **Oracle + Alura**, com foco em **Data Science**, **visualização de dados** e **tomada de decisão baseada em evidências**.

---

## 🧠 Objetivo

Ajudar o Senhor João a decidir **qual loja da rede Alura Store deve ser vendida**, com base em:

- 📈 Faturamento total
- 📦 Categorias mais vendidas
- ⭐ Avaliação média dos clientes
- 🛒 Produtos mais e menos vendidos
- 🚚 Frete médio por loja
- 🗺️ (Extra) Distribuição geográfica das vendas

---

## 📁 Estrutura do Projeto

```bash
alura-store-challenge/
│
├── gráficos/                 # Pasta com imagens geradas durante a análise
├── AluraStoreBr_v2.ipynb     # Notebook com todo o código e gráficos
├── loja_1.csv                # Dados da Loja 1
├── loja_2.csv                # Dados da Loja 2
├── loja_3.csv                # Dados da Loja 3
├── loja_4.csv                # Dados da Loja 4
├── mapa_loja_1.html          # Mapa interativo da Loja 1
├── mapa_loja_2.html          # Mapa interativo da Loja 2
├── mapa_loja_3.html          # Mapa interativo da Loja 3
├── mapa_loja_4.html          # Mapa interativo da Loja 4
├── mapa_lojas.html           # Mapa interativo com a distribuição das lojas
└── README.md                 # Documentação do projeto
```

---

## 📥 Origem dos Dados

Os arquivos `.csv` com os dados de vendas foram disponibilizados pela Alura no repositório oficial do desafio:

🔗 [Repositório original](https://github.com/alura-es-cursos/challenge1-data-science)

Arquivos utilizados:

- `loja_1.csv`
- `loja_2.csv`
- `loja_3.csv`
- `loja_4.csv`

As informações contêm dados de:

- Produtos vendidos
- Categorias
- Preço e frete
- Avaliação do cliente
- Vendedor
- Localização (latitude e longitude)
- Tipo e forma de pagamento

---

## 📦 Bibliotecas Utilizadas

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `folium`
- `wordcloud`

---

## 📊 Principais Análises Realizadas

- Comparação de faturamento entre as lojas
- Análise de categorias mais vendidas por loja
- Distribuição de avaliações (histogramas + curva de densidade)
- Nuvem de palavras com os produtos mais vendidos
- Análise do frete médio com boxplot
- Mapas geográficos (dispersão e concentração de vendas por estado)

---

## 📈 Exemplos de Gráficos e Insights Obtidos

### 🔹 Faturamento por Loja
> Loja 4 teve o menor faturamento: **R$ 1.384.498**

### 🔹 Categorias Mais Vendidas
> Loja 4 com desempenho inferior nas categorias **eletrodomésticos** e **instrumentos musicais**

### 🔹 Avaliações dos Clientes
> Loja 1: maior frequência de notas 5  
> Loja 4: média mais baixa e maior número de avaliações negativas

### 🔹 Produtos Mais e Menos Vendidos
> Loja 4 teve baixa consistência e pulverização das vendas  
> Loja 1 apresentou líderes claros de vendas

### 🔹 Frete Médio por Loja
> Loja 4 teve **o menor custo médio de frete**, mas ainda assim o pior desempenho geral

### 🔹 Concentração Geográfica
> Loja 4 tem presença mais dispersa e menor foco em regiões estratégicas como **SP, RJ e MG**

---

## ✅ Conclusão da Análise

A loja recomendada para ser vendida é a **Loja 4**, por apresentar:

- 📉 Menor faturamento
- ⭐ Avaliações mais baixas e dispersas
- 📦 Menor eficiência nas categorias estratégicas
- 🛍️ Mix de produtos com baixa consistência
- 🚚 Frete barato, porém insuficiente para compensar a performance ruim
- 🗺️ Presença geográfica fraca em regiões densas

---

## 🚀 Como Executar

1. Clone este repositório:

```bash
git clone https://github.com/seu-usuario/alura-store-challenge.git
