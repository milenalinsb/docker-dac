Inicialmente- baixar a imagem tomcat
docker pull tomcat

Inicializar o container com o comando
Docker container run tomcat

O comando "Docker container ls" irá listar todos os containers em execução, o id, o nome da imagem base, o comando para startar o container "nome_do_container run", quando foi criado, o status dele, a porta em que está rodando e o nome default.

Enquanto o comando "Docker image ls" listará todas as imagens baixadas no meu docker, especificando a versão , o id, quando foi criada e o tamanho de cada uma delas.

O docker auxilia na virtualização de um SO, com isso é possível otimizar a estrutura de uma máquina de desenvolvimento. Com o uso dessa plataforma é possível adequar a máquina ára cada tipo de negócio. O container executa uma imagem, como um repositório e será utilizado para inicializar as dependÊncias da aplicação.

Tive dificuldade em criar o artefato .war, e na composição do documento Dockerfile