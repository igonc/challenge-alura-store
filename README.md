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

- `AluraStore.Br.ipynb`: Notebook com todo o código, análises e gráficos
- `loja_1.csv` até `loja_4.csv`: Dados das 4 lojas
- `README.md`: Descrição completa do projeto

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

## ✅ Conclusão

Após as análises, recomendamos que o Senhor João venda a **Loja 4**, por apresentar:

- Menor faturamento
- Pior avaliação média
- Menor eficiência logística
- Menor capilaridade geográfica
- Mix de produtos menos consistente

---

## 🚀 Como executar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/alura-store-challenge.git

