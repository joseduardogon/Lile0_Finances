### README do Projeto Lile0 Finances

---

## Lile0 Finances - Controle Financeiro Pessoal

**Lile0 Finances** é um aplicativo desktop open-source desenvolvido em Python, com o objetivo de ajudar pessoas a controlarem seus gastos, planejarem suas finanças e visualizarem o impacto de decisões financeiras futuras. O aplicativo permite o registro de transações, análise de receitas e despesas, previsões de saldo e simulações financeiras, além de importar extratos bancários fornecidos pelo usuário. Ele é construído com **Flet** para uma interface intuitiva e moderna, utilizando diversas bibliotecas para enriquecer a experiência e garantir segurança e funcionalidade.

### Funcionalidades

- **Dashboard Interativo**: Resumo financeiro com gráficos dinâmicos de saldo, receitas, despesas e visão por categoria.
- **Registro de Transações**: Permite adicionar, editar e visualizar transações, organizadas por tipo (receita/despesa) e categoria.
- **Importação de Extratos Bancários**: Importação de arquivos OFX, CSV e PDF com OCR para leitura automática de transações.
- **Planejamento Orçamentário**: Definição de limites de gastos por categoria com alertas de gastos excessivos.
- **Simulação e Previsão Financeira**: Simulação de cenários futuros com base nos dados de transações, permitindo visualizar o impacto financeiro de decisões.
- **Segurança**: Autenticação e criptografia de dados para proteger informações financeiras do usuário.

### Tecnologias e Bibliotecas

- **Python**: Linguagem principal do aplicativo.
- **Flet**: Framework para criação da interface gráfica.
- **SQLite**: Banco de dados local para armazenamento de dados.
- **SQLAlchemy**: ORM para manipulação de dados de forma mais organizada.
- **Matplotlib/Plotly**: Visualização de dados e gráficos interativos.
- **pandas**: Manipulação de dados financeiros e geração de relatórios.
- **OCR com PyPDF2/Tesseract**: Extração de dados financeiros de PDFs.
- **cryptography**: Criptografia e segurança dos dados dos usuários.

### Estrutura do Código

O código é modularizado para facilitar a manutenção e expansões futuras. As principais funcionalidades estão organizadas em módulos, tais como `interface`, `transacoes`, `simulacoes`, `importacao` e `seguranca`. Cada módulo cuida de uma parte específica do aplicativo, garantindo uma estrutura organizada e escalável.

### Contribuição e Desenvolvimento

Contribuições são bem-vindas! O projeto é open-source e, com sua ajuda, pode se tornar uma ferramenta cada vez mais útil e poderosa para gerenciamento financeiro pessoal.

### Instalação

1. Clone o repositório para sua máquina.
   ```bash
   git clone https://github.com/joseduardogon/lile0-finances.git
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Execute o aplicativo:
   ```bash
   python app.py
   ```

---

## Lile0 Finances - Personal Finance Management

**Lile0 Finances** is an open-source desktop application developed in Python to help people control their expenses, plan their finances, and visualize the impact of future financial decisions. The application allows users to record transactions, analyze income and expenses, forecast balances, and run financial simulations. Additionally, it supports importing bank statements provided by users. Built with **Flet**, it offers an intuitive and modern interface, using various libraries to enrich the user experience and ensure functionality and security.

### Features

- **Interactive Dashboard**: Financial overview with dynamic graphs for balance, income, expenses, and category breakdown.
- **Transaction Recording**: Add, edit, and view transactions categorized by type (income/expense) and category.
- **Bank Statement Import**: Import OFX, CSV, and PDF files with OCR for automatic transaction reading.
- **Budget Planning**: Set spending limits per category with alerts for overspending.
- **Financial Simulation and Forecasting**: Scenario simulation based on transaction data to visualize financial impact.
- **Security**: Authentication and data encryption to protect user financial information.

### Technologies and Libraries

- **Python**: Main language of the application.
- **Flet**: Framework for building the graphical interface.
- **SQLite**: Local database for data storage.
- **SQLAlchemy**: ORM for organized data management.
- **Matplotlib/Plotly**: Data visualization and interactive graphs.
- **pandas**: Data manipulation and report generation.
- **OCR with PyPDF2/Tesseract**: Extract financial data from PDFs.
- **cryptography**: Data encryption for user security.

### Code Structure

The code is modularized to facilitate maintenance and future expansion. Key functionalities are organized into modules such as `interface`, `transactions`, `simulations`, `import`, and `security`. Each module manages a specific aspect of the application, ensuring an organized and scalable structure.

### Contribution and Development

Contributions are welcome! This project is open-source, and with your help, it can become an even more useful and powerful tool for personal finance management.

### Installation

1. Clone the repository to your machine.
   ```bash
   git clone https://github.com/joseduardogon/lile0-finances.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```
