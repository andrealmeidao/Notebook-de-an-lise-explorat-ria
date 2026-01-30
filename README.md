# Notebook-de-ana-lise-explorat-ria
estudar cancelamento de clientes em um case didático.

Exercício prático de Data Science centrado na análise de churn. O núcleo é o notebook inicial.ipynb, que carrega cancelamentos.csv com pandas, exibe a tabela e inspeciona metadados (.info()), faz limpeza básica (dropna()), e explora a variável alvo cancelou com contagens e proporções. Em seguida o notebook gera histogramas por coluna usando plotly.express para visualizar distribuições e comparar perfis entre clientes que cancelaram e os que permaneceram. Há também exemplos de filtragem condicional (por exemplo, excluir contratos Monthly, limitar chamadas ao call center, ou dias de atraso) para demonstrar como segmentar a base e avaliar mudanças na taxa de cancelamento.

Entradas: o CSV cancelamentos.csv (colunas como CustomerID, idade, sexo, duracao_contrato, total_gasto, cancelou, etc.).
Saídas: visualizações interativas (histogramas), tabelas de contagem/percentual e subconjuntos filtrados que ajudam a identificar padrões associados ao churn.

Uso esperado: abrir inicial.ipynb em um ambiente Jupyter/Colab com pandas e plotly instalados, executar células passo a passo para replicar a limpeza, visualização e filtragens. O material serve como base didática para aprender EDA, tratamento de dados e geração de hipóteses sobre cancelamento.

OBS: Utilizar codespace para abrir um ambiente de testes no próprio navegador.
