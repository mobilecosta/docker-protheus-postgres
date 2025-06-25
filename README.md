![docker-protheus-postgres](https://github.com/user-attachments/assets/f9a323df-2f7b-42da-ba85-0e31aebb2f6f)

![Badge release date](https://img.shields.io/github/release-date/rodrigomicrosiga/docker-protheus-postgres)
![Badge_license](https://img.shields.io/github/license/rodrigomicrosiga/docker-protheus-postgres)


O projeto docker-protheus-postgres, objetiva a rápida criação de ambientes de desenvolvimento TOTVS Protheus utilizando o database PostgreSQL.

# Status do Projeto:

🚀 Projeto em constante evolução 🚀

Esse projeto acompanhará a evolução das imagens mantidas no meu repositório DOCKER HUB. 

https://hub.docker.com/u/rodrigomicrosiga 

# Tag Docker:

- appserver onça preta
![Badge docker onca preta](https://img.shields.io/docker/v/rodrigomicrosiga/appserver-dev-protheus/24.3.0.5)

- appserver harpia
![Badge docker harpia](https://img.shields.io/docker/v/rodrigomicrosiga/appserver-dev-protheus/20.3.2.23)

- dbaccess
![Badge docker dbaccess](https://img.shields.io/docker/v/rodrigomicrosiga/dbaccess-dev-protheus/24.1.0.2)

- license
![Badge docker license](https://img.shields.io/docker/v/rodrigomicrosiga/license-dev-protheus/3.7.0)

- postgres
![Badge docker license](https://img.shields.io/docker/v/rodrigomicrosiga/postgres-dev-protheus/16.9)

# Compatibilidade:

![Linux](https://img.shields.io/badge/Linux-E34F26?logo=linux&logoColor=black&style=for-the-badge)
![Windows](https://img.shields.io/badge/Windows-017AD7?logo=windows&logoColor=white&style=for-the-badge)
![MacOS](https://img.shields.io/badge/Mac_OS-20232A?logo=apple&logoColor=white&style=for-the-badge)

# Tecnologias Utilizadas:

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge)
![Postgres](https://img.shields.io/badge/postgresql-4169e1?style=for-the-badge&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

# Funcionalidades:

A partir da execução do arquivo docker-compose.yaml, serão criados ambientes 12.1.2310 ou 12.1.2410.

🖥️ Exemplo 🖥️

Após clonar o projeto, deverá escolher qual ambiente deseja montar e de acordo com a sua escolha, executará a instrução conforme imagem abaixo:
![docker-compose-up-d-postgres](https://github.com/user-attachments/assets/0c24c914-2f1d-4537-80e4-4bd5dc8e291d)

Nesse projeto decidi realizar o uso do "healthcheck" para o PostGres e com isso é possível verificar a saúde do container através do "docker ps". Observem a informação de "healthy" conforme a imagem abaixo:
![docker-ps-postgres-healthy](https://github.com/user-attachments/assets/c788a7d9-003f-40c8-b37e-6a69679c99ca)

Se desejar, também pode verificar via Docker Desktop:
![docker-desktop-postgres](https://github.com/user-attachments/assets/d6180334-bb30-49f8-89e1-eaf9f9b9401c)

Nesse momento o ambiente estará disponível para uso.

# Demonstração da Aplicação:

⚙️ dbAccess 24.1.0

O acesso pode ser realizado via dbmonitor (qt). 

![acesso-dbaccess](https://github.com/user-attachments/assets/b2b0bc6e-8574-4f3a-a77c-83f3df55e968)

Após acessar a interface poderá realizar a validação de comnicação com o banco utilizando como base os dados existentes no arquivo ".env" que previamente está padronizado como "protheus" (DB/USER/PWD).

![valida-conexao-postgres](https://github.com/user-attachments/assets/6d60bb4b-8e89-4ae5-88ad-b368fb1c09fa)

E também via tlppCore (GUI) através da URL http://127.0.0.1:32033/api conforme abaixo:

![tlpp-core-gui](https://github.com/user-attachments/assets/d338670f-f5d3-4b76-8752-6172429c084a)

IMPORTANTE:
O DBACCESS está utilizando o modo "ConnectionMode=2".

![connection-mode-postgres](https://github.com/user-attachments/assets/c2ef5434-0961-4fda-a7e6-0c8f6929d13f)


⚙️ Release 12.1.2310 

O acesso poderá ser realizado via smartclient QT (desktop) ou WebApp.

⚙️ Release 12.1.2410

O acesso deverá ser realizado via WebApp/Browser através da URL http://127.0.0.1:1240/webapp 

![acesso-via-browser-onca-preta](https://github.com/user-attachments/assets/86f1b1c9-e163-46bf-9bc8-067518f94db2)

E na sequencia será solicitada a ação em relação ao WebAgent:

![permissao-web-agent](https://github.com/user-attachments/assets/d0e24ee1-6df7-4341-98b7-bdd2e4f67a19)

IMPORTANTE:
Caso o Web-Agent ainda não esteja instalado será possível instalar a partir da inicialização do sistema.

Defina o tipo de empresa que deseja criar:

![criacao-de-empresas](https://github.com/user-attachments/assets/1ee8431e-7efb-4a01-bfad-3a75e9034c6d)

Defina a localização do ambiente:

![localizacao](https://github.com/user-attachments/assets/24bad27b-0bc8-4d0e-8ed3-a264348be446)

Inicializando o ambiente:

![inicializando-sistema-onca-preta](https://github.com/user-attachments/assets/d08c2ad0-1e34-43a6-adff-6c46ae08cbf5)






