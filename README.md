# Análise de Crédito

Este repositório contém a análise de dados de crédito de 10.127 pessoas, abordando variáveis como **idade**, **estado civil**, **escolaridade**, **salário anual** e **tipos de cartões de crédito**. O objetivo é explorar padrões de transações financeiras e comportamento de crédito, utilizando ferramentas como **Excel**, **Power BI**, **Power Point**, **Python** e **Jupyter Notebook**.

## Ferramentas Utilizadas

- **Excel**: Análise de dados e elaboração de gráficos.
- **Power BI**: Criação de dashboards interativos.
- **Power Point**: Apresentação dos resultados.
- **Python**: Processamento de dados e cálculos.
- **Jupyter Notebook**: Execução de código Python e visualização de resultados.

## Análise I

Nesta análise, foram considerados dados de 10.127 pessoas, com informações sobre **idade**, **estado civil**, **escolaridade**, **salário anual** e **tipos de cartões**. A análise foi realizada ao longo de um período de 12 meses e incluiu os seguintes insights:

- **Faixa Etária**: Idades entre 26 e 73 anos.
- **Estado Civil**:
  - **Casados**: 4.687 pessoas
  - **Solteiros**: 3.943 pessoas
  - **Divorciados**: 748 pessoas
  - **NA**: 749 pessoas
- **Escolaridade**:
  - **Sem Educação Formal**: 1.487 pessoas
  - **Ensino Médio**: 2.013 pessoas
  - **Graduação**: 1.013 pessoas
  - **Mestrado**: 3.128 pessoas
  - **Doutorado**: 967 pessoas
  - **NA**: 1.519 pessoas
- **Salário Anual**:
  - **Menos de R$40 mil**: 3.562 pessoas
  - **Entre R$40 mil e R$60 mil**: 1.788 pessoas
  - **Entre R$60 mil e R$80 mil**: 1.400 pessoas
  - **Entre R$80 mil e R$120 mil**: 1.533 pessoas
  - **Acima de R$120 mil**: 726 pessoas
  - **NA**: 1.112 pessoas
- **Tipos de Cartões**:
  - **Blue**: 9.436 pessoas
  - **Silver**: 555 pessoas
  - **Gold**: 116 pessoas
  - **Platinum**: 20 pessoas

## Principais Descobertas

- O valor total das transações realizadas foi superior a **R$45 milhões**, com mais de **657 mil transações**.
- O salário anual total das pessoas analisadas foi superior a **R$571 milhões**.
- **Mulheres** têm maior escolaridade que os **homens**.
- O número de transações realizadas pelas **mulheres** foi superior aos seus ganhos anuais, enquanto para os **homens**, os ganhos anuais foram superiores ao número de transações.
- As pessoas **casadas** têm o maior limite de crédito, com **43,31%** do total, sendo **13,3%** mulheres e **26,47%** homens.

## Análise II

Na segunda análise, observamos dados mais detalhados sobre os tipos de cartões e os limites de crédito médios, com o seguinte resumo:

- **Cartões Platinum**:
  - Menor idade encontrada: **39 anos** (**mulher**) e **41 anos** (**homem**).
  - Média de limite de crédito: **R$30.000**.
- **Cartões Gold**:
  - Média de limite de crédito: **R$28.000**.
- **Cartões Silver**:
  - Média de limite de crédito: **R$25.000**.
- **Cartões Blue**:
  - Média de limite de crédito: **R$7.000**.

Além disso, a análise de **escolaridade** e seus respectivos cartões de crédito revelou que pessoas com **doutorado** e **mestrado** tendem a ter os maiores limites de crédito médios.

### Quantidade de Pessoas por Escolaridade e Tipo de Cartão

- **Doutorado**:
  - 5 pessoas com cartão **Platinum** (**2 mulheres**, **3 homens**).
  - 10 pessoas com cartão **Gold** (**4 mulheres**, **6 homens**).
- **Mestrado**:
  - 8 pessoas com cartão **Platinum** (**4 mulheres**, **4 homens**).
  - 36 pessoas com cartão **Gold** (**12 mulheres**, **24 homens**).

## Conclusão

- A diferença na quantidade de pessoas entre os gêneros é de **5,89%** a mais de **mulheres**.
- Os **homens** têm mais pessoas com **cartão de crédito**.
- As **mulheres** realizaram mais transações do que os seus ganhos anuais, enquanto os **homens** apresentaram o contrário.
- O valor total de transações realizadas pelas **mulheres** foi de **R$23 milhões**, enquanto os **homens** realizaram transações totalizando **R$21 milhões**.
- A faixa etária com maior gasto foi entre **36 e 56 anos**, com um total de **R$38 milhões** em transações.

## Fonte dos Dados

Os dados utilizados nesta análise foram retirados de Kaggle - Análise de Crédito.

## Como Executar o Projeto

Para rodar os notebooks deste projeto, siga as instruções abaixo:

### Clone o repositório:

```bash
git clone https://github.com/ewertondrigues02/Analise_de_Credito.git
cd Analise_de_Credito
```

## Instale as dependências

Se você ainda não possui as dependências instaladas, crie um **ambiente virtual** e instale as bibliotecas necessárias:

```bash
python -m venv venv
source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
```

## Execute os notebooks

Abra os notebooks no **Jupyter** e execute as células para ver a análise detalhada.

```bash
jupyter notebook

```

### Contribuições
Contribuições são bem-vindas! Se você deseja melhorar ou adicionar algo ao projeto, por favor, envie um pull request.

Copiar código





