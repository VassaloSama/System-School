# Projeto System-School
Estudo de API RESTful para gestão de escolas

## 📖 Sobre o Projeto
Esta API foi desenvolvida utilizando **Flask** e **SQLAlchemy** para gerenciar escola. O sistema permite a criação, leitura, atualização e remoção de professores, turmas e alunos no banco de dados.

## 🛠️ Tecnologias Utilizadas
- Python 🐍
- Flask
- Flask-SQLAlchemy
- SQLite / PostgreSQL / MySQL (dependendo da configuração)
- Swagger para documentação automática dos endpoints

## 🚀 Como Executar o Projeto
### 1️⃣ Clonar o Repositório
```bash
git clone https://github.com/seu-usuario/nome-do-repo.git
cd nome-do-repo
```

### 2️⃣ Criar e Ativar um Ambiente Virtual
```bash
python -m venv venv
# Ativar no Windows
venv\Scripts\activate
# Ativar no macOS/Linux
source venv/bin/activate
```

### 3️⃣ Instalar Dependências
```bash
pip install -r requirements.txt
```

### 4️⃣ Configurar o Banco de Dados
```python
from app import db
from app import app

with app.app_context():
    db.create_all()
```

### 5️⃣ Rodar a Aplicação
```bash
flask run
```
A API estará disponível em: `http://127.0.0.1:5000`