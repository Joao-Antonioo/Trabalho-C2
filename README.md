
#Intruções de como executar o programa:
 
#Deve-se criar um arquivo .env no diretório
*adicionar a variável DATABASE_URL="file:./dev.db" para conectar ao banco
*adicionar a variável jwt_Token_Validation="{Nome}" para validar o token

#Comandos para executar na máquina local
*npm install
*npx prisma generate
*npx ts-node-dev ./src/server

#Comandos para rodar no docker
*npm install
*npx prisma generate
*docker-compose up --build
