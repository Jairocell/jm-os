
# JM OS

**Sistema completo de Orçamento e Ordem de Serviço com FastAPI, SQLite e React.**

## ✅ Funcionalidades

- Cadastro de clientes
- Geração de orçamentos
- Controle de serviços e peças
- Geração de relatórios em PDF
- API RESTful com FastAPI
- Banco de dados SQLite
- Frontend com React + Tailwind

## ✅ Como rodar localmente

### 🔧 Backend

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/jm-os.git
cd jm-os
```

2. Crie ambiente virtual (opcional):

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Configure o banco:

```bash
sqlite3 database.db < banco.sql
```

5. Rode a API:

```bash
uvicorn main:app --reload
```

### 🔧 Docker (opcional)

```bash
docker build -t jm-os .
docker run -p 8000:8000 jm-os
```

## ✅ Licença

MIT License

## ✅ Autor

JM OS SYSTEM

