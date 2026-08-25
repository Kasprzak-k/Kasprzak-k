# Olá, sou o Arthur 

Estudante de **Engenharia de Software** na PUC-RS, com foco em desenvolvimento **back-end com Java**.
Hoje divido meu tempo entre projetos pessoais, pesquisa acadêmica via PET e uma iniciativa de desenvolvimento web que estou estruturando no meu trabalho atual. Busco meu primeiro estágio para dar o próximo passo.

📍 Porto Alegre, RS, Brasil

---

## 🎓 Formação & Programas Acadêmicos

**Bacharelado em Engenharia de Software**, PUC-RS (2024 – atual)

**Programa de Educação Tutorial (PET), área de Tecnologia**, PUC-RS *(2026 – atual)*
Membro oficial do PET, programa de excelência acadêmica voltado a ensino, pesquisa e extensão. Atualmente em processo de escolha do laboratório de pesquisa para atuação.

**Ensino Médio**, Nanaimo District Secondary School, Canadá

---

## 🛠️ Tecnologias & Conceitos

**Domínio sólido**
- Java 21: POO, Collections, Lambdas, Generics, Records
- Spring Boot 3.x / 4.x: arquitetura N-Tier, Spring Data JPA, injeção de dependência via construtor, `RestClient`
- Estruturas de Dados: grafos, hashing, heaps, análise de complexidade (Big O)
- Git & GitHub

**Conhecimento aplicado**
- Documentação de API com Swagger UI (springdoc-openapi) para integração com front-end
- Padrão DTO · Lombok · boas práticas de código limpo
- SQL · PostgreSQL · Modelagem relacional · Gerenciamento transacional com `@Transactional`
- Cache com Redis (`@Cacheable`, Spring Cache Abstraction)
- Containerização com Docker & Docker Compose
- Consumo de APIs externas: OpenAQ API, Google Calendar API
- Desserialização JSON com Jackson (`ObjectMapper`)
- Versionamento e colaboração em equipe com Git/GitHub
- Scrum / metodologias ágeis

**Acadêmico**
- C: ponteiros, alocação dinâmica
- Processamento paralelo e distribuído (cursando)

---

##  Projetos

### [ProjetoFinancas2026](https://github.com/Kasprzak-k/ProjetoFinancas2026) — Agregador de Portfólio Financeiro
API REST para gestão financeira pessoal e controle de posições em ativos.
Back-end em **Java 21 + Spring Boot 3.2**, com front-end sendo desenvolvido por colaboradores.

**Stack:** Java 21 · Spring Boot · Spring Data JPA · PostgreSQL · Redis · Docker · Swagger UI · Lombok · Maven

Destaques técnicos:
- Arquitetura em camadas (Controllers → Services → Repositories → Domain)
- Cálculos financeiros com `BigDecimal` e `RoundingMode` para precisão exata
- Cache de portfólio e preços via Redis (`spring-boot-starter-data-redis`)
- API documentada via Swagger UI para integração com o front-end
- Ambiente containerizado com Dockerfile + Docker Compose (app + PostgreSQL + Redis)
- Projeto colaborativo orientado a portfólio

---

### [google-calendar-api](https://github.com/Kasprzak-k/google-calendar-api) — Integração com Google Calendar
API REST que consome a Google Calendar API para listar feriados brasileiros.
Construída com **Spring Boot 4.0** e o novo `RestClient` (substituto moderno do `RestTemplate`).

**Stack:** Java 21 · Spring Boot 4.0 · RestClient · Lombok · Maven

Destaques técnicos:
- Integração com a Google Calendar API v3 via `RestClient`
- Injeção de API Key via `@Value` e `application.properties`
- Arquitetura em camadas: Controller → Service → DTO
- Demonstra consumo de APIs externas autenticadas em Spring Boot moderno

---

### [jsonplaceholder-rest](https://github.com/Kasprzak-k/jsonplaceholder-rest) — REST Client com Spring Boot
Cliente REST que consome a API pública JSONPlaceholder, explorando o `RestClient` do Spring.

**Stack:** Java 17 · Spring Boot 3.2 · RestClient · Maven

Destaques técnicos:
- Consumo de API pública com `RestClient` (API moderna do Spring Web)
- Endpoint `GET /events` expondo dados integrados via `EventService`
- Projeto de estudo aplicado do padrão Service + Controller

---

### [pm25](https://github.com/Kasprzak-k/pm25) — Monitor de Qualidade do Ar (PM2.5)
Aplicação Java que consome a **OpenAQ API** (v3) para buscar dados de qualidade do ar por coordenadas geográficas.

**Stack:** Java 17 · Java HttpClient · Jackson Databind · Maven

Destaques técnicos:
- Consumo de API REST externa com `java.net.http.HttpClient` (sem frameworks)
- Desserialização de JSON com Jackson (`ObjectMapper`) mapeando para Records
- Modelagem com `record` Java para representação imutável de dados (`PM25Result`, `Coordinates`)
- Autenticação via header de API Key (`X-API-Key`)

---

### [ProjeArquitetura](https://github.com/Kasprzak-k/ProjeArquitetura) — Exercícios de Arquitetura de Computadores
Projetos práticos da disciplina de Arquitetura de Computadores, incluindo manipulação de propriedades do sistema em Java e modelagem orientada a objetos.

**Stack:** Java

---

##  Experiência

**BSB Global Company** *(atual)*
- **Iniciativa de Desenvolvimento Web:** à frente da estruturação de uma nova frente de desenvolvimento de sites para clientes da empresa.
- **Prospecção de Leads (BDR):** responsável pela prospecção e comunicação com potenciais clientes para apresentação dos serviços da empresa.

---

## 📬 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arthur_Kasprzak-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/arthur-kasprzak-8716a4358/)
[![Email](https://img.shields.io/badge/Email-kasprzakramos@icloud.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:kasprzakramos@icloud.com)
