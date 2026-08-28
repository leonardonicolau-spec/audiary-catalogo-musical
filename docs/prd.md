# PRD: Audiary — Plataforma de Catalogação e Diário Musical

## 1. Identificação

- **Nome:** Leonardo Nicolau Skorobohatei
- **Produto:** Audiary
- **Slogan:** *Keep track of what you hear*
- **Tema:** Plataforma de catalogação, descoberta e registro de experiências musicais.

## 2. Descrição

O Audiary é uma aplicação web voltada à descoberta, catalogação e registro de experiências musicais. Inspirado em plataformas como o Letterboxd, o sistema busca oferecer ao usuário um espaço dedicado não apenas ao consumo de música, mas também à relação com a música enquanto obra.

Enquanto serviços de streaming são principalmente voltados à reprodução e descoberta de conteúdos, o Audiary permite que o usuário registre os álbuns que ouviu, atribua notas, escreva resenhas e organize sua biblioteca musical.

O sistema tem como objetivo funcionar como um diário musical digital, permitindo que o usuário construa um histórico das obras que escutou e acompanhe sua própria trajetória musical ao longo do tempo.

## 3. Objetivos do Sistema

- Permitir que usuários pesquisem e descubram artistas e álbuns.
- Permitir o registro de álbuns já escutados.
- Permitir que usuários atribuam notas e escrevam resenhas sobre os álbuns.
- Criar uma biblioteca musical pessoal baseada no histórico de audição.
- Permitir que usuários mantenham uma lista de álbuns que desejam ouvir futuramente.
- Apresentar as informações musicais de forma organizada, responsiva e visualmente consistente.

## 4. Atores do Sistema

- **Visitante (Não Autenticado):** Pessoa que acessa a plataforma para explorar o catálogo, pesquisar artistas/álbuns e visualizar a landing page.
- **Membro (Usuário Autenticado):** Ouvinte que possui perfil na aplicação e interage ativamente salvando avaliações, escrevendo resenhas, marcando favoritos e gerenciando sua biblioteca pessoal e *Listenlist*.

## 5. Histórias de Usuário (User Stories)

### 📌 Épico 1: Exploração e Busca (RA1, RA4, RA5)

- **US01:** Como **Visitante**, eu quero pesquisar por artistas e álbuns na barra de busca, para que eu possa encontrar informações detalhadas, capas e dados reais de obras musicais.
- **US02:** Como **Visitante**, eu quero navegar por uma interface responsiva e adaptada para dispositivos móveis ou desktop, para que eu possa consultar o catálogo confortavelmente em qualquer tela.
- **US03:** Como **Membro**, eu quero visualizar os detalhes de um álbum em um modal/card interativo, para que eu possa ler informações de faixa, gênero e ano de lançamento.

### 📌 Épico 2: Diário Musical e Registros (RA2, RA4, RA5)

- **US04:** Como **Membro**, eu quero registrar um álbum como "ouvido" informando a data da audição, para que eu possa manter um histórico cronológico do meu diário musical.
- **US05:** Como **Membro**, eu quero atribuir uma nota de 1 a 5 estrelas a um álbum, para que eu possa classificar minhas experiências musicais.
- **US06:** Como **Membro**, eu quero escrever, editar e excluir resenhas sobre um álbum, para que eu possa registrar minhas opiniões pessoais sobre a obra.

### 📌 Épico 3: Organização da Biblioteca e Listas (RA2, RA5)

- **US07:** Como **Membro**, eu quero salvar álbuns na minha *Listenlist* (lista de desejos), para que eu me lembre de ouvi-los no futuro.
- **US08:** Como **Membro**, eu quero marcar álbuns como "Favoritos", para que eu possa ter acesso rápido às minhas obras preferidas no meu perfil.
- **US09:** Como **Membro**, eu quero filtrar os álbuns da minha biblioteca por gênero e ano de lançamento, para que eu encontre registros específicos com facilidade.

### 📌 Épico 4: Perfil e Preferências (RA1, RA2)

- **US10:** Como **Membro**, eu quero visualizar minha página de perfil com o resumo de todas as minhas estatísticas, resenhas e biblioteca, para que eu acompanhe minha trajetória musical.
- **US11:** Como **Membro**, eu quero que minhas preferências de interface e dados de sessão fiquem salvos localmente, para que a aplicação lembre das minhas escolhas ao retornar.

## 6. Escopo do MVP

### Must Have

- Busca de artistas e álbuns por meio de uma API pública.
- Visualização das informações de álbuns.
- Registro de álbuns ouvidos.
- Registro da data de audição.
- Sistema de avaliação de 1 a 5 estrelas.
- Escrita e gerenciamento de resenhas.
- Biblioteca pessoal.
- Perfil do usuário.
- Persistência dos dados por meio de uma API fake.

### Should Have

- Sistema de favoritos.
- Listenlist para álbuns que o usuário deseja ouvir.
- Filtros por gênero e ano de lançamento.

### Could Have

- Ordenação do histórico por data, nota ou título.
- Estatísticas pessoais de audição.
- Sugestões de álbuns com base nos gêneros favoritos.

### Won't Have no MVP

- Reprodução de áudio diretamente na aplicação.
- Importação automática do histórico do Spotify, Apple Music ou outros serviços de streaming.
- Sistema de seguidores e interação social entre usuários.

## 7. Requisitos Não Funcionais

- A aplicação deverá possuir uma interface responsiva, adaptada para dispositivos móveis e desktops.
- A interface deverá utilizar um sistema visual consistente de cores, tipografia e componentes.
- Os formulários deverão possuir validações no lado do cliente e mensagens de feedback para o usuário.
- Os dados inseridos pelo usuário deverão ser persistidos por meio de uma API fake.
- A aplicação deverá apresentar mensagens adequadas quando ocorrerem erros durante requisições às APIs.
- A estrutura do projeto deverá ser modular e organizada, facilitando sua manutenção e evolução.