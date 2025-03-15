## Projeto conceitual para banco de dados de um E-commerce

### Projeto conceitual de um banco de dados para um e-commerce usando **MySQL Workbench**. O modelo EER foi exportado para o formato png.

---

Esse projeto faz parte do desafio de código da Formação SQL Database Specialist da DIO. Nele foram aplicados conceitos do modelo EER (Entidade Relacionamento Estendido).

A seguir a lista com soluções para os levantamentos proposto no desafio:

1. Criada duas entidades distintas: **Pessoa Jurídica** e **Pessoa Física** já que o cliente que faz o pedido pode ser apenas uma delas. O relacionamento dessas entidades com a entidade cliente respectivamente gera outras duas entidades na qual denominei de **Cliente é uma PJ** e **Cliente é uma PF**

2. Criada entidade para a forma de pagamento. O cliente pode ter cadastrado mais de uma forma de pagamento, logo foi gerada um nova entidade na qual os atributos compõem qual forma o cliente deseja usar para pagar. 

**Obs.: criei uma entidade de pagamento para pessoa física e pessoa jurídica, pois cada uma tem suas particularidades**

3. Foi criada uma entidade para entrega, pois ela possui atributos particulares que são somente dela.

