# Ecoleta - Seu marcketplace de coleta de resíduos.

Ajudamos pessoas a encontrarem pontos de coleta de forma eficiente.

Projeto Ecoleta, desenvolvido durante a **NLW - Next Level Week**, de 01/06 a 07/06/20, oferecida pela [Rocketseat](rs).

## Este projeto é constituído por:

1. Back End, disponível na pasta /server, desenvolvido em [Node.js][nodejs] 
2. Front End, disponível na pasta /web, desenvolvido em [React][reactjs]
3. Mobile, disponível na pasta /mobile, desenvolvido em [React Native][rn]

### Como rodar o Back End:

```bash
# Clone este repositório
$ git clone https://github.com/leon-carvalho/Ecoleta
# Acesse a pasta do projeto no terminal
$ cd nlw_ecoleta
# Vá para a pasta server
$ cd server
# Instale as dependências
$ npm install
# Crie o banco de dados SQLite
$ npm run knex:migrate
# Rode os seeds para preenchimento das tabelas do banco de dados
$ npm run knex:seed
# Execute a aplicação em modo de desenvolvimento
$ npm run dev
# O servidor inciará na porta:3333 - acesse http://localhost:3333
```

### Como rodar o Front End - Aplicação Web:

```bash
# Vá para a pasta da aplicação Front End
$ cd web
# Instale as dependências
$ npm install
# Execute a aplicação 
$ npm start
# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```

### Rodando a aplicação Mobile:

```bash
# Vá para a pasta da aplicação Mobile
$ cd mobile
# Instale as dependências
$ npm install
# Execute a aplicação
$ npm start
# A aplicação será aberta na porta:19002 - acesse http://localhost:19002/
# Instale o app Expo em um dispositivo móvel e faça a leitura do QR Code apresentado em http://localhost:19002/ por meio do app.
```

## Licença
Este projeto esta sobe a licença MIT. Veja o arquivo LICENSE.md para mais detalhes.

Feito por Victor Pacheco

[nodejs]: https://nodejs.org/
[reactjs]: https://reactjs.org
[rn]: https://facebook.github.io/react-native/
[license]: https://opensource.org/licenses/MIT
[rs]: https://rocketseat.com.br
