# 🐍 Pipeline de ETL e Análise de Vendas (Python & Pandas)

Este projeto prático demonstra a construção de um processo completo de ETL (Extração, Transformação e Carga) e Análise Exploratória de Dados utilizando Python. O foco foi simular um cenário real de negócios, recebendo uma base de dados "suja" com inconsistências comuns do dia a dia corporativo e aplicando técnicas de *Data Cleaning* para gerar relatórios financeiros fiáveis e visualizações gráficas.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python
- **Ambiente:** Jupyter Notebook / Google Colab
- **Bibliotecas Principais:** `pandas` (manipulação de dados), `numpy` (operações numéricas) e `matplotlib` (visualização de dados).

## ⚙️ Etapas do Projeto

**1. Extração e Simulação:** - Geração de um dataset robusto (500 registos) simulando inconsistências reais de preenchimento.

**2. Transformação e Limpeza (ETL):**
- **Remoção de Duplicados:** Identificação e eliminação de registos repetidos na base de dados.
- **Padronização de Texto:** Correção de inconsistências em strings, como nomes de cidades escritos em minúsculas (conversão para *Title Case*).
- **Tratamento de Valores Nulos:** Identificação de campos de data vazios (`NaN`) e preenchimento com valores padrão.
- **Conversão de Tipos de Dados (O grande desafio):** Limpeza de colunas financeiras formatadas como texto (ex: "R$ 3.500,00"), removendo símbolos, corrigindo separadores decimais e de milhar, e convertendo o resultado final para o formato numérico (`float`) para permitir cálculos matemáticos.

**3. Análise Exploratória e Visualização:** - Agrupamento de dados para calcular o faturamento total e criar um ranking das cidades com maior volume de vendas.
- Construção de um gráfico de barras destacando a performance de vendas por cidade.

**4. Carga (Exportação):** - Geração e exportação da base de dados final consolidada e limpa em formato `.xlsx` (Excel), pronta para consumo por outras ferramentas de BI ou equipas de negócio.

## 🚀 Como visualizar o projeto
- Abra o ficheiro do Jupyter Notebook (`.ipynb`) disponível neste repositório para acompanhar todo o código comentado, passo a passo.
- O resultado visual final da análise está disponível na imagem `.png` (Gráfico de Vendas), e a base de dados limpa encontra-se na folha de cálculo `.xlsx` em anexo.
