Challenge-AluraStore

Desafio de Ciência de Dados

📊 Alura Store — Análise Exploratória de Dados

Projeto desenvolvido no Challenge de Data Science da Alura.

O objetivo é analisar o desempenho de quatro lojas da Alura Store, avaliando indicadores-chave para que o Sr. João possa decidir qual loja vender.
A análise foi feita em Python, utilizando as bibliotecas Pandas e Matplotlib.

🎯 Objetivo da Análise

O estudo buscou responder uma pergunta central:

Qual loja o Sr. João deve vender, considerando faturamento, satisfação dos clientes, categorias mais vendidas, logística (frete) e desempenho dos produtos?

Para isso, foi realizada uma exploração detalhada dos dados, somando faturamento, contando categorias, avaliando produtos mais vendidos e comparando a experiência dos clientes.

📁 Estrutura do Projeto
📦 Challenge-AluraStore  
 ┣ 📄 README.md – Documentação geral do projeto  
 ┣ 📄 AluraStoreBrasil.ipynb – Código + análises + gráficos  
 ┣ 📄 Relatório final - Analise AluraStore.pdf – Conclusões e recomendações finais  
 ┣ 📂 dados/ – CSVs usados na análise  
 ┗ 📂 Imagens/ – Gráficos exportados  

🔍 Principais Insights Obtidos

✅ 1. Faturamento Total por Loja
Gráfico de barras mostrando o faturamento total de cada loja.
Permite comparar objetivamente qual loja vende mais.
Insight: As lojas com maior faturamento apresentam maior potencial de receita, mas isso sozinho não determina se é a melhor para manter ou vender.

✅ 2. Categorias Mais Vendidas
Análise das categorias com maior volume de vendas por loja.
Insight: Algumas lojas dependem de poucas categorias, o que pode indicar risco de concentração ou um forte nicho de mercado.

✅ 3. Avaliação Média e Distribuição das Avaliações
Foram usadas duas visualizações: média por loja (gráfico de linha) e boxplot.
Insight: Mesmo com médias próximas, o boxplot mostrou que algumas lojas têm mais notas baixas (1 e 2), indicando insatisfação pontual.

✅ 4. Produtos Mais e Menos Vendidos
Com value_counts(), identificaram-se os destaques positivos e negativos de cada loja.
Insight: Produtos campeões podem ser ampliados; os de menor saída indicam baixa demanda ou estoque ocioso.

✅ 5. Frete Médio por Loja
Análise do custo médio de frete por loja.
Insight: Fretes altos impactam a conversão e a satisfação do cliente, podendo reduzir margens.

▶️ Como Executar o Projeto
✅ Requisitos

Python 3.10 ou superior

Jupyter Notebook ou Google Colab

Bibliotecas:

pip install pandas matplotlib

✅ Execução

Baixe o arquivo AluraStoreBrasil.ipynb

Abra no Jupyter Notebook, VS Code ou Google Colab

Execute as células em sequência

Os gráficos serão gerados automaticamente ao final da análise

✅ Conclusão Final

Ao final do notebook, é apresentada uma recomendação estruturada sobre qual loja o Sr. João deve vender, considerando:

Faturamento

Satisfação dos clientes

Diversidade e força das categorias

Produtos com maior e menor saída

Custo médio de frete

📈 A conclusão serve como apoio à decisão estratégica do cliente, indicando a loja com pior desempenho geral e justificando de forma objetiva a recomendação de venda.
