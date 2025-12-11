# Meu Orçamento (My Budget)

Um aplicativo web full-stack para gerenciamento de finanças pessoais, construído com Python, Flask e SQL. Originalmente feito como o projeto final do curso CS50 de Harvard.
<br>
A full-stack web aplication for personal finance management, built with Python, Flask and SQL. Originally made as Harvard CS50's Final Project.

![Screenshot do Dashboard do Meu Orçamento](https://i.imgur.com/jHT4RNr.png)

---

## 🇧🇷 Sobre o Projeto (Português)

O **Meu Orçamento** é uma aplicação web completa, projetada para capacitar usuários a assumirem o controle de suas finanças pessoais. A ferramenta permite registrar receitas e despesas, categorizá-las, definir orçamentos mensais com acompanhamento visual, analisar gastos através de gráficos e automatizar o lançamento de transações recorrentes.

O objetivo é oferecer uma plataforma intuitiva e poderosa para que os usuários possam entender seus hábitos de consumo, planejar o futuro e alcançar seus objetivos financeiros.

### Principais Funcionalidades

* **Autenticação Segura:** Sistema de registro e login com senhas criptografadas e sessões de usuário.
* **Dashboard Financeiro:** Um resumo visual do mês corrente com total de receitas, despesas, saldo e transações recentes.
* **Gerenciamento de Transações:** Adicione, categorize e delete receitas ou despesas facilmente.
* **Orçamentos Mensais:** Defina limites de gastos por categoria e acompanhe seu progresso com barras que mudam de cor.
* **Relatórios Visuais:** Um gráfico de pizza interativo mostra a distribuição dos seus gastos por categoria.
* **Histórico com Filtros:** Analise todas as suas transações passadas, com a opção de filtrar por mês e/ou categoria.
* **Transações Recorrentes:** Automatize o lançamento de despesas e receitas fixas (como salários e assinaturas).

### Tecnologias Utilizadas

* **Backend:** Python 3, Flask
* **Banco de Dados:** SQLite
* **Frontend:** HTML5, CSS3, JavaScript
* **Frameworks/Bibliotecas:** Bootstrap 5, Chart.js, Jinja


## 🇬🇧 About The Project (English)

My Budget is a full-stack web application designed to empower users to take control of their personal finances. The tool allows users to log income and expenses, categorize them, set monthly budgets with visual feedback, analyze spending through charts, and automate the entry of recurring transactions.

The goal is to offer an intuitive yet powerful platform for users to understand their spending habits, plan for the future, and achieve their financial goals.

### Key Features

* **Secure Authentication:** A complete registration and login system with hashed passwords and user sessions.
* **Financial Dashboard:** A visual summary of the current month with total income, expenses, balance, and recent transactions.
* **Transaction Management:** Easily add, categorize, and delete income or expense entries.
* **Monthly Budgets:** Set spending limits by category and track your progress with color-coded bars.
* **Visual Reports:** An interactive pie chart shows the distribution of your expenses across categories.
* **Filtered History:** Analyze all your past transactions, with options to filter by month and/or category.
* **Recurring Transactions:** Automate the entry of fixed expenses and incomes (like salaries and subscriptions).

### Tech Stack

* **Backend:** Python 3, Flask
* **Database:** SQLite
* **Frontend:** HTML5, CSS3, JavaScript
* **Frameworks/Libraries:** Bootstrap 5, Chart.js, Jinja

---

## 🛠️ Como Rodar Localmente (How to Run)

Como este projeto não inclui o banco de dados nem o ambiente virtual (por boas práticas de segurança), siga estes passos para configurar o projeto na sua máquina.

### Pré-requisitos
* Python 3
* Git
* SQLite3

### Passo a Passo

1.  **Clone o repositório**
    ```bash
    git clone [https://github.com/SEU-USUARIO/NOME-DO-REPO.git](https://github.com/SEU-USUARIO/NOME-DO-REPO.git)
    cd NOME-DO-REPO
    ```

2.  **Crie e Ative o Ambiente Virtual**
    ```bash
    # Criar a venv
    python3 -m venv venv

    # Ativar no Linux/macOS
    source venv/bin/activate

    # Ativar no Windows (Powershell)
    .\venv\Scripts\Activate
    ```

3.  **Instale as Dependências**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure o Banco de Dados**
    Como o arquivo `.db` não está no repositório, você precisa criá-lo a partir do esquema.
    ```bash
    sqlite3 budget.db < schema.sql
    ```

5.  **Rode a Aplicação**
    ```bash
    flask run
    ```
    Acesse o link gerado (geralmente `http://127.0.0.1:5000`) no seu navegador.

---

## 🇬🇧 How to Run Locally

Since this project excludes the database file and the virtual environment (for security best practices), follow these steps to set it up on your machine.

### Prerequisites
* Python 3
* Git
* SQLite3

### Step-by-Step

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/YOUR-USERNAME/REPO-NAME.git](https://github.com/YOUR-USERNAME/REPO-NAME.git)
    cd REPO-NAME
    ```

2.  **Create and Activate Virtual Environment**
    ```bash
    # Create venv
    python3 -m venv venv

    # Activate on Linux/macOS
    source venv/bin/activate

    # Activate on Windows (Powershell)
    .\venv\Scripts\Activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set Up the Database**
    Since the `.db` file is not in the repo, you must create it from the schema file.
    ```bash
    sqlite3 budget.db < schema.sql
    ```

5.  **Run the Application**
    ```bash
    flask run
    ```
    Open the generated link (usually `http://127.0.0.1:5000`) in your browser.
