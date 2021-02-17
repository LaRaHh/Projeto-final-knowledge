## Base de conhecimento

## Descrição

O site tem a funcionalidade de exibir diversos artigos, que podem ser inseridos por usuários administradores, cada um com seu tema, imagem e conteúdo. Esses artigos também podem ser buscados na barra de busca.

## Instalação

<h2>Para acessar o projeto é necessário:</h2>

<h3>No front-end:</h3>
<br/>

- Para o set-up do projeto:
```
npm install
```

- Compilar e recarregar o projeto para desenvolvimento:
```
npm run serve
```

- Compila e minimiza para produção:
```
npm run build
```

- Lints e conserta arquivos:
```
npm run lint
```

<h3>No back-end:</h3>
<br/>

- Para o set-up do projeto:
```
npm install
```

E também instalar os bancos: PostgreSQL, MongoDB.

- Para usar o banco postgreSLQ (é o usado no projeto), deve-se renomear o arquivo "env_file" para ".env" e seu conteúdo deve ser:
```
module.exports = {
    authSecret: 'número aleatório',
    db: {
        host: 'seu host',
        port: sua porta,
        database: 'o nome do seu banco',
        user: 'o banco usado (aconselho o postgreSQL)',
        password: 'sua senha'
    }
}
```

- Para usar o banco MongoBD:
```
sudo mongod ou mongod
```

## Desenvolvimento

Para iniciar o desenvolvimento, é necessário clonar o projeto do GitHub num diretório de sua preferência:

cd "diretorio de sua preferencia"
git clone https://github.com/LaRaHh/Projeto-final-knowledge.git

## Features

O projeto funciona cadastrando usuários como normais ou administradores, os administradores podem cadastrar novos artigos e criar novas categorias. Enquanto que os usuários normais podem apenas ler os artigos e buscar por eles na barra lateral de busca.

## Licença

Não se aplica.