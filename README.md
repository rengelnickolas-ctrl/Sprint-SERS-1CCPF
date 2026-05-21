# Sprint-SERS-1CCPF

# Membros

Rodrigo Santana - RM: 572454


Nickolas Emanuel - RM: 573483


Marcelo do Nascimento RM: 569410


Rodrigo Zambelle - RM: 570425


Nathan Hiroshi - RM: 572806


# Problema

A GoodWe não possui um modelo padrão de cobrança para a linha HCA G2, devido à ausência de suporte a plataformas terceiras de
pagamento, o hardware atual não possui suporte ao protocolo OCPP, que é o padrão de mercado utilizado para comunicação direta com as demais plataformas de pagamento.
O objetivo do projeto é propor uma solução viável em relação a esse problema.

# Proposta

Desenvolver uma plataforma de gerenciamento em nuvem integrada a um Gateway de Pagamento (como mercado pago e picpay), o sistema fará consultas agendadas via software (pull) para monitorar o consumo dos carregadores. Uma IA analisará o histórico de recargas para prever picos de consumo e ajustar de forma adaptável a potência das estações de recarga.

# Impactos esperados

Permite que shoppings e mercados cobrem pelas recargas ou deem descontos na recarga através de compras feitas no local e o controle inteligente de carga evita a queda de disjuntores e elimina a necessidade de reformas caras na infraestrutura elétrica do comércio.

# Tecnologias Utilizadas

**Backend**: Feito via Python para criar a lógica do sistema, gerenciar as regras de negócio e realizar as consultas programadas (Pull) para ler os dados das estações.  
