<h1 align="center">:musical_note: Screen Sound Music :musical_note:</h1>

<p align="center">Screen Sound Music é uma aplicação Java desenvolvida com Spring Boot para gerenciar artistas e músicas, além de permitir consulta de informações sobre artistas utilizando a API do ChatGPT.</p>

## :gear: Funcionalidades

- **Cadastro de Artistas:** Permite cadastrar artistas do tipo solo, dupla ou banda.
- **Cadastro de Músicas:** Associa músicas aos artistas cadastrados.
- **Listagem de Músicas:** Exibe todas as músicas cadastradas no sistema.
- **Busca de Músicas por Artista:** Permite buscar músicas de um artista específico.
- **Pesquisa de Artistas:** Utiliza a API do ChatGPT para obter informações sobre um artista.

## :computer: Tecnologias Utilizadas

- Java
- Spring Boot
- Maven
- OpenAI Java Client

## :arrow_forward: Como Executar

1. **Clone o repositório:**
   ```sh
   git clone https://github.com/gyselle-marques/ScreenSoundMusic.git
   ```
2. **Configure a variável de ambiente com sua chave da OpenAI:**
    - No Windows:
      ```sh
      set OPENAI_APIKEY=sua-chave-aqui
      ```
3. **Execute a aplicação:**
   ```sh
   mvn spring-boot:run
   ```
4. **Ao iniciar, um menu interativo será exibido no terminal, permitindo navegar pelas opções de cadastro, listagem e pesquisa.**

## :warning: Observações

- É necessário possuir uma chave de API válida da OpenAI para utilizar a funcionalidade de pesquisa de artistas.
- O projeto utiliza um repositório JPA para persistência dos dados.

## :page_facing_up: Licença

Este projeto está sob a Licença MIT.
