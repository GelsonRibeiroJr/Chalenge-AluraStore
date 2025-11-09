# Challenge-AluraStore
Desafio Ciencia de Dados

📊 Alura Store — Análise Exploratoria de Dados

Projeto desenvolvido no Challenge de Data Science - Alura

Este projeto tem como objetivo analisar o desempenho de quatro lojas da Alura Store, avaliando diversos indicadores para que o Sr. João possa decidir qual loja vender. A análise é feita em Python, utilizando Pandas e Matplotlib.

🎯 Objetivo da Análise

O estudo buscou responder uma pergunta central:

Qual loja o Sr. João deve vender, considerando faturamento, satisfação dos clientes, categorias mais vendidas, logística (frete) e desempenho dos produtos?

Para isso, realizamos uma exploração detalhada dos dados, somando faturamento, contando categorias, avaliando produtos mais vendidos e comparando a experiência dos clientes.

📦 Challenge-AluraStore
┣ 📄 README.md – Documentação geral do projeto
┣ 📄 AluraStoreBrasil.ipynb – Código + análises + gráficos
┣ 📄 Relatório final - Analise AluraStore.pdf – Conclusões e recomendações finais
┣ 📂 dados/ – CSVs utilizados na análise
┗ 📂 imagens/ – Gráficos exportados para o README e relatório

🔍 Principais Insights Obtidos
✅ 1. Faturamento Total por Loja

Gráfico de barras mostrando o faturamento total reunido de cada loja.
Esse gráfico permite comparar objetivamente qual loja vende mais.

Insight:
A loja com maior faturamento apresenta maior potencial de receita, mas isso sozinho não determina se é a melhor para manter ou vender.

✅ 2. Categorias Mais Vendidas

Para cada loja, analisamos as categorias com mais vendas.

Insight:
Algumas lojas têm maior concentração em categorias específicas, o que pode indicar dependência de poucos produtos — ou um forte nicho.

✅ 3. Avaliação Média e Distribuição das Avaliações

Foram usados dois gráficos:

Média por loja (linha)

Boxplot comparando a distribuição das notas

Insight:
Mesmo com médias parecidas, o boxplot revela diferenças importantes:
algumas lojas apresentam mais notas baixas (1 e 2), indicando clientes insatisfeitos.

✅ 4. Produtos mais e menos vendidos

Com value_counts() identificamos os destaques positivos e negativos de cada loja.

Insight:
Produtos campeões mostram oportunidades de expansão, enquanto os menos vendidos podem indicar problemas de demanda ou redundância no catálogo.

✅ 5. Frete Médio por Loja

Gráfico de área mostrando o custo médio de frete em cada loja.

Insight:
Fretes mais altos impactam a conversão e satisfação do cliente — e podem reduzir a margem.

## 📊 Exemplos de Gráficos

### 📦 Faturamento por Loja
![Gráfico de Faturamento por Loja](imagens/Grafico%20de%20Faturamento%20por%20Loja.png)

### ⭐ Distribuição das Avaliações por Loja
![Gráfico de Média de Avaliação por Loja](imagens/Grafico%20de%20Media%20de%20Avaliacao%20por%20Loja.png)

### 🚚 Frete Médio por Loja
![Gráfico de Frete Médio por Loja](imagens/Grafico%20Frete%20Medio%20por%20Loja.png)

### 🛒 Produtos Mais x Menos Vendidos
![Gráfico de Produtos Mais e Menos Vendidos](imagens/Grafico%20Produtos%20Mais%20x%20Menos%20vendidos%20por%20Loja.png)


▶️ Como Executar o Projeto
✅ Requisitos

Python 3.10 ou superior

Jupyter Notebook ou Google Colab

Bibliotecas:

pandas

matplotlib

Para instalar:

pip install pandas matplotlib

✅ Para rodar o notebook

Baixe o arquivo AluraStoreBrasil.ipynb

Abra no Jupyter Notebook, VS Code ou Colab

Execute as células na ordem em que aparecem

Os gráficos são gerados automaticamente ao final das análises

✅ Conclusão Final

Ao final do notebook, é apresentada uma recomendação estruturada sobre qual loja o Sr. João deve vender, baseada nos principais fatores analisados:

Faturamento

Satisfação dos clientes

Diversidade e força das categorias

Produtos com maior e menor saída

Custo médio de frete

Essa conclusão serve como apoio à decisão estratégica do cliente.
