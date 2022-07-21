- 👋 Hello, I’m @umRuivo 
- 👀 I’m interested in programming and tecnology 
- 🌱 I’m currently learning TypeScript

- 📫 How to reach me ... junior@dr.com

<!---
umRuivo/umRuivo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
This is my roadmap:
```mermaid
graph LR
EU[Junior Alves] --> LINUX(LINUX USER) -->  BACK(Back-End) 
BACK --> DOCKER(DOCKER) 
NODE(Node.js) 
NODE --> JS(JavaScript) --> AD
NODE --> TS(TypeScript) --> AD
AD(Adonis.js / Express.js) --> API(API Rest)
NODE --> ORM(ORM - Prisma.js) --> AD
DOCKER --> NODE
DOCKER --> SQL((SQLite)) -->  ORM
DOCKER --> MYSQL((MySql)) -->  ORM
DOCKER --> POST((Postgresql)) -->  ORM
DOCKER --> MONGO((MongoDB)) -->  ORM
LINUX --> FRONT(Front-End)
API --> GIT(Git - Gitlab - Github) --> END{Task done}

FRONT --> HTML(HTML) --> VIEW(VIEW)
FRONT --> JSF(JavaScript) --> VIEW
FRONT --> CSS(CSS) --> VIEW
CSS  --> BOOTSTRAP(BOOTSTRAP) --> VIEW
CSS  --> TAILWINDCSS(TAILWINDCSS) --> VIEW
CSS  --> W3(W3.CSS) --> VIEW
FRONT --> NEXT(NEXT.JS) --> REACT(REACT.JS) --> VIEW
VIEW --> GIT -->  END
