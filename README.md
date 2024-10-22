- Instalar os containers:
`docker compose up -d --build`

- Entrar no container:
`docker exec -it exercicio-pgsql bash`

- Logar no banco de dados:
    - Host: `localhost`.
    - Usuário: `user`.
    - Senha: `pass`.
    - Banco de dados: `default`.
    - Porta: `5432`.

- Criar um banco de dados chamado `AdventureWorks` no `SGBD`.

- Executar no container:
`psql -d default -U user`

- Executar os comandos:
`\c AdventureWorks` => Conecta no banco de dados.
`\i /data/install.sql` => Preenche o banco de dados com os arquivos.
