# SPRING + AI

Este é um projeto que combina Spring Boot com Spring AI para criar uma API inteligente.

## 🚀 Tecnologias Utilizadas

- Java 24
- Spring Boot 3.4.4
- Spring AI 1.0.0-M7
- Maven

## 📋 Pré-requisitos

- Java 24 ou superior
- Maven
- Uma chave de API do OpenAI (para integração com Spring AI)

## 🔧 Configuração

1. Clone o repositório:
```bash
git clone git@github.com:Lucasmaciiel/spring-ia.git
```

2. Configure as variáveis de ambiente:
   - Crie um arquivo `.env` na raiz do projeto
   - Adicione sua chave de API do OpenAI:
   ```
   OPENAI_API_KEY=sua_chave_aqui
   ```

3. Instale as dependências:
```bash
mvn clean install
```

## 🏃‍♂️ Executando o Projeto

Para iniciar o projeto, execute:

```bash
mvn spring-boot:run
```

O servidor estará disponível em `http://localhost:8080`

## 📚 Documentação da API (Em andamento)

A documentação da API estará disponível em:
- Swagger UI: `http://localhost:8080/swagger-ui.html`

## 🧪 Testes

Para executar os testes:

```bash
mvn test
```

## 📦 Estrutura do Projeto

```
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── lmg/
│   │           └── api/
│   │               └── ai/
│   └── resources/
└── test/
```

## 🤝 Contribuindo

1. Faça um Fork do projeto
2. Crie uma Branch para sua Feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a Branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📝 Licença

Este projeto está sob a licença [MIT](LICENSE).

## 👥 Autores

- Lucas Maciel de Gois - lucasmacielgois@gmail.com
