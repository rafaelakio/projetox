# ProjetoX

Aplicação web Java dinâmica (ProjetoX) projetada para deploy no Apache Tomcat 7.0. Projeto estruturado com Eclipse WTP para serviços web.

## Pré-requisitos

- Java 7 (JDK 1.7)
- Apache Tomcat 7.0
- Eclipse IDE com Web Tools Platform (WTP)

## Instalação

1. Clone o repositório:
```bash
git clone https://github.com/rafaelakio/projetox.git
```

2. Importe o projeto no Eclipse como "Existing Projects into Workspace"
3. Configure o Tomcat 7.0 no Eclipse
4. Execute o projeto no servidor

## Como Usar

- Acesse `http://localhost:8080/ProjetoX/` no navegador
- A aplicação web estará disponível com as funcionalidades implementadas

## Arquitetura

- **`src/`**: Código-fonte Java e lógica de negócio
- **`WebContent/`**: Assets estáticos, JSPs e configuração web
- **`WebContent/META-INF/`**: Metadados JAR/WAR e arquivos de manifesto
- Tecnologias: Java 7, Servlet 3.0, JSP, JavaScript

## Como Contribuir

Veja [CONTRIBUTING.md](CONTRIBUTING.md) para diretrizes de contribuição.

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.
