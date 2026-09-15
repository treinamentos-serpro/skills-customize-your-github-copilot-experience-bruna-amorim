# 📘 Atividade: Building REST APIs com FastAPI

## 🎯 Objetivo

Aprender a criar uma API REST básica com FastAPI, incluindo rotas, validação de dados, manipulação de recursos e respostas em JSON.

## 📝 Tarefas

### 🛠️ Configuração inicial da API

#### Descrição
Crie uma aplicação FastAPI simples e configure uma rota de saúde para verificar se a API está funcionando corretamente.

#### Requisitos
O programa concluído deve:

- importar o framework `FastAPI`
- criar uma instância da aplicação
- adicionar uma rota `GET /health`
- retornar um JSON com o status da API, por exemplo: `{ "status": "ok" }`
- permitir que a aplicação seja executada localmente com `uvicorn`

### 🛠️ Criação de recursos e endpoints

#### Descrição
Implemente um pequeno CRUD para gerenciar itens, como tarefas ou livros, usando endpoints HTTP básicos.

#### Requisitos
O programa concluído deve:

- criar uma lista em memória para armazenar os dados
- implementar `GET /items` para listar todos os itens
- implementar `GET /items/{item_id}` para buscar um item específico
- implementar `POST /items` para criar um novo item
- implementar `PUT /items/{item_id}` para atualizar um item existente
- implementar `DELETE /items/{item_id}` para remover um item

### 🛠️ Validação e modelagem de dados

#### Descrição
Use modelos de dados para validar a estrutura das entradas e respostas da API.

#### Requisitos
O programa concluído deve:

- definir um modelo para os itens com campos como `id`, `title` e `description`
- validar os dados recebidos antes de salvar ou atualizar
- retornar respostas em JSON com formato consistente
- garantir que campos obrigatórios sejam tratados corretamente
- mostrar mensagens de erro úteis para entradas inválidas

### 🛠️ Documentação e boas práticas

#### Descrição
Explorar o sistema de documentação automática do FastAPI e organizar a API de forma clara.

#### Requisitos
O programa concluído deve:

- usar nomes claros para rotas e modelos
- manter a API organizada em um único arquivo ou em módulos simples
- verificar que a documentação interativa esteja disponível em `/docs`
- incluir exemplos ou descrições de uso para facilitar a compreensão
