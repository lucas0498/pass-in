# pass.in

## Sobre o Projeto
O pass.in é uma aplicação de gestão de participantes em eventos presenciais. A ferramenta permite que o organizador cadastre um evento e crie uma página pública de inscrição. Os participantes inscritos podem emitir uma credencial para check-in no dia do evento.

### Requisitos Funcionais
- Cadastro de novos eventos pelo organizador.
- Visualização de dados e lista de participantes pelo organizador.
- Inscrição e visualização de crachá de inscrição pelo participante.
- Realização de check-in no evento pelo participante.

### Regras de Negócio
- Inscrição única por participante em cada evento.
- Inscrição permitida apenas em eventos com vagas disponíveis.
- Check-in único no evento pelo participante.

### Requisitos Não-Funcionais
- O check-in é realizado através de um QRCode.

## Tecnologias Utilizadas
- **Java**: Linguagem de programação.
- **Maven**: Ferramenta de automação de compilação.
- **Spring Boot**: Framework para facilitar a configuração e publicação de aplicações.
- **API Rest**: Interface de programação de aplicações para comunicação.
- **HSQL Database**: Sistema de gerenciamento de banco de dados.
- **JPA**: Especificação para persistência de dados em Java.
- **Flyway**: Ferramenta de migração de banco de dados.
- **DTOs**: Objetos de transferência de dados para manipulação de dados.
