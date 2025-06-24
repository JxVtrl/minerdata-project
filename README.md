# MinerData

Sistema completo de coleta e visualização de dados públicos, com backend em Node.js e frontend em React.js. Inclui comunicação em tempo real via WebSocket (Socket.IO) e infraestrutura orquestrada com Docker.

## 🔧 Estrutura do Projeto

Este repositório principal inclui dois submódulos Git:

- [`backend`](https://github.com/JxVtrl/minerdata-backend): API Node.js com coleta automatizada de dados e WebSocket.
- [`frontend`](https://github.com/JxVtrl/minerdata-frontend): Aplicação React.js para visualização dos dados coletados em tempo real.

## 🚀 Tecnologias

- Node.js + Express + Socket.IO
- React.js
- PostgreSQL
- Docker & Docker Compose
- Git Submodules

## 🐳 Como rodar com Docker

```bash
git clone --recurse-submodules git@github.com:JxVtrl/minerdata.git
cd minerdata
docker-compose up --build
