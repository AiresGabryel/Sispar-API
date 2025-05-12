# Sispar API

**Sispar API** é uma aplicação desenvolvida em Python para gerenciar colaboradores e solicitações de reembolso. A API oferece endpoints RESTful organizados com base em controladores e documentados por arquivos OpenAPI/YAML.

## 📁 Estrutura do Projeto

Sispar-API-main/
│
├── a.py
├── config.py
├── requirements.txt
├── run.py
├── src/
│ ├── app.py
│ ├── controller/
│ │ ├── colaborador_controller.py
│ │ └── reembolso_controller.py
│ ├── docs/
│ │ ├── colaborador/
│ │ └── reembolso/
│ ├── model/
│ │ ├── colaborador_model.py
│ │ └── reembolso_model.py
│ └── repository/
└── .gitignore

markdown
Copiar código

## 🚀 Como executar

### Pré-requisitos

- Python 3.8+
- Pip (gerenciador de pacotes)

### Instalação

1. Clone este repositório ou extraia os arquivos do `.zip`.
2. Instale as dependências:

```bash
pip install -r requirements.txt
Execute a aplicação:

bash
Copiar código
python run.py
A API será iniciada, geralmente em http://localhost:5000 (dependendo da configuração do app.py ou run.py).

📚 Documentação
A documentação dos endpoints está localizada na pasta src/docs, em arquivos .yml separados por funcionalidade (colaborador e reembolso).

📦 Endpoints principais
/colaborador: Cadastro, login, atualização e exclusão de colaboradores

/reembolso: Solicitação, listagem, atualização e exclusão de reembolsos

🛠 Tecnologias utilizadas
Python

Flask (provavelmente, com base na convenção dos arquivos)

YAML (para documentação OpenAPI)

Estrutura MVC (Model-View-Controller)

🤝 Contribuição
Pull requests são bem-vindos. Para mudanças maiores, abra uma issue antes para discutir o que você gostaria de modificar.

Feito por Gabryel Aires.
