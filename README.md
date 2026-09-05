# 🛒 Sistema de Vendas (E-commerce Engine)

Sistema modular de gestão de vendas e estoque construído em Python, aplicando os princípios de **Clean Architecture**, **Orientação a Objetos (POO)** e o padrão **Repository**.

---

## 📐 Arquitetura e Estrutura do Projeto

O projeto é organizado em 4 camadas independentes de responsabilidade:

```text
sistema_vendas/
├── banco_de_dados/   # Infraestrutura: Conexão SQLite e scripts DDL (schema.sql)
├── modelos/          # Domínio: Entidades puras POO (Cliente, Produto, Venda)
├── repositorios/     # Persistência: Queries SQL (INSERT, SELECT, UPDATE, DELETE)
├── servicos/         # Casos de Uso: Lógica e orquestração do negócio
└── main.py           # Ponto de entrada do sistema