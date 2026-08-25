PRD: Audiary — Plataforma de Catalogação e Diário Musical

1. Identificação

Nome: Leonardo Nicolau Skorobohatei
Produto: Audiary
Slogan: Keep track of what you hear
Tema: Plataforma de catalogação, descoberta e registro de experiências musicais.

2. Descrição

O Audiary é uma aplicação web voltada à descoberta, catalogação e registro de experiências musicais. Inspirado em plataformas como o Letterboxd, o sistema busca oferecer ao usuário um espaço dedicado não apenas ao consumo de música, mas também à relação com a música enquanto obra.

Enquanto serviços de streaming são principalmente voltados à reprodução e descoberta de conteúdos, o Audiary permite que o usuário registre os álbuns que ouviu, atribua notas, escreva resenhas e organize sua biblioteca musical.

O sistema tem como objetivo funcionar como um diário musical digital, permitindo que o usuário construa um histórico das obras que escutou e acompanhe sua própria trajetória musical ao longo do tempo.

3. Objetivos do Sistema

- Permitir que usuários pesquisem e descubram artistas e álbuns.
- Permitir o registro de álbuns já escutados.
- Permitir que usuários atribuam notas e escrevam resenhas sobre os álbuns.
- Criar uma biblioteca musical pessoal baseada no histórico de audição.
- Permitir que usuários mantenham uma lista de álbuns que desejam ouvir futuramente.
- Apresentar as informações musicais de forma organizada, responsiva e visualmente consistente.

4. Atores do Sistema

Visitante

Pessoa que acessa a aplicação sem possuir uma conta. Pode pesquisar e visualizar informações sobre artistas e álbuns disponíveis na plataforma.

Usuário

Pessoa autenticada que pode registrar álbuns como ouvidos, atribuir notas, escrever resenhas, favoritar álbuns, manter sua biblioteca e criar uma lista de álbuns que deseja ouvir.

API Pública

Serviço externo responsável por fornecer informações musicais, como artistas, álbuns, capas, gêneros e datas de lançamento.

API Fake

Serviço utilizado pela aplicação para persistir e consultar dados gerados pelos usuários, como registros de audição, avaliações, resenhas e listas.

5. Histórias de Usuário

5.1 Descoberta Musical

- HU01: Como visitante, quero pesquisar artistas e álbuns para descobrir novos conteúdos musicais.
- HU02: Como visitante, quero visualizar informações de um álbum para conhecer seu artista, gênero, data de lançamento e faixas.
- HU03: Como visitante, quero filtrar resultados por gênero ou ano de lançamento para encontrar álbuns de acordo com meus interesses.

5.2 Registro de Audição

- HU04: Como usuário, quero registrar um álbum como ouvido, informando a data em que o escutei, para manter um histórico das minhas experiências musicais.
- HU05: Como usuário, quero atribuir uma nota de 1 a 5 estrelas a um álbum, para registrar minha opinião sobre a obra.
- HU06: Como usuário, quero visualizar meu histórico de álbuns ouvidos, para acompanhar minha trajetória musical.

5.3 Resenhas

- HU07: Como usuário, quero escrever uma resenha sobre um álbum que ouvi, para registrar minhas impressões sobre a obra.
- HU08: Como usuário, quero editar ou excluir minhas resenhas, para manter minhas opiniões atualizadas.

5.4 Biblioteca Pessoal

- HU09: Como usuário, quero adicionar um álbum à minha biblioteca, para organizar as obras que já ouvi.
- HU10: Como usuário, quero remover um álbum da minha biblioteca, para manter minha coleção organizada.
- HU11: Como usuário, quero marcar álbuns como favoritos, para acessar rapidamente as obras que mais gosto.

5.5 Lista de Desejos

- HU12: Como usuário, quero adicionar álbuns à minha Listenlist, para registrar obras que desejo ouvir futuramente.
- HU13: Como usuário, quero remover álbuns da minha Listenlist, para manter minha lista atualizada.

5.6 Perfil

- HU14: Como usuário, quero visualizar meu perfil com meus álbuns ouvidos, avaliações, resenhas e favoritos, para acompanhar minha atividade musical.

6. Escopo do MVP

Must Have

- Busca de artistas e álbuns por meio de uma API pública.
- Visualização das informações de álbuns.
- Registro de álbuns ouvidos.
- Registro da data de audição.
- Sistema de avaliação de 1 a 5 estrelas.
- Escrita e gerenciamento de resenhas.
- Biblioteca pessoal.
- Perfil do usuário.
- Persistência dos dados por meio de uma API fake.

Should Have

- Sistema de favoritos.
- Listenlist para álbuns que o usuário deseja ouvir.
- Filtros por gênero e ano de lançamento.

Could Have

- Ordenação do histórico por data, nota ou título.
- Estatísticas pessoais de audição.
- Sugestões de álbuns com base nos gêneros favoritos.

Won't Have no MVP

- Reprodução de áudio diretamente na aplicação.
- Importação automática do histórico do Spotify, Apple Music ou outros serviços de streaming.
- Sistema de seguidores e interação social entre usuários.

7. Requisitos Não Funcionais

- A aplicação deverá possuir uma interface responsiva, adaptada para dispositivos móveis e desktops.
- A interface deverá utilizar um sistema visual consistente de cores, tipografia e componentes.
- Os formulários deverão possuir validações no lado do cliente e mensagens de feedback para o usuário.
- Os dados inseridos pelo usuário deverão ser persistidos por meio de uma API fake.
- A aplicação deverá apresentar mensagens adequadas quando ocorrerem erros durante requisições às APIs.
- A estrutura do projeto deverá ser modular e organizada, facilitando sua manutenção e evolução.