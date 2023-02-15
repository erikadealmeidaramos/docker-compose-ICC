# Feito individualmente por: Erika de Almeida Ramos

## Eu instalei o mysql no servidor do nginx para verificar se a conexão com o mysql estava funcionando mesmo

## Passos para o teste: 

- Na pasta onde está o arquivo do docker-compose (esta), rodar: docker-compose up
- Listar os containers ativos para verificar os ids e nomes: docker container ps
- Executei o container de acordo com o nome que vi na listagem: docker exec -it licaocasa-nginx-1 sh
- Tentei fazer a conexão com o mysql, referenciando o nome do serviço que está no docker-compose: mysql -u root -p -h mysql
- Coloquei a senha que defini no docker compose: erika
