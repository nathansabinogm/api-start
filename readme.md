
CRUD
    R -> READ
    C -> CREATE
    U -> UPDATE
    D -> DELETE

### criando api
* json-server
```
npm install json-server
```

* criando arquivo banco
```
{
    "categoria": [
        { 
            "id": 1, 
            "nome": "notebook"
        },
        {
            "id": 2,
            "nome": "games"
        }
    ],
 "produtos": [
        { 
            "id": 1, 
            "nome": "notebook core i3",
            "qtde": 10,
            "preco": 1500.00
        },
        {
            "id": 2,
            "nome": "notebook core i5",
            "qtde": 5,
            "preco": 1500.00
        }
    ]
}
```

* rodar a api
```
npx json-server banco.json
```

### Testando rotas
    * get -->    http://localhost:3000/login
    * put -->    http://localhost:3000/login
    * post -->   http://localhost:3000/login
    * delete --> http://localhost:3000/login

* get -->  READ     --> listar
* put -->  UPDATE   --> atualizar
* post --> CREATE   --> inserir
* delete --> DELETE --> deletar

    * patch
### Criando projeto
* comando
```
npm create vite@latest
```

* instalar as dependencies
```
npm install
```

* rodar o projeto
```
npm run dev
```
