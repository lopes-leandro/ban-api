# JSON-Server com TypeScript
Um servidor de api simples para ser utilizado no desenvolvimento de suas aplicações, sem a necessidade de construção de uma API robusta em outras linguagem. JSON-Server é simples, direto, de fácil configuração e ajuda a pagar seus boletos do final do mês....

Siga os passos abaixo para criar o seu ou clone este repositório

Através da linha de comando no seu Terminal, execute o comando:
```bash
 mkdir sample-api && cd sample-api
```
Inicialize o projeto com:
```bash
npm init -y
```
Instale o json-server
```bash
npm i json-server
```
Instale o typescript e o type do json-server para ts
```bash
npm i typescript @types/json-server
```
Crie o arquivo de configuração do typescript que será necessário para este projeto
```bash
npx tsc init
```
Crie seu arquivo README.md isso é muito importante:
```bash
echo "# <Nome do seu projeto>" >> README.md
```
Crie os arquivos necessários para o json-server executar:
```bash
touch db.json
touch server.ts
```