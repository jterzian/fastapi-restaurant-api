# FastAPI Restaurant API 🍔

Este projeto é uma API para um sistema de restaurante desenvolvida com **FastAPI**, focada em demonstrar boas práticas de desenvolvimento, incluindo automação com **Poetry** e integração contínua (CI) via **GitHub Actions**.

## 🚀 Status do Projeto
![CI Pipeline](https://img.shields.io/github/actions/workflow/status/jterzian/fastapi-restaurant-api/python-app.yml?branch=main&label=CI%20Pipeline&style=for-the-badge)
*(Este selo mostra que o código está passando nos testes automaticamente!)*

## 🛠️ Tecnologias Utilizadas
* **Python 3.9**
* **FastAPI**: Framework web de alta performance.
* **Uvicorn**: Servidor ASGI para rodar a aplicação.
* **Poetry**: Gerenciamento de dependências e ambiente virtual.
* **Pytest & HTTPIX**: Para testes automatizados e requisições assíncronas.
* **GitHub Actions**: Automação do pipeline de testes (CI).

## 📂 Estrutura de Pastas
* `main.py`: Ponto de entrada da aplicação FastAPI.
* `tests/`: Pasta contendo os testes automatizados (`test_main.py`).
* `.github/workflows/`: Configuração do pipeline de CI/CD.

## ⚙️ Como rodar o projeto localmente
1. Instale as dependências:
   ```bash
   pip install fastapi uvicorn pytest httpx

Execute o servidor:

Bash
uvicorn main:app --reload
Rode os testes:

Bash
pytest
🧪 Integração Contínua (CI)
O projeto possui um pipeline configurado no GitHub Actions que, a cada push, realiza:

Configuração do ambiente Python.

Instalação das dependências.

Execução automática da suíte de testes para garantir a integridade do código.