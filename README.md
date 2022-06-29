Backend utilizado para a aula de autenticação com nextjs do **Programa Ignite da Rocketseat**.

Para acessar a aplicação frontend basta [clicar aqui](https://github.com/enkinduweles/authentication-with-ssr-nextjs)

## Rotas

### Autenticação
Rota para gerar o jwt
```
POST /sessions
```

### Atualizar token
Rota para gerar novo token
```
POST /refresh
```

### Informações do usuário
Rota para retornar os dados do usuário caso esteja autenticado
```
GET /me
```
