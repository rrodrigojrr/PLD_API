# API de valores de valores de Preço de Liquidação das Diferenças (PLD) e outras variáveis do setor elétrico

O PLD é a referência oficial para valorar a energia restante que é liquidada na CCEE. O valor do PLD influencia nos contratos do mercado livre de energia e pode ser usado para minimizar custos. Este projeto independente tem o objetivo de manter uma API operacional com dados oficiais do PLD, previsão a curto, médio e longo prazo da variáveil, dados oficiais e previsão de Energia Natural Afluente, dados meteorológicos e hidrológicos e previsão de tempo e clima. Em outras palavras, uma API que tenta unir a maior quantidade possível de dados relevantes para o setor elétrico brasileiro. 

Este projeto está em estágio inicial de desenvolvimento. Porém, muito em breve, se espera que esteja em pleno funcionamento com as suas principais funcionalidades. 

### Funcionalidades em operação:

- PLD horário atualizado instantâneamente após a divulgação da CCEE;
- End-points com filtros de consulta por intervalo de data, intervalo de valor e submercado;
- Banco de dados com dados históricos de PLD horário (PLD sombra e oficial). 

### Descriçãp técnica:

A API foi completamente desenvolvida em Python utilizando o micro-framework Flask. Os dados são armazenados no banco de dados PostgresSQL. A API é mantida operacional rodando num servidor do Google Cloud. 

## Contato
Para saber mais, entre em contato pelo e-mail: rrodrigo.junior@outlook.com
