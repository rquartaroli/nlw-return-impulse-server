## 💻 Projeto
Back-end utilizado no projeto Widget da semana NLW-Return Impulse da Rocketseat. Nele contém a tabela feedbacks onde irá armazenar os feedbacks recebidos dos usuários.


## ✨ Tecnologias

- [Node JS](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prisma](https://www.prisma.io/)
- [Nodemailer](https://nodemailer.com/about/)
- [TS-NODE-DEV](https://github.com/wclr/ts-node-dev)
- [Jest](https://jestjs.io/pt-BR/)


## :hammer_and_wrench: Front-end da aplicação

Para você visualizar o projeto Front-end web. Acesse [esse link](https://github.com/rquartaroli/nlw-return-impulse-web).

Para você visualizar o projeto Front-end mobile. Acesse [esse link](https://github.com/rquartaroli/nlw-return-impulse-mobile).


## 🔖 Layout

Você pode visualizar o layout do projeto através [desse link](https://www.figma.com/file/xiP4Pn4TsRYnpnGb5ap9he/Feedback-Widget-(Community)?node-id=10%3A1638). É necessário ter conta no [Figma](http://figma.com/) para acessá-lo.


## Executando o projeto

Utilize o **npm install** para instalar as dependências do projeto.
Em seguida, inicie o projeto.<br/>

```cl
npm run dev
```

Caso queira visualizar as tabelas através do prisma studio,<br/>
**Execute esse comando em outro terminal:**<br/>
 
 ```cl
npx prisma studio
```


## 🎏 Rota

- **Feedback** 
<p>
  <img alt="POST" src="https://img.shields.io/badge/-POST-brightgreen">
  <strong>/feedbacks</strong>
</p>

Body: JSON
```json
{
	"type": "BUG",
	"comment": "Esta tudo bugado!"
}
```
<br />

**Recomendação**: Para executar as rotas, recomendo a utilização do [Insomnia](https://insomnia.rest/).


## 📄 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Feito por Rafael Quartaroli através das aulas ministradas pela [Rocketseat](https://rocketseat.com.br/).

<br />
