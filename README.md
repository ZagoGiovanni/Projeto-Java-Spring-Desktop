<h1 align="center">Lista de Tarefas - Aplicação Desktop</h1>
<p align="center">Cliente Desktop para o sistema de gerenciamento de tarefas (To-Do List), desenvolvido com JavaFX.</p>

<p align="center">
  <img src="https://img.shields.io/badge/JavaFX-21-orange?style=for-the-badge&logo=openjfx" alt="JavaFX 21">
  <img src="https://img.shields.io/badge/Java-21-blue?style=for-the-badge&logo=java" alt="Java 21">
  <img src="https://img.shields.io/badge/Maven-4-red?style=for-the-badge&logo=apache-maven" alt="Maven">
</p>

<details>
  <summary><strong>📝 Sobre o Projeto</strong></summary>
  <br>
  Esta é a aplicação cliente de Desktop para o sistema "Lista de Tarefas". Ela oferece uma experiência nativa para o usuário, consumindo a mesma API REST que a versão web, permitindo o gerenciamento de tarefas diretamente do computador.

  O projeto foi desenvolvido seguindo o tutorial "Projeto Aplicação Full Stack" do professor Ricardo Tec.
</details>

## 🏛️ Arquitetura da Solução

Este projeto corresponde à aplicação Desktop da solução "Lista de Tarefas". A arquitetura completa é modularizada em três repositórios independentes.

* **Desktop (Esta Aplicação):** Cliente Desktop desenvolvido com JavaFX.
* **Backend (API REST):** API RESTful desenvolvida com Spring Boot que serve como o núcleo da aplicação.
    * ➡️ **Link para o repositório:** `https://github.com/ZagoGiovanni/Projeto-Java-Spring-API`
* **Frontend (Web):** Interface web desenvolvida com Angular.
    * ➡️ **Link para o repositório:** `https://github.com/ZagoGiovanni/Projeto-Java-Spring-Web`

## 💻 Tecnologias Utilizadas

- **JavaFX 21**
- **Java 21**
- **Maven**
- **Scene Builder** (para a interface gráfica)

## 🚀 Como Executar o Projeto

### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina:
* [Java (JDK)](https://www.oracle.com/java/technologies/downloads/) - Versão 21 ou superior.
* [JavaFX SDK](https://gluonhq.com/products/javafx/) - Configurado em sua IDE.
* [Maven](https://maven.apache.org/download.cgi) - Versão 3.8 ou superior.
* [Git](https://git-scm.com/downloads).
* **A API REST precisa estar em execução** para que o cliente desktop funcione.

### Rodando a Aplicação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/seu-usuario/lista-tarefas-desktop.git](https://github.com/seu-usuario/lista-tarefas-desktop.git)
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd lista-tarefas-desktop
    ```

3.  **Execute a aplicação via Maven:**
    ```bash
    mvn javafx:run
    ```

4.  Alternativamente, importe o projeto em sua IDE preferida (IntelliJ, Eclipse) e execute a classe principal.

## Autor

**Giovanni dos Santos Zago**

- LinkedIn: `https://www.linkedin.com/in/giovanni-zago-058891290/`
- GitHub: `https://github.com/ZagoGiovanni`
