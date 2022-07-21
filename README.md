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
NODE --> JS(JavaScript) --> API(API Rest)
NODE --> TS(TypeScript) --> API
NODE --> AD(Adonis.js / Express.js) --> API
NODE --> ORM(ORM - BD) --> API
DOCKER --> SQL((SQLite)) -->  ORM
DOCKER --> MYSQL((MySql)) -->  ORM
DOCKER --> POST((Postgresql)) -->  ORM
DOCKER --> MONGO((MongoDB)) -->  ORM
EU --> FRONT(Front-End)
API --> END{Task done}

FRONT --> HTML(HTML) --> VIEW(VIEW)
FRONT --> JSF(JavaScript) --> VIEW
FRONT --> CSS(CSS) --> VIEW
FRONT --> NEXT(NEXT.JS) --> REACT(REACT) --> VIEW
VIEW --> END
