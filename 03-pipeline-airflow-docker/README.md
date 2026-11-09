# Pipeline orquestrado com Airflow e Docker

> Status: 🚧 em construção

## Problema de negócio
Automatizar a ingestão e o tratamento diário de dados públicos, de forma reprodutível e agendada.

## Dados
API pública (ex.: Banco Central ou IBGE). _Informar endpoint._

## Metodologia
1. Container com Docker
2. DAG no Airflow (extrair → tratar → carregar)
3. Agendamento, logs e tratamento de falhas

## Principais resultados
_(preencher ao concluir: 3 a 5 conclusões em linguagem de negócio, com gráficos)_

## Como rodar
```bash
git clone https://github.com/<seu-usuario>/portfolio-dados-seguros.git
cd portfolio-dados-seguros
pip install -r requirements.txt
```
_(complementar com os passos específicos deste projeto)_

## Próximos passos
_(melhorias e limitações conhecidas)_
