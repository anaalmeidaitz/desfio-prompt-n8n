Quero criar uma automação no N8N para analisar os dados de uma planilha no google sheets, que contém as informações das faturas de clientes e suas respectivas datas de vencimento e que deve ser verificado as faturas que estão com atraso de pagamento, enviando um e-mail para os clientes realizando essa cobrança.

**Público ou responsável:**
Clientes da empresa

**Resultado esperado:**
Cada cliente que tiver com a fatura em atraso de pagamento, deve receber um e-mail com a cobrança.

**Ferramentas envolvidas:**
Google sheets e Gmail

**Fluxo desejado:**
1. Todas as segundas-feiras, às 9h da manhã, rodar o trigger 
2. Pegar os dados da planilha com as faturas PENDENTES dos clientes
3. Enviar email para os clientes que estão com as faturas vencidas

**Regras importantes:**
Apenas com as faturas que estão pendentes de pagamento e já passaram da data de vencimento
