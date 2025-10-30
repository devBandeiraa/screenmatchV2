# ScreenMatch

Aplicação Java para gerenciamento de séries, temporadas e episódios. O ScreenMatch permite buscar informações sobre séries, salvar dados localmente e gerenciar seu catálogo pessoal de séries favoritas.

## 🚀 Tecnologias

- Java 25
- Spring Boot 3.5.6
- Spring Data JPA
- PostgreSQL
- Maven
- Jackson (para manipulação de JSON)

## 📋 Pré-requisitos

- Java 25 ou superior
- Maven
- PostgreSQL
- Uma chave de API do OMDB (opcional, para busca de séries)

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/screenmatch.git
cd screenmatch
```

2. Configure o banco de dados:
   - Crie um banco de dados PostgreSQL
   - Atualize as configurações de conexão no `application.properties`

3. Execute a aplicação:
```bash
mvn spring-boot:run
```

## 🛠️ Funcionalidades

- Busca de séries por título
- Listagem de temporadas e episódios
- Armazenamento local de séries favoritas
- Consulta de informações detalhadas sobre séries
- Gerenciamento de catálogo pessoal

## 📝 Estrutura do Projeto

```
src/main/java/br/com/jhordan/screenmatch/
├── config/         # Configurações da aplicação
├── model/          # Entidades do domínio
├── principal/      # Lógica principal da aplicação
├── repository/     # Repositórios JPA
└── service/        # Lógica de negócios
```

---

Desenvolvido com ❤️ por Jhordan Bandeira
