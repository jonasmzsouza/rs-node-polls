<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/jonasmzsouza/rs-node-polls?style=flat-square&color=A3E635">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/jonasmzsouza/rs-node-polls?style=flat-square&color=1f6feb">
  <a href="https://github.com/jonasmzsouza/rs-node-polls/commits/main">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/jonasmzsouza/rs-node-polls/main?style=flat-square&color=2f74c0">
  </a>
</p>

<hr>

<p align="center">
  <a href="#-about-the-project">About</a> |
  <a href="#-technologies">Technologies</a> | 
  <a href="#-how-to">How to</a> | 
  <a href="#-author">Author</a> 
</p>

## 💻 About the project

This project is application developed in Node.js. Built in the 14th edition of NWL Expert by [Rocktseat](https://www.rocketseat.com.br/).<br>
This is a real-time polling application using the WebSocket protocol.

![rs-node-polls-diagram](https://github.com/jonasmzsouza/rs-node-polls/assets/61324433/1019fe4c-093f-470c-81de-1325ad347565)


---

## 🛠 Technologies

Technologies and tools that were used in the development of the project:

### **Languages | Environments | Frameworks | Libraries | Techniques**

- [Node.js](https://nodejs.org/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Typescript](https://www.typescriptlang.org/)
- [Docker](https://www.docker.com/)
- [Prisma](https://www.prisma.io/)
- [PostgreSQL](https://www.postgresql.org/)
- [Redis](https://github.com/redis/ioredis)
- [Zod](https://zod.dev/)
- [Fastify](https://fastify.dev/)

### **Utilities**

- Editor: **[Visual Studio Code](https://code.visualstudio.com/)**
- Extension VS Code: **[Prisma](https://marketplace.visualstudio.com/items?itemName=Prisma.prisma)**
- Emojis: **[Emoji Cheat Sheet](https://github.com/ikatyang/emoji-cheat-sheet)**, **[Markdown Emoji](https://gist.github.com/rxaviers/7360908)**
- Shields: **[Shields](https://shields.io/)**

---

## 🔧 How to

### Requirements
- Node 20.x
- NPM 10.x
- Docker

### Installation

1. clone repo
2. delete the file `package-lock.lock`
3. install the dependencies `npm install`
4. start the services with the command `docker-compose up -d`
5. run the project `npm run dev`
6. resources in `http://localhost:3333/`

#### Resources
  - Create Poll `http://localhost:3333/polls`
  - Get Poll  `http://localhost:3333/polls/:pollId`
  ```
  {
    "title": "Poll Title",
    "options": ["pollOption1", "pollOption2", "pollOption3", "pollOption4"]
  }
  ```
  - Create Vote on Poll `http://localhost:3333/polls/:pollId/votes`
  ```
  {
    "pollOptionId": "..."
  }
  ```
  - Websocket `ws://localhost:3333/polls/:pollId/results`

---

## 👨‍💻 Author

<table>
  <tr>
    <td align="center">
      <a href="https://jonasmzsouza.github.io/">
         <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/61324433?v=4" width="100px;" alt=""/>
         <br />
         <sub><b>Jonas Souza</b></sub>
      </a>
    </td>
  </tr>
</table>
 
[![Github Badge](https://img.shields.io/badge/-jonasmzsouza-3e4957?style=flat-square&logo=Github&logoColor=white&link=https://github.com/jonasmzsouza)](https://github.com/jonasmzsouza) [![Linkedin Badge](https://img.shields.io/badge/-jonasmzsouza-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/jonasmzsouza/)](https://www.linkedin.com/in/jonasmzsouza/)
