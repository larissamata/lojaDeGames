# Loja de Games

## Descrição do Projeto:

Esse é um sistema de loja de games desenvolvido utilizando **Java, Spring Boot e SQL**, com testes realizados no Insomnia. O projeto permite o gerenciamento de produtos e categorias, facilitando a organização e consulta de informações sobre os jogos disponíveis na loja.


## Tecnologias Utilizadas: 

- Java

- Spring Boot

- Spring Data JPA

- Banco de Dados MySQL

- Jakarta Persistence API (JPA)

- Insomnia (para testes de API)
  

## Funcionalidades: 

- Cadastro, consulta, atualização e remoção de produtos.

- Cadastro, consulta, atualização e remoção de categorias.

- Relacionamento entre categorias e produtos.


## Como Executar o Projeto: 

1. **Clone o repositório**:

```

git clone https://github.com/larissamata/lojaDeGames.git

```


2. **Acesse a pasta do projeto**:

```

cd lojaDeGames

```


3. **Configure o banco de dados**:

- Certifique-se de ter um banco de dados SQL configurado.

- Atualize as configurações de conexão no arquivo application.properties.


4. **Execute o projeto**:

- Abra o terminal e navegue até a pasta raiz do projeto (onde está o arquivo pom.xml).
  
- Execute o seguinte comando para iniciar a aplicação:

```

mvn spring-boot:run

```

- Se tudo estiver correto, o servidor Spring Boot será iniciado na porta 8080 (ou outra configurada).


5. **Testes no Insomnia**:

- Utilize o Insomnia para testar as requisições GET, POST, PUT e DELETE.

- Os endpoints estão documentados abaixo.

## Endpoints da API: 

### Categoria:

- **GET** `/categorias` - Consulta todas as categorias
  
- **GET** `/categorias/{id}` - Consulta categoria por ID
  
- **GET** `/categorias/descricao/{descricao}` - Consulta categoria por descrição

- **POST** `/categorias` - Cria uma nova categoria

- **PUT** `/categorias/{id}` - Atualiza uma categoria existente

- **DELETE** `/categorias/{id}` - Deleta uma categoria

### Produto:

- **GET** `/produtos` - Consulta todos os produtos

- **GET** `/produtos/{id}` - Consulta produto por ID

- **GET** `/produtos/nome/{nome}` - Consulta produto por nome

- **POST** `/produtos` - Cria um novo produto

- **PUT** `/produtos/{id}` - Atualiza um produto existente

- **DELETE** `/produtos/{id}` - Deleta um produto

## Melhorias Futuras:

- Implementação de autenticação e autorização com Spring Security.

- Interface gráfica para facilitar a interação do usuário.

- Integração com serviços de pagamento.

## Autora:

💻🌟 Desenvolvido por: Larissa Mata. 

