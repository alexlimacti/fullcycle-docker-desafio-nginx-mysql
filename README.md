# Desafio do curso FullCycle, no módulo de DevOps, trabalhando com docker.

### Descrição do desafio
> Nesse desafio você colocará em prática o que aprendemos em relação a utilização do nginx como proxy reverso. A idéia principal é que quando um usuário acesse o nginx, o mesmo fará uma chamada em nossa aplicação node.js. Essa aplicação por sua vez adicionará um registro em nosso banco de dados mysql, cadastrando um nome na tabela people.

__O retorno da aplicação node.js para o nginx deverá ser:__
```html
<h1>Full Cycle Rocks!</h1>

- Lista de nomes cadastrada no banco de dados.
```

### Requisitos
1. Toda a aplicação deve estar disponível na porta 8080.

  
### Para rodar :zap:
```
git clone https://github.com/alexlimacti/fullcycle-docker-desafio-nginx-mysql.git

cd fullcycle-docker-desafio-nginx-mysql

docker-compose up [-d]
```

<br/>
<br/>