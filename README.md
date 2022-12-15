# Lojinha API Automação
Esse é um repositório que possui alguns testes de API Rest de uma software chamado de Lojinha. Os sub-tópicos abaixo descrevem algumas decisões tomadas na estruturação do projeto.

## Tecnologias Utilizadas
- Java
  https://www.oracle.com/java/technologies/javase/jdk18-archive-downloads.html
- Junit
  https://mvnrepository.com/artifact/org.junit.jupiter/junit-jupiter-engine/5.8.2
- RestAssured
  https://mvnrepository.com/artifact/io.rest-assured/rest-assured/5.0.0
- Maven
  https://maven.apache.org

## Testes Automatizados
Testes para validar as partições de equivalência relacionadas ao valor do produto na Lojinha, que estão vinculadas diretamente a regra de negócio que diz que o valor do produto deve estar entre R$ 0,01 e R$ 7.000,00

## Notas Gerais
- Sempre utilizamos a anotação Before Each para capturar o token que será utilizado posteriormente nos métodos de teste
- Utilização de classes POJO
- Dados iniciais de classe Data Factory
- É utilizado o Junit 5 para usar a anotação DisplayName, para descrever os casos de teste em PT