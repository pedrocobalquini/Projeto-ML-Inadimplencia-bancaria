# Projeto-ML-financeiro

## 1.Objetivo do projeto

Desenvolver um modelo que preveja se uma conta ficará inadimplente no próximo mês, de acordo com dados demográficos e históricos.

## 2.Dados

Os dados utilizados no projeto contêm informações demográficas, de crédito, e histórico de pagamentos de clientes. Segue a descrição das variáveis:

### 2.1 Variáveis Demográficas
LIMIT_BAL: Valor do crédito fornecido (em novos dólares taiwaneses - NT), incluindo crédito individual e familiar.

SEX: Gênero do cliente:
- 1 = Masculino
- 2 = Feminino

Nota: Os dados de gênero não serão utilizados para tomar decisões devido a considerações éticas.

EDUCATION: Nível de instrução do cliente:
- 1 = Pós-graduação
- 2 = Universidade
- 3 = Ensino Médio
- 4 = Outros

MARRIAGE: Estado civil do cliente:
- 1 = Casado
- 2 = Solteiro
- 3 = Outros

AGE: Idade do cliente (em anos).

### 2.2 Histórico de Pagamentos

PAY_1–PAY_6: Status de pagamento nos meses de abril a setembro:

- PAY_1: Status em setembro.
- PAY_2: Status em agosto.
- ... (até PAY_6, status em abril).

Status de pagamento:

- -1 = Pagamento pontual.
- 1 = Atraso de 1 mês no pagamento.
- 2 = Atraso de 2 meses no pagamento.
- ...
- 8 = Atraso de 8 meses no pagamento.
- 9 = Atraso de 9 meses ou mais.


### 2.3 Dados Financeiros

Valores das Faturas (BILL_AMT1–BILL_AMT6), representam os valores das faturas mensais (em novos dólares taiwaneses):

- BILL_AMT1: Valor da fatura em setembro.
- BILL_AMT2: Valor da fatura em agosto.
- ...
- BILL_AMT6: Valor da fatura em abril.

Valores Pagos (PAY_AMT1–PAY_AMT6), representam os valores pagos nas faturas mensais (em novos dólares taiwaneses):

- PAY_AMT1: Valor pago em setembro.
- PAY_AMT2: Valor pago em agosto.
- ...
- PAY_AMT6: Valor pago em abril.
