# API Bancária Assíncrona com FastAPI

## 📌 Sobre o Projeto
Este projeto eleva o sistema bancário para o nível de produção. Utilizando o framework **FastAPI**, transformamos a lógica de negócios em uma API REST completa, capaz de lidar com requisições assíncronas de forma eficiente e segura.

## ⚡ Principais Diferenciais
* **Alta Performance:** Uso de `async` e `await` para operações não bloqueantes.
* **Tipagem Estática:** Aproveitamento total dos Type Hints do Python para reduzir bugs.
* **Validação Automática:** Uso do **Pydantic** para garantir que os dados de entrada (JSON) estejam corretos.
* **Documentação Automática:** A API já nasce com documentação interativa via Swagger UI (`/docs`).

## 🛠️ Tecnologias Utilizadas
* **Python 3.12+**
* **FastAPI:** Framework web moderno e veloz.
* **Uvicorn:** Servidor ASGI para execução da aplicação.
* **Pydantic:** Para modelagem e validação de schemas.

## 🚀 Endpoints Principais
* `POST /clientes`: Cadastro de novos correntistas.
* `POST /contas`: Abertura de contas vinculadas.
* `GET /extrato/{conta_id}`: Consulta de movimentações assíncronas.
* `POST /transacoes`: Realização de depósitos e saques com validação.

## 🏁 Como Rodar a API
1. Instale as dependências: `pip install fastapi uvicorn`
2. Inicie o servidor: `uvicorn main:app --reload`
3. Acesse `http://127.0.0.1:8000/docs` para testar os endpoints.

---
## 👩‍💻 Autora
Feito com 💛 por Bruna Guimarães
