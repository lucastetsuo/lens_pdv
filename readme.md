# PDV
Criação de um PDV utilizando:
    - Docker
    - Laravel 8.*
    - Livewire

Pré-requisitos

    Docker

Instalação

    Clonar projeto
    Executar comando "docker-compose up -d"
    Executar no diretorio "src" o comando "composer install"
    Executar na raiz do projeto o comando "docker exec -it CONTAINER_ID sh", o id do container pode ser encontrado pelo comando docker ps, o 
    nome do container é "picpay-desafio-backend_php"
    Dentro do container executar o comando "php artisan migrate", se for utilizar seeds, execute o comando "php artisan db:seed"
    
    Api estará disponível no endereço "http://localhost:8088/api"

Autor

    Lucas Tetsuo Takagi - lucastetsuo


