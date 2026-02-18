# 🛠️ Sistema de Gerenciamento de Oficina Mecânica (SQL)
### 🎓 Desafio de Projeto - Bootcamp Klabin - Excel e Power BI Dashboards 2026

---

## 👨‍💻 Autor e Apoio
* **Desenvolvedor:** [Fred Cavalheiro]
* **Instituição:** [DIO (Digital Innovation One)](https://www.dio.me/)
* **Patrocínio:** [Klabin](https://www.klabin.com.br/)

---

### 🛠️ Solução Criativa e Adaptação de Hardware
Devido ao fato de estar utilizando um **computador emprestado** que não possui suporte para a instalação de softwares pesados como o **MySQL Workbench**, optei por uma solução inteiramente baseada em nuvem:
* **Ambiente de Desenvolvimento:** [Google Colab](https://colab.research.google.com/)
* **Tecnologia:** Linguagem **SQL** executada via **Python** com as bibliotecas `mysql-connector-python` e `Pandas` (para manipulação e visualização de dados em formato de tabela).
* **Proatividade:** Essa escolha garantiu que o desafio fosse entregue dentro dos prazos, validando a lógica e a integridade referencial através de scripts funcionais, mesmo sem a ferramenta visual padrão.

## 📝 Descrição do Projeto
Este projeto consiste na implementação de um sistema de banco de dados relacional para o contexto de uma **Oficina Mecânica**. O objetivo é gerenciar Ordens de Serviço (OS), veículos, clientes, mecânicos, além de peças e serviços, garantindo a integridade dos dados e permitindo consultas complexas para suporte à decisão.

> **Nota de Implementação:** Devido a limitações de hardware local e à necessidade de uma solução ágil, o projeto foi desenvolvido inteiramente em **nuvem**. O uso do **Google Colab** foi estratégico para simular um ambiente de produção Linux/MySQL sem sobrecarregar a máquina física utilizada.

---

## 🛠️ Ferramentas e Documentações (Links Úteis)

O projeto foi construído utilizando as seguintes tecnologias:

* [**Google Colab**](https://colab.research.google.com/) - Ambiente de desenvolvimento em nuvem.
* [**MySQL**](https://www.mysql.com/) - Sistema de Gerenciamento de Banco de Dados (SGBD).
* [**Pandas**](https://pandas.pydata.org/docs/) - Biblioteca para manipulação e visualização de dados.
* [**dbdiagram.io**](https://dbdiagram.io/) - Ferramenta utilizada para gerar o diagrama ER automaticamente via código (DBML).
* [**SQLAlchemy**](https://www.sqlalchemy.org/) - SQL Toolkit e Object Relational Mapper para Python.

---

## 📐 Modelagem e Código Fonte

Abaixo estão os acessos diretos para os entregáveis técnicos do projeto:

* 🖼️ [**Acesse aqui a Imagem do Diagrama (Esquema Lógico)**](./) *(Suba o arquivo .png e ele ficará acessível)*
* 📜 [**Acesse aqui o Código DBML / DML (Script SQL)**](./) *(Suba o seu arquivo .sql ou .txt aqui)*
* 📓 [**Acesse o Notebook do Projeto no Colab**](./) *(Suba o seu arquivo .ipynb aqui)*

---

## 🚀 Estrutura do Desafio

O código foi dividido em etapas lógicas para facilitar a manutenção:

1.  **Configuração do Ambiente:** Instalação do servidor MySQL dentro da instância do Colab.
2.  **Definição do Esquema (DDL):** Criação de tabelas com chaves primárias, estrangeiras e constraints de integridade.
3.  **Persistência de Dados (DML):** Inserção de dados fictícios para simulação de cenários reais.
4.  **Queries de Negócio:**
    * Filtros com `WHERE` e ordenações com `ORDER BY`.
    * Cálculos de atributos derivados (Margem de lucro, faturamento).
    * Agrupamentos com `GROUP BY` e filtros de grupo com `HAVING`.
    * Junções complexas com `INNER JOIN` para relatórios detalhados.

---

## 📊 Performance e Visualização
Utilizamos a integração do **Pandas** com o **SQLAlchemy** para gerar tabelas interativas diretamente no notebook, permitindo uma análise rápida dos dados de faturamento e produtividade da oficina.

---

<p align="center">
Desenvolvido com foco em excelência técnica para o Bootcamp Klabin - DIO 2026 🚀
</p>
