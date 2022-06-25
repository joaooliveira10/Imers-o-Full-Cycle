# Imersao-Full-Cycle


## Itens necessários 

Docker: https://www.docker.com/
GoLang: https://go.dev/
VSCode: https://code.visualstudio.com/ ou Goland: https://www.jetbrains.com/go/

1   Simulação de coordenadas
   Na pasta simulator encontraremos arquivos GO e Docker, vamos executar o docker para poder utilizar o conteiner
   Para iniciar o conteiner vamos dar um:
   docker-compose up -d 
   
   Para verificar se ele esta ativo podemos verificar dando um:
   docker-compose ps
   
   Vamos mexer em nosso conteiner
   docker exec -it simulator bash
   
   Dentro do conteiner GO vamos criar o pacote onde iremos utilizar
   go mod init github.com/joaooliveira10/simulator
