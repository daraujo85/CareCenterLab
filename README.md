# CareCenterLab

O **CareCenterLab** é o projeto-laboratório oficial do curso **"Agentes de Código no Terminal"**, desenvolvido pela **Garagem do Código**. 

Este laboratório serve como ambiente controlado para ensinar e demonstrar o comportamento de agentes autônomos de desenvolvimento de software em cenários reais, porém seguros.

---

## 🏥 Domínio Fictício

O projeto simula um sistema simplificado de gestão para um **centro de cuidado**. É importante reforçar que:
*   Trata-se de um **domínio puramente acadêmico e fictício**.
*   **Não utiliza dados reais** e **não representa nenhum cliente real**.
*   O fluxo de negócios é focado na gestão de:
    *   **Residentes:** cadastro e monitoramento das pessoas assistidas.
    *   **Medicamentos:** controle de prescrições e dosagens.
    *   **Sinais Vitais:** registro de medições biológicas (como temperatura e pressão).
    *   **Alertas:** disparos automáticos caso as medições fujam dos limites aceitáveis.

---

## 🛠️ Stack Tecnológica

O ecossistema é construído sobre tecnologias modernas e robustas do mundo corporativo:
*   **.NET 8**
*   **C#**
*   **ASP.NET Core Web API** (utilizando Minimal APIs)
*   **xUnit** (para a suíte de testes de unidade)

---

## 📂 Estrutura do Projeto

A solução está dividida em duas partes principais:

*   **`CareCenterLab.Api/`**: Contém a aplicação Web API com os endpoints HTTP, regras de negócio e lógica de monitoramento.
*   **`CareCenterLab.Tests/`**: Projeto de testes que referencia diretamente o projeto da API para garantir a cobertura contínua das regras de negócio através de testes unitários.

---

## 💻 Comandos Úteis

Para interagir com o laboratório no terminal, utilize os seguintes comandos oficiais:

*   **Compilar o projeto:**
    ```bash
    dotnet build
    ```
*   **Executar a suíte de testes:**
    ```bash
    dotnet test
    ```
*   **Rodar a API localmente:**
    ```bash
    dotnet run --project CareCenterLab.Api
    ```

---

## 🤖 Trabalho com Agentes de Código

No âmbito do curso, os agentes interagem com o repositório seguindo diretrizes rigorosas de engenharia de software:

1.  **Trabalhar em Branches Claras:** O desenvolvimento deve ocorrer em branches específicas de feature ou laboratório (como a branch atual `lab/setup-agentes`).
2.  **PLANO Antes de Alterar:** Antes de realizar qualquer modificação em arquivos de código, o agente deve ler o contexto atual, formular e propor um plano de ação para aprovação do usuário.
3.  **Seguir Tarefas Definidas:** As metas e o escopo de atuação estão listados sequencialmente no arquivo `LAB_TASKS.md`.
4.  **Commits Pequenos com Intenção:** Commits devem ser atômicos, focados e acompanhados de mensagens claras que expliquem a intenção por trás das alterações.
