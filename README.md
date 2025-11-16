# Task Tracker API
API de lista de tarefas feita Express.

## Funcionalidades
- Criar novas tarefas, com uma descrição para cada uma
- Editar o status e a descrição das tarefas
- Listar tarefas
- Excluir tarefas

## Tecnologias
- NodeJS 24.11.1
- Express 5.1.0
- Dotenv 17.2.3
- Nodemon 3.1.11

## Como executar
```
git clone https://github.com/bernardoeuler/task-tracker-api.git
cd task-tracker-api
npm i
npm start
```

## Endpoints

### GET /tasks

#### Resposta

```json
[
	{
		"id": "8a76ec78a4c8469687ff427ba7b4615d",
		"description": "Ir ao mercado",
		"status": "Pending",
		"createdAt": 1763236144826
	}
]
```

### POST /tasks

#### Requisição

```json
{
	"description": "Ir ao mercado"
}
```

#### Resposta

```json
{
	"message": "Task created successfully"
}
```
