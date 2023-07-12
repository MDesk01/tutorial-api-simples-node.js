# tutorial-api-simples-node.js
Pequeno tutorial de como construir uma API simples utilizando node.js e json-server
<br>
----
<br>
1 - CRIE UMA PASTA
<br>
2 - ENTRE NELA
<br>
3 - USE O COMANDO 'npm init -y' PARA CRIAR UM ARQUIVO DE PACOTE JSON
<br>
4 - USE O COMANDO 'npm i json-server' PARA CRIAR AS DEPENDÊNCIAS DO JSON SERVER
<br>
5 - CRIE UM ARQUIVO C/ O NOME 'db.json'
<br>
6 -  DENTRO DO 'db.json' CRIE UM(OU MAIS) OBJETOS JSON SEGUINTO O SEGUINTE MODELO:
<br>
{
<br>
	"objetos": [{
<br>
		"id": 1,
  <br>
		"nome": "nome_do_objeto_01"
  <br>
		},{
  <br>
		"id": 2,
  <br>
		"nome": "nome_do_objeto_02"
  <br>
		}
  <br>
]}
<br>
7 - VA ATÉ O ARQUIVO "package.json" E NOS "scripts" INSIRA O COMANDO START DA SEGUINTE FORMA:
<br>
	"start": "json-server --watch db.json --port 3001"
 <br>
8 - PARA INICIAR A API, USE O COMANDO 'npm start'
