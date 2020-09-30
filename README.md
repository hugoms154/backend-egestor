# eGestor
Aplicação com a responsabilidade de facilitar a gestão de funcionários. Controlando dados de funcionários como data de contratação, salários, status (ativo|inativo|bloqueado).

## Resumo
API REST<br />
Rotas disponíveis na documentação swagger no arquivo `swagger.json` localizado em `.src/`<br />
Também estando disponível a partir da rota `/swagger` pelo navegador.

## Tecnologias
NodeJS | Typescript | Express | Jest | SQLite | TypeORM | Tsyringe

## Instalação
Use o git [clone](https://git-scm.com/docs/git-clone) para clonar o repositório. Então instale as dependencias com yarn.
```bash
git clone https://github.com/hugoms154/backend-allu.git
cd backend-allu

yarn install
```

Inicie o banco de dados executando. Será criado o arquivo em `./src/database/db.sqlite`.
```bash
yarn typeorm migration:run
```

## Scripts disponíveis

### database: rodar novas migrations
```bash
yarn typeorm migration:run
```

### database: reveter última migration
```bash
yarn typeorm migration:revert
```

### server: Iniciar servidor
```bash
yarn dev:server
```
### tests: Testes automatizados
```bash
yarn test
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
