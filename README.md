# *Comandos

- npm init -y (Inicializa um projeto  NodejS)
- i -D typescript (Instalando o typescript como DevDependency)
- npx tsc --init (Inicia um projeto Typescript, criando o arquivo tsconfig.json)
- npx tsc (Transpila os arquivos.TS para arquivos.JS)
- node index.js (Execeuta o arquivo.JS)
- npx ts-node index.ts (Executa diretamente o arquivo.ts)

##Alterações no arquivo packege.json
* "scripts": {
   1. "start": "node dist/index.js",
   2. "dev": "npx ts-node src/index.ts",
   3. "build": "rimraf dist && npx tsc",
   4. "build-and-run": "npm rum build && npm start"