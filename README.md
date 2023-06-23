# README

[Video sistema rodando](https://www.loom.com/share/cdc4bdac00d849f38bac650e0d0f9cea?sid=64174ce3-fa76-4fdc-84b6-d17337c465c2)

### Subir a aplicação
```sh
./run.sh
```

Caso ocorra erro de permissão:
```sh
sudo chmod +x run.sh
```

### Autenticação
```
O endpoint de criação de usuários é aberto, os demais utilizam BasicAuth;
Necessário criar um usuário novo e se autenticar com ele em cada requisição;
```

### Multitenancy
```
O usuário é o escopo ("tenant"), se autenticando com o devido usuário, apenas serão vistos/criados registros nesse tenant
```

### Documentação

```
{...}/api-docs
```
