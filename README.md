# App-Help-Please

## Descrição do Projeto

O App-Help-Please é uma aplicação desktop desenvolvida em Java, utilizando a biblioteca Swing para a interface gráfica. O projeto parece ser um sistema de abertura e monitoramento de chamados, com funcionalidades de login, cadastro de usuários e visualização de chamados. A autenticação de usuários é realizada diretamente no código, com credenciais pré-definidas para múltiplos usuários.

## Estrutura do Projeto

O projeto está organizado nos seguintes pacotes:

*   **`src/appaberturachamdos`**: Contém a classe principal da aplicação (`AppAberturaChamdos.java`), que serve como ponto de entrada.
*   **`src/view`**: Armazena as classes Java e os arquivos `.form` (gerados pelo NetBeans) que definem as interfaces gráficas do usuário, como telas de login, cadastro, abertura de chamados, monitoramento e visualização de chamados.
*   **`src/Images`**: Contém os recursos de imagem utilizados na interface gráfica da aplicação, como ícones e planos de fundo.

## Funcionalidades Principais

O App-Help-Please oferece as seguintes funcionalidades:

*   **Autenticação de Usuários**: A tela de login (`TelaLogin.java`) permite que usuários pré-definidos acessem o sistema. As credenciais são verificadas diretamente no código-fonte.
*   **Cadastro de Usuários**: Uma tela de cadastro (`TelaCadastro.java`) permite o registro de novos usuários.
*   **Abertura de Chamados**: Usuários podem abrir novos chamados através da interface (`TelaAberturaDeChamados.java`).
*   **Monitoramento de Chamados**: Uma tela dedicada (`TelaMonitoramentoDoChamados1.java`) permite o acompanhamento do status dos chamados.
*   **Visualização de Chamados**: Telas como `TelaVisualizaçãoDoChamados.java` e `TelaVisualizaçãoGodd.java` são responsáveis por exibir detalhes dos chamados.
*   **Avaliação**: Existe uma tela de avaliação (`TelaAvaliação.java`), sugerindo a possibilidade de avaliar serviços ou chamados.
*   **Informações sobre a Empresa**: A tela `TelaSobreAEmpresa.java` fornece informações adicionais.

## Requisitos do Sistema

Para executar o App-Help-Please, você precisará dos seguintes softwares instalados:

*   **Java Development Kit (JDK)**: Versão 8 ou superior.
*   **NetBeans IDE (Opcional)**: O projeto foi desenvolvido no NetBeans, e o IDE facilita a abertura e edição dos arquivos `.form`.

## Como Compilar e Executar

### Usando NetBeans IDE

1.  Abra o NetBeans IDE.
2.  Vá em `File > Open Project...` e selecione a pasta `App-Help-Please-main/AppAberturaChamdos`.
3.  O NetBeans deve reconhecer o projeto automaticamente.
4.  Para compilar, clique em `Run > Clean and Build Project`.
5.  Para executar, clique em `Run > Run Project` ou pressione `F6`.

### Via Linha de Comando (Avançado)

1.  Navegue até o diretório raiz do projeto (`App-Help-Please-main/AppAberturaChamdos`).
2.  Compile os arquivos Java:
    ```bash
    javac -d build/classes src/**/*.java
    ```

3.  Execute a aplicação:
    ```bash
    java -cp "build/classes" appaberturachamdos.AppAberturaChamdos
    ```

## Credenciais de Teste (Tela de Login)

O arquivo `TelaLogin.java` contém credenciais de teste codificadas para acesso ao sistema. Abaixo estão alguns exemplos de usuários e senhas que podem ser utilizados para testar a aplicação:

| Usuário    | Senha |
|------------|-------|
| Diego      | 123   |
| Carol      | 123   |
| Leonardo   | 123   |
| Arthur     | 123   |
| Vinicius   | 123   |
| Bruno      | 123   |
| Gustavo    | 123   |

## Contribuição

Se você deseja contribuir com este projeto, sinta-se à vontade para fazer um fork do repositório e enviar suas pull requests. Para grandes mudanças, por favor, abra uma issue primeiro para discutir o que você gostaria de mudar.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` (se existir) para mais detalhes.

## Autor

Manus AI


