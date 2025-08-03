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

![smartclient-ini](https://github.com/user-attachments/assets/91fdc8f9-0575-4d33-907a-fdfe3fc24c36)


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

Acesso inicial:

![credenciais-acesso-onca-preta](https://github.com/user-attachments/assets/bc9ef2cd-750d-4736-a144-df999d6b79db)

Escolha o Módulo:

![modulos-onca-preta](https://github.com/user-attachments/assets/38686084-0c8f-41d4-ac9d-eed620730090)

Criando tabelas:

![criando-tabelas-onca-preta](https://github.com/user-attachments/assets/3fb28533-b6de-4755-b974-8f5e323e6cc5)

Definindo o tipo de ambiente:

![tipo-de-ambiente-onca-preta](https://github.com/user-attachments/assets/3abc4bad-48d7-4feb-b724-1ecc7adcd48b)

Ambiente disponível para uso:

![ambiente-disponivel-postgres-onca-preta](https://github.com/user-attachments/assets/1cfd2071-3685-4c94-8079-fde106915c87)


# ℹ️ Informações Adicionais:

⚙️ Release 12.1.2310 
- Porta TCP 2240
- Porta WebApp 2240
- WebMonitor Habilitado
- APP_MONITOR Habilitado
- 25-06-27-LIB_LABEL_30062025_P12_HARPIA
- 25-05-19-CENTRAL_DE_ATUALIZACOES_V2_4_0
- 25-05-16-P12_APPSERVER_BUILD-20.3.2.23_LINUX_X64
- 25-06-27-SMARTLINK-2.6.3_HARPIA
- 25-05-14-P12_SMARTCLIENT_WEBAPP_9.2.0_LINUX_X64

⚙️ Release 12.1.2410
- Porta TCP 1240
- Porta WebApp 1240
- WebMonitor Habilitado
- APP_MONITOR Habilitado
- WebAgent Habilitado
- 25-06-27-LIB_LABEL_30062025_P12_ONCA
- 25-05-19-CENTRAL_DE_ATUALIZACOES_V2_4_0
- 25-03-28-P12_APPSERVER_BUILD-24.3.0.5_LINUX_X64
- 25-06-27-SMARTLINK-2.6.3_ONCA
- 25-05-19-P12_SMARTCLIENT_WEBAPP_10.1.0_LINUX_X64
- 25-05-14-P12_SMARTCLIENT_WEB-AGENT_1.0.17

⚙️ DBAccess 24.1.0.2

⚙️ TOTVS License Server 3.7.0

⚙️ Postgres 16.9

# ❓ Dúvidas:

Credenciais de acesso:
- O ambiente será criado na primeira inicialização, incluindo a criação de tabelas e credenciais de acesso.

Acesso via webApp/Browser:
- O endereço é composto por http://127.0.0.1:<porta_tcp>/webapp

Acesso ao WebMonitor:
- O endereço é composto por http://127.0.0.1:<porta_tcp>/webmonitor

Deverá ser informado usuário, senha e nome do ambiente:

![web-monitor-postgres-onca-preta](https://github.com/user-attachments/assets/e0afb5f3-8b6b-4176-b934-afd96a69b00c)

Visualizando informações do WebMonitor:

![web-monitor-postgres](https://github.com/user-attachments/assets/97bd0956-9ff2-4562-a4c7-60a7a0668393)

Acesso ao tlppCore (GUI)
- o endereço é composta por http://127.0.0.1:<porta_app_monitor>/api

![tlpp-core-gui-postgres](https://github.com/user-attachments/assets/c7d2b5c0-2734-4eee-891e-7dbe5ee555f8)


Persistência de dados:
- Se desejar, poderá manter os dados do ambiente salvos, e para isto, deverá utilizar um "volume" para realizar a persistência de dados, desta maneira tudo que for realizado no container será refletido para o host conforme definido no
 arquivo "docker-compose".

![volume-linux-postgres](https://github.com/user-attachments/assets/5e9270d6-0558-4534-b943-932cf6345a58)

- No exemplo abaixo, criei um volume especifico no disco para que tudo seja mantido.

![volume-grafico-postgres](https://github.com/user-attachments/assets/1e5020a6-0671-4928-8cfd-8b3391bc7dc7)

Lembrando que o volume poderá ser criado/definido de 2 formas:

- Através da instrução "docker volume create nome_do_volume"
- Através do Docker Desktop - Resources/File Sharing

O nome ou caminho do volume obrigatoriamente deverão ser mencionados no arquivo docker-compose.yaml.

Verificando o agrupamento de caracteres no POSTGRES:

Através da instrução abaixo é possível avaliar o retorno para garantir que tudo está em ordem.

![sql-postgres](https://github.com/user-attachments/assets/e6a2670b-30b1-4477-bb2b-0dd3e84d14c3)


# 🐙🐋 O que é o Docker Compose 🐙🐋

É um arquivo, cujo objetivo é simplificar a execução, organização e a comunicação de diversas aplicações.

Especificamente neste projeto, o docker-compose faz uso de 3 imagens construidas para o montagem dos ambientes, possuem variáveis de controle para facilitar qualquer possível manutenção. Exemplo: alterar a porta de acesso ao sistema e a criação/definição de volumes para persistência de dados.

Alguns pontos de atenção:

- image:

Define a origem da imagem, que será usada como base para a montagem/criação do container.

- ports:

Define a porta de comunicação entre o host e container.

- environment:

Variáveis de ambiente extremamente úteis para a macrosubstituição de informações sensíveis.

- volumes:

Define onde poderá ser realizada a persitência de dados entre o host e container.

- depends_on:

Define a depêndencia do container para sua execução com sucesso.

Como comentei anteriormente, nesse projeto também está sendo utilizado o recurso de "healthcheck" que tem como objetivo validar a saúde do conteiner (Postgres no caso) e com isso garantir a sua disponibiliadde de uso.

![healthcheck-postgres](https://github.com/user-attachments/assets/cf9b7785-b6b0-46d2-97ff-8392b18f0406)

Entendendo melhor o "healthcheck":

- test:
Comando que o Docker executará para verificar a saúde do contêiner.
O comando pg_isready é um utilitário do PostgreSQL que verifica o status de conexão de um servidor de banco de dados PostgreSQL.
Através do -U postgres: especifica o usuário a ser usado para a verificação, que deve corresponder ao POSTGRES_USER.
Através do -d postgres: especifica o nome do banco de dados a ser verificado, que deve corresponder ao POSTGRES_DB.

- interval:
A cada 10s (10 segundos), o comando de healthcheck será executado.

- timeout:
Se o comando levar mais de 5s (5 segundos) para responder, a verificação será considerada como falha.

- retries:
O contêiner será considerado "não saudável" (unhealthy) após 5 tentativas consecutivas de falha.

- start_period:
Fornece um período de carência de 10s (10 segundos) após o contêiner iniciar. Falhas de healthcheck durante este período não contarão para o número máximo de retries, dando tempo para o PostgreSQL inicializar.


# 💻 Extras 💻

No meu repositório DOCKER HUB existem diversas imagens disponiveís para uso e que também terão projetos criados aqui no GitHub.

🔗 https://hub.docker.com/u/rodrigomicrosiga 🔗

# ✉️ Dúvidas, Idéias, Contato... ✉️

Sintam se a vontade para contatar-me. 
Afinal a ideia é compartilhar conhecimento com todos! 👊🏻💥

## Anotações Mobile
## 1 - Inclusão Rest


[ONSTART]

Jobs=HTTPJOB

Refreshrate=3600

[HTTPV11]

Enable=1

AddressFamily=1

Sockets=HTTPREST

TimeOut=3600


[HTTPREST] 

Port=8080

IPsBind=

URIs=HTTPURI

Security=1

MaxQueue=10

;LogRequest=1

;LogResponse=1

[HTTPURI]

URL=/rest

PrepareIn=99

Instances=1,2,1,1

CORSEnable=0

AllowOrigin=*

[HTTPJOB]

MAIN=HTTP_START

ENVIRONMENT=PROTHEUS


