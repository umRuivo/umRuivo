- 👋 Hi, I’m @umRuivo
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
umRuivo/umRuivo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
This is my roadmap:
```mermaid
graph LR
EU[Junior Alves] --> BACK(Back-End) -->  LINUX(LINUX USER)
LINUX --> VPS(VPS) --> DOCKER(DOCKER) --> 
NODE(Node.js) 
NODE --> JS(JavaScript) --> AD
NODE --> TS(TypeScript) --> AD
AD(Adonis.js / Express.js) --> API(API Rest)
NODE --> ORM(ORM - BD) --> AD
DOCKER --> SQL((SQLite)) -->  ORM
DOCKER --> MYSQL((MySql)) -->  ORM
DOCKER --> POST((Postgresql)) -->  ORM
DOCKER --> MONGO((MongoDB)) -->  ORM
EU --> FRONT(Front-End)
API --> GIT(Git - Gitlab - Github) --> END{Task done}

FRONT --> HTML(HTML) --> VIEW(VIEW)
FRONT --> JSF(JavaScript) --> VIEW
FRONT --> CSS(CSS) --> VIEW
CSS  --> BOOTSTRAP(BOOTSTRAP) --> VIEW
CSS  --> TAILWINDCSS(TAILWINDCSS) --> VIEW
CSS  --> W3(W3.CSS) --> VIEW
FRONT --> NEXT(NEXT.JS) --> REACT(REACT.JS) --> VIEW
VIEW --> GIT -->  END
