# tutorial-api-simples-node.js
Pequeno tutorial de como construir uma API simples utilizando node.js e json-server

----

1 - CRIE UMA PASTA
2 - ENTRE NELA
3 - USE O COMANDO 'npm init -y' PARA CRIAR UM ARQUIVO DE PACOTE JSON
4 - USE O COMANDO 'npm i json-server' PARA CRIAR AS DEPENDÊNCIAS DO JSON SERVER
5 - CRIE UM ARQUIVO C/ O NOME 'db.json'
6 -  CRIE UM(OU MAIS) OBJETOS JSON SEGUINTO O SEGUINTE MODELO:
{
	"objetos": [{
		"id": 1,
		"nome": "nome_do_objeto_01"
		},{
		"id": 2,
		"nome": "nome_do_objeto_02"
		}
]}

7 - VA ATÉ O ARQUIVO "package.json" E NOS "scripts" INSIRA O COMANDO START DA SEGUINTE FORMA:
	"start": "json-server --watch db.json --port 3001"
8 - PARA INICIAR A API, USE O COMANDO 'npm start'
