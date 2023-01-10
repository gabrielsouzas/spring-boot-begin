# Spring Boot Project para iniciantes
Para criar esse projeto na prática são necessárias as seguintes dependências:

* JDK instalado.
* Visual Studio Code instalado.
* Ter as seguintes extensões instaladas no VS Code: Extension Pack for Java e Spring Boot Extension Pack.

# Criação do Projeto

1. Vá até o menu **View** do VS Code e clique em Command Palette...;
2. Digite **java project** na caixa de texto que aparecer;
3. Selecione a opção **Create Java Project** e em seguida clique nos itens conforme a lista:
   * **Tipo do Projeto:** Spring Boot; 
   * **Gerenciador de Dependências:** Maven Project;
   * **Versão Spring Boot:** Selecione a última versão estável, exemplo: **3.0.1**;
   * **Nome do Pacote:** br.com.springbootbegin;
   * **Nome do Artefato:** spring-boot-begin;
   * **Tipo de Empacotamento:** Jar;
   * **Versão Java:** 17;
   * **Dependências:** Spring Web e Thymeleaf.
4. Após a configuração clique no botão **Enter**, uma janela será aberta para a seleção da pasta onde o projeto será criado;
5. Clique no botão **Open** no canto inferior direito do VS Code para abrir o projeto.

# Rodando o Projeto
Para rodar o projeto vá até o Spring Boot Dashboard, localizado no menu lateral esquerdo do VS Code, localize o nome do projeto e clique em **Run**.

Para ver o projeto rodando abra o seu navegador e digite na **URL**: http://localhost:8080/saudacao/{DIGITE QUALQUER COISA AQUI}

# Referências
Este projeto foi desenvolvido utilizando como guia o video do [
Hélio Kamakawa - Configurando JAVA no VS Code](https://youtu.be/K2OD-3NBE6s) e pela leitura da página [
TreinaWeb - O que é o Spring Boot?](https://www.treinaweb.com.br/blog/o-que-e-o-spring-boot)
