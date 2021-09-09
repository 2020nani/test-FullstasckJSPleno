Teste
CONTELE
Desenvolvido por Hernani Amancio de Almeida

Executar projeto
Para executar o projeto, sera necessario instalar os seguintes programas em seu computador:

Nodejs
Docker
Docker Compose
Postbird
yarn
Desenvolvimento
Para iniciar o desenvolvimento e necessario clonar o projeto do Github num diretorio de sua preferencia com os seguintes comandos:

cd "diretorio de sua preferencia"
git clone https://github.com/2020nani/testeContele.git
cd testeContele
Apos clonar o projeto em seu computador e necessario criar os containers docker para rodar o front e o back:

para criar o container da api, dentro da pasta raiz do projeto de o comando cd serverContele e depois o comando docker-compose up -d
Obs: Certifique que o docker esta rodando

Acesse seu banco de dados com o Postbird que pedira as variaveis ambiente contidas no arquivo docker-compose.yml do service postgres

Feito isso voce pode acessar a api em seu computador na porta 3333 e a documentacao dela na url http://localhost:3333/api-docs

Agora e necessario criar o container do front para isso de o comando cd ../frontContele no terminal, para acessar a pasta onde esta o codigo do front

Dentro desta pasta no terminal de o comando docker-compose up -d

Feito isso voce pode acessar a front em seu computador no endereco http://localhost:3000 e nosso projeto estara rodando dentro dos container docker
