# ETL Universities

## Setup
1. Clone o repositório
2. Crie um ambiente virtual: `python -m venv venv`
3. Ative o venv: `venv\Scripts\activate` (Windows)
4. Instale dependências: `pip install -r requirements.txt`
5. Configure sua chave do MongoDB Atlas no arquivo `.env`
6. Execute: `python main.py` (SQLite) ou `python orchestrate_prefect.py` (MongoDB)