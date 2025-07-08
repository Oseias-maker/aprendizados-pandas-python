# 📊 Primeiros Passos com Pandas em Python

Este repositório tem como objetivo compartilhar meus primeiros aprendizados com a biblioteca **Pandas**, uma das ferramentas mais poderosas para análise e manipulação de dados em Python.

## 🧠 O que você vai encontrar aqui?

- Leitura de arquivos `.csv` com `pandas.read_csv()`
- Filtragem de dados com condições lógicas
- Seleção de colunas e linhas específicas
- Estatísticas descritivas com `.describe()` e `.info()`
- Agrupamentos de dados com `groupby()`
- Limpeza e tratamento de dados ausentes
- Criação de novas colunas com base em regras

## 📁 Estrutura do repositório

📂 Pandas-intro
┣ 📂 .ipynb_checkpoints
┣ 📂 OutPut
┣ 📄 2025_Passagem
┣ 📄 2025_Viagem

(Não foi possível fazer uploads dos arquivos, pois são maiores do que 25Mb e o GitHub não permite ser maior do que 25Mb)
Link do meu Google Drive com os arquivos: https://drive.google.com/drive/folders/1N0WJwMdg1uRU3pGT8qpeURP5gwG0_qqy?usp=drive_link  

# Códigos de análise de projetos

# 📁 Análise de Dados de Viagens com Pandas

Este script em Python utiliza a biblioteca **Pandas** para realizar uma análise exploratória e tratamento de dados relacionados a viagens de servidores públicos. O objetivo é transformar, limpar e gerar insights a partir de dados reais armazenados em arquivos CSV.

## 🔧 Funcionalidades do Script

### 📥 1. Importação de Dados
- Leitura de arquivo CSV com encoding específico (`Windows-1252`) e separador `;`.
- Caminhos configurados para leitura de dados e exportação dos resultados.

### 🔄 2. Conversão de Tipos de Dados
- Conversão de colunas financeiras (`Valor diárias`, `Valor passagens`, `Valor devolução`, `Valor outros gastos`) para tipo `float`.
- Substituição de vírgulas por pontos nas colunas numéricas.

### ➕ 3. Cálculo de Total de Gastos
- Criação de nova coluna chamada **`Total de gastos`**, com a soma de todas as despesas relacionadas a cada viagem.

### 🧼 4. Limpeza de Dados
- Preenchimento de valores nulos da coluna `Cargo` com o texto `"NÃO IDENTIFICADO"`.

### 🗓️ 5. Conversão de Datas
- Conversão de colunas de data para o formato `datetime`.
- Cálculo do número de dias entre data de início e fim da viagem.
- Criação da coluna `Mês da viagem` com o nome do mês.

### 📊 6. Agregação e Consolidação
- Agrupamento dos dados por **Cargo**, gerando uma tabela com:
  - Despesa média
  - Duração média da viagem
  - Número total de viagens
  - Soma das despesas
  - Meses em que as viagens ocorreram

### 📌 7. Filtragem de Cargos Relevantes
- Identificação de cargos que representam mais de 1% das viagens.
- Criação de uma nova tabela com esses cargos filtrados para análise final.

### 💸 8. Análise de Gastos Elevados
- Identificação de servidores com **gastos totais acima de R$ 175.000**.
- Filtro e exibição dos dados correspondentes.

### 🔗 9. Junção com Outro Conjunto de Dados
- Leitura de um segundo CSV com detalhes sobre passagens.
- Junção com os dados principais usando o campo `Identificador do processo de viagem`.
- Filtro para destacar viagens combinadas com altos gastos.

### 💾 10. Exportação dos Resultados
- Exportação da tabela consolidada para um arquivo Excel (`.xlsx`) no diretório de saída.

## 🗂️ Estrutura Esperada






## 📌 Observações
- Este projeto é uma base para aprimoramento de técnicas em **análise de dados públicos** com Pandas.
- É possível expandir o projeto com visualizações, dashboards ou mais filtros específicos.

