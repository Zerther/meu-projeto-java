# Meu Projeto Java com Gradle

Este é um projeto de exemplo em **Java 21+** utilizando **Gradle Kotlin DSL** no ambiente WSL2.

Exemplo simples de ambiente moderno para projetos Java rodando dentro do WSL integrado ao VS Code, pronto para uso com Gradle e SDKMAN.

## Estrutura do Projeto

meu-projeto-java/
├── app/ # Código fonte e testes da aplicação

│ ├── build.gradle.kts

│ └── src/

├── gradle/ # Configurações e wrapper do Gradle

├── gradle.properties # Propriedades globais do Gradle

├── gradlew / gradlew.bat

├── settings.gradle.kts

├── .vscode/ # Configurações locais para VS Code


## Como executar

```bash
./gradlew :app:run

Hello World!


## Requisitos
WSL2

JDK Corretto (via SDKMAN)

Gradle (via SDKMAN)

VS Code + Extensão Java
