<p align="center">
  Plataforma web/mobile para suporte a casas de acolhimento desenvolvida na NLW #3 da <a href="https://rocketseat.com.br/">Rocketseat</a> 🚀
</p>

<p align="center">
  <img alt="Happy" src="![happy](https://user-images.githubusercontent.com/57222479/136369893-29cc87e7-ada0-42f4-81c3-7348df3ee14b.png)" width="100%">
</p>

## 💡 Principais tecnologias
- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [TypeScript](https://www.typescriptlang.org/)
- [Typeorm](https://typeorm.io)
- [Leaflet](https://leafletjs.com/)

## 📜 Instruções

#### Para o backend:
- Na pasta **backend**
- `npm run typeorm migration:run` ou `yarn typeorm migration:run` para execução das migrações do banco de dados (sqlite na versão atual)
- `npm run start:dev` ou `yarn start:dev` para rodar o servidor em desenvolvimento com typescript
- `npm build` ou `yarn build` para construção da versão de produção otimizada com javascript
- `npm start` ou `yarn start` para execução da versão de produção em javascript
- certifique-se de criar um arquivo .env na pasta backend seguindo o modelo de .env.example

#### Para mobile:
- Na pasta **mobile**
- `npm start` ou `yarn start` para rodar o servidor expo, siga as instruções no termial

#### Para frontend:
- Na pasta **web**
- `npm run start:dev` ou `yarn start:dev` para rodar um servidor de desenvolvimento com react-scripts
- `npm build` ou `yarn build` para gerar a versão de produção otimizada do projeto em javascript
- `npm start` ou `yarn start` para iniciar um servidor de produção com o build construido no passo anterior
- é possível configurar um link para chamada a API (antes do build) em um arquivo .env configurando o link numa variável REACT_APP_API_URL

#### [🔗 Referência da Rocketseat](https://github.com/rocketseat-education/nlw-03-omnistack)
