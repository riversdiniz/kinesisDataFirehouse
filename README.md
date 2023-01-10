# Kinesis Data Firehouse
Criando um Kenesis Data Firehouse AWS

• Deverá produzir dados particionados por data
• Todos os sensores (produtores no mesmo arquivo)
• Cada arquivo uma saída de buffer (todos os dados do
intervalo)

# Formato de Dados

• Todos os sensores devem gerar o mesmo formato!
• Idtemp
• Data
• Type: powerfactor, temperature,
hydraulicpressure
• Timestamp

# Etapas

1. Kinesis Data Stream
2. Criar Aplicações geradoras de Dados
3. Bucket
4. Kinesis Data Firehouse
5. Crawler, Catalog
6. Job para gerar parquet
7. Athena
