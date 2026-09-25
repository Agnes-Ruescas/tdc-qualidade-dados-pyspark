# Dados não mentem... ou mentem?

Notebook da apresentação **“Dados não mentem... ou mentem? Investigando a qualidade com PySpark”**, apresentada por **Agnes Ruescas** no TDC, no estande da Alura.

## O que vamos investigar

Um relatório indica que as vendas ficaram **37% acima da meta**. Mas será que a soma considera apenas pedidos válidos?

Com PySpark, o notebook percorre a investigação: examina valores ausentes e inválidos, distingue eventos duplicados de atualizações, seleciona a versão atual de cada pedido, aplica regras de qualidade e separa registros para análise. Ao final, confere as contagens e recalcula o indicador: **20% abaixo da meta**.

## Como acompanhar

1. Abra [Investigacao_Qualidade.ipynb](Investigacao_Qualidade.ipynb) aqui no GitHub para ler o código.
2. Para executar, baixe o arquivo e importe-o como notebook em um ambiente Databricks com PySpark.
3. Execute as células na ordem. Os dados fictícios já estão no notebook; não é preciso carregar arquivos externos.

## Ideia principal

Uma soma pode estar tecnicamente correta e ainda responder à pergunta errada. Antes de confiar em um indicador, precisamos definir quais registros são elegíveis e tornar as regras de qualidade explícitas.

---

**Agnes Ruescas** · Engenharia de Dados · Instrutora Alura
