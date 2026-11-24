
# 🗄️ Estudos de Banco de Dados Relacional - MySQL

Repositório dedicado aos exercícios práticos de modelagem de dados e criação de scripts SQL desenvolvidos no **MySQL Workbench**.

## 📌 Projeto em Destaque: Escola de Idiomas (`Escola_de_Idiomas`)

Modelagem e implementação estrutural de um banco de dados para gerenciar o funcionamento de uma escola de idiomas.

### 🛠️ Conceitos Aplicados:
- **DDL (Data Definition Language):** Criação de bancos de dados e tabelas (`CREATE DATABASE`, `CREATE TABLE`).
- **Relacionamentos:** Definição de Chaves Primárias (`PRIMARY KEY`) e Chaves Estrangeiras (`FOREIGN KEY`) conectando entidades como `idiomas`, `cursos`, `professores`, `alunos`, `turmas`, `salas`, `matriculas` e `habilitacao_professor`.
- **Integridade Referencial:** Aplicação de regras de atualização e exclusão (`ON DELETE RESTRICT` e `ON UPDATE CASCADE`).
- **Validação de Dados:** Uso de restrições (`NOT NULL`, `UNIQUE`, `CHECK`) e tipagens específicas (`ENUM`, `SET`, `DECIMAL`, `DATE`, `TIME`).
- **Diagrama EER:** Modelagem visual das entidades e suas cardinalidades.

## 📂 Arquivos do Repositório
- `fala_mundo.sql` - Script completo de criação das tabelas e restrições.
- `exercicios.mwb` - Arquivo de modelagem EER do MySQL Workbench.
