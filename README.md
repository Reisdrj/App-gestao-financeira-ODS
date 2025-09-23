# SaveSpark — Gerenciamento Financeiro Pessoal 🚀

**Descrição**
SaveSpark é uma aplicação web projetada para facilitar o controle e a gestão das finanças pessoais. Através de uma interface limpa e intuitiva (ex.: tela de login abaixo), o usuário pode registrar receitas e despesas, categorizar transações, acompanhar saldos e visualizar relatórios simples para tomar decisões financeiras melhores.

![SaveSpark - Login/Dashboard](./assets/screenshot.png)

---

## Funcionalidades principais

* Cadastro e autenticação de usuários (login/registro).
* Registro de transações: receitas e despesas com data, categoria, descrição e valor.
* Classificação por categorias (ex.: Alimentação, Transporte, Moradia, Lazer).
* Visão resumida do mês: saldo, total de receitas, total de despesas.
* Filtros por período e por categoria.
* Relatórios básicos (gráficos / tabelas) para acompanhar comportamento de gastos.
* Exportar/Importar CSV (opcional).
* Interface responsiva e foco em usabilidade.

---

## Tech stack (sugestão)

> Ajuste conforme a implementação real do projeto.

* Backend: Python + Django
* Frontend: HTML/CSS com Tailwind CSS
* Banco de dados: PostgreSQL (produção)
* Autenticação: Django auth

---

## Requisitos

* Python 3.10+
* pip

---

## Instalação e execução (modo local — exemplo com Django)

1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/savespark.git
cd savespark
```

2. Crie e ative um ambiente virtual

```bash
python -m venv venv
source venv/bin/activate   # Linux / macOS
venv\Scripts\activate      # Windows
```

3. Instale dependências

```bash
pip install -r requirements.txt
```

6. Execute o servidor de desenvolvimento

```bash
python manage.py runserver
# Acesse http://localhost:8000
```

---

## Estrutura de diretórios

```
Projeto/
├─ Home/                  # Funcionalidade (uma das)
├─ SaveSpark/             # Conf do Django

```

---

## Como contribuir

Contribuições são bem-vindas!

1. Faça um fork do projeto.
2. Crie uma branch (`feature/nova-funcionalidade`).
3. Faça commits claros e pequenos.
4. Abra um Pull Request com descrição das alterações.

Antes de implementar features grandes, abra uma *issue* para discutir o escopo.

---

## Licença

Distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para detalhes.

---
