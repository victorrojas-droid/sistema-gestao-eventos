# sistema-gestao-eventos

## Descrição
O sistema de Gestão de Eventos é uma aplicação desenvolvida para facilitar o gerenciamento de eventos, permitindo o cadastro, organização e acompanhamento de eventos e participantes.

## Tipos de Usuários

### Organizador
- Criar eventos
- Editar eventos
- Visualizar lista de participantes

### Participante
- Visualizar eventos disponíveis
- Inscrever-se em eventos
- Ver detalhes dos eventos

## Objetivo
Objetivo do sistema é centralizar as informações de eventos em uma plattaforma digital, facilitando a administração e o acesso às informações pelos organizadores.

## Funcionalidades
- Cadastro de eventos
- Listagem de eventos
- Cadastro de participantes
- Controle de inscrições
- Visualização de detalhes do evento

## Arquitetura do sistema
O sistema segue uma arquitetura em três camadas: 
- **Frontend:** interface do usuário
- **Backend:** lógica da aplicação
- **Database:** armazenamento de dados

Estrutura do projeto:
frontend/
backend/
database/

## Modelo de Banco de Dados

O sistema utiliza um banco de dados relacional para armazenar informações sobre eventos e participantes.

### Tabela: eventos

- id_evento
- nome_evento
- descricao
- data_evento
- local_evento

### Tabela: participantes

- id_participante
- nome
- email
- telefone

### Tabela: inscricoes

- id_inscricao
- id_evento
- id_participante
- data_inscricao

## Cloud Computing
O sistema pode ser hospedado em serviços em nuvem, permitindo maior escalabilidade e disponibilidade.

Exemplo de arquitetura em cloud:
- Frontend hospedado em servidor web
- Backend executado em servidor de aplicação
- Banco de dados em serviço gerenciado na nuvem

## Arquitetura em Cloud
O sistema pode ser implantado em uma arquitetura de computação em nuvem, garantindo escalabilidade, disponibilidade e facilidade de manutenção. 

Fluxo da aplicação:

Usuário -> Frontend -> Backend -> Banco de Dados

- **Frontend:** responsável pela interface do usuário, acessada pelo navegador.
- **Backend:** responsável pelas regras de negócio e comunicação com o banco de dados.
- **Banco de Dados:** armazena informações sobre eventos e participantes.

  ### Exemplo de serviços em nuvem

- Frontend hospedado em servidor web na nuvem
- Backend executando em uma máquina virtual ou container
- Banco de dados em serviço gerenciado na nuvem

## Tecnologias sugeridas
- HTML, CSS e JavaScript (Frontend)
- Node.js ou Python (Backend)
- MySQL ou PostgreSQL (Banco de dados)

## Tecnologias Utilizadas

As seguintes tecnologias podem ser utilizadas para o desenvolvimento do sistema:

- HTML
- CSS
- JavaScript
- Node.js
- Banco de dados MySQL

## Infraestrutura em Cloud

O sistema pode ser hospedado em uma infraestrutura de computação em nuvem, utilizando serviços como:

- Servidor de aplicação na nuvem
- Banco de dados gerenciado
- Hospedagem do frontend

Provedores de cloud que poderiam ser utilizados:

- AWS
- Microsoft Azure
- Google Cloud

## Fluxo de Funcionamento do Sistema

O funcionamento do sistema ocorre da seguinte forma:

1. O usuário acessa a aplicação pelo navegador.
2. O frontend envia as requisições para o backend.
3. O backend processa as informações e aplica as regras de negócio.
4. O backend consulta ou grava informações no banco de dados.
5. Os dados são retornados para o frontend e exibidos ao usuário.

Esse modelo permite que o sistema seja facilmente escalado em ambientes de computação em nuvem.

  ## Autor
  Victor Gabriel Rojas de Araujo
