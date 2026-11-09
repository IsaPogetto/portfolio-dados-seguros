# Pipeline ETL de dados de seguros

> Status: 🚧 em construção

## Problema de negócio
Consolidar dados brutos de apólices e sinistros em um banco estruturado, pronto para análise e dashboards.

## Dados
Mesma base do projeto 1 (ou dados abertos da SUSEP). _Informar fonte._

## Metodologia
1. Extração (CSV/API)
2. Transformação com Python/Pandas (limpeza, padronização, validações de qualidade)
3. Carga em PostgreSQL com modelo relacional/dimensional (pasta `sql/`)
4. Dashboard no Power BI

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
