# Esquema-OS-de-Oficina-Mecanica
# Esquema Oficina Mecânica

## Descrição
Este projeto representa o esquema conceitual de um sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica.  
O sistema gerencia informações sobre clientes, veículos, equipes de mecânicos, serviços realizados e peças utilizadas.

## Estrutura do Esquema Conceitual
1. **Cliente**: Representa os clientes da oficina.
2. **Veículo**: Representa os veículos dos clientes.
3. **Mecânico**: Representa os mecânicos da oficina.
4. **Equipe**: Agrupamento de mecânicos responsáveis pela execução dos serviços.
5. **Ordem de Serviço (OS)**: Registro de serviços e peças utilizados em um veículo.
6. **Serviço**: Serviços disponíveis na oficina.
7. **Peça**: Peças utilizadas nos serviços.

## Relacionamentos
- Clientes possuem veículos (1:N).
- Veículos possuem ordens de serviço (1:N).
- Equipes são compostas por mecânicos (N:N).
- Ordens de serviço incluem serviços e peças (N:N).

## Tecnologias
- Linguagem SQL
- Ferramenta de modelagem: MySQL Workbench

