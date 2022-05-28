# desafio-fullcycle-node
Desafio do curso FullCycle, no módulo de DevOps, trabalhando com docker.

## Descrição do desafio
Quando um usuário acessar o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro no banco de dados mysql, cadastrando um nome na tabela people.

## O retorno da aplicação node.js para o nginx deverá ser:
```html
<h1>Full Cycle Rocks!</h1>

- Listar nomes cadastrados no banco de dados.
```

## Requisitos
1. Toda a aplicação deve estar disponível na porta 8080.

  
## Para rodar
```
git clone https://github.com/leonardoquintania/desafio-fullcycle-node.git
cd desafio-desafio-fullcycle-node
docker-compose up [-d]
```
<br/>
<br/>

