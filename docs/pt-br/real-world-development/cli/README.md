---
slug: pt-br/real-world-development/cli
title: "CLI do GitHub Copilot"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

O **[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** coloca o GitHub Copilot no seu terminal como um assistente de programação baseado em agentes. Ele explora bases de código, gera código, executa comandos e se conecta a ferramentas externas — tudo pela linha de comando, para que você mantenha o foco sem trocar para um editor gráfico.

Ao longo destas lições, você instalará e autenticará o Copilot CLI, depois fornecerá contexto do projeto com instruções personalizadas antes de usar o modo plan para gerar um recurso de forma deliberada. Você conectará o servidor MCP do Playwright para testar esse recurso em um navegador real e, em seguida, ampliará o Copilot com skills de agente reutilizáveis e agentes personalizados. Por fim, você explorará comandos de barra para gerenciar contexto, modelos e compartilhamento, e concluirá com uma revisão do que criou. Você também pode seguir uma [série opcional de três módulos com GitHub Copilot CLI e Foundry][foundry] para preparar um modelo, criar e implantar um agente hospedado e integrá-lo ao site.

## Lições

| Lição | Tópico | Descrição |
|----------|-------|-------------|
| [0. Pré-requisitos][ex0] | Configuração | Crie seu repositório e seu codespace |
| [1. Instalar o Copilot CLI][ex1] | Instalação | Instale e autentique o Copilot CLI |
| [2. Adicionar classificações por estrelas][ex2] | Primeira alteração | Exiba classificações existentes e mescle seu primeiro PR |
| [3. Modos de agente][ex3] | Modos de agente | Planeje e implemente uma funcionalidade com os modos Plan e Autopilot |
| [4. Instruções personalizadas][ex4] | Contexto | Explore e atualize instruções para orientar o Copilot |
| [5. Skills de agente][ex5] | Verificações reutilizáveis | Personalize uma skill e execute as verificações do projeto |
| [6. Validar com o MCP do Playwright][ex6] | Observação no navegador | Configure o MCP e inspecione o comportamento da filtragem |
| [7. Criar e usar um agente de QA][ex7] | Requisitos e cobertura | Crie um perfil especializado e reúna evidências de verificação |
| [8. Criar e mesclar o PR da funcionalidade][ex8] | Revisão e mesclagem | Revise a alteração completa e crie o PR |
| [9. Ferramentas avançadas da CLI][ex9] | Recursos da CLI | Explore contexto, modelos, compartilhamento e delegação |
| [10. Encerramento e próximos passos][ex10] | Resumo | Revise o fluxo de trabalho e os recursos reutilizáveis |
| [Opcional: Incorpore o Foundry][foundry] | Agentes hospedados | Prepare um modelo, crie e implante um Backer Concierge baseado no catálogo e conecte-o ao site |

## Pré-requisitos

Antes de participar deste workshop, verifique se você tem:

- [ ] Uma conta do GitHub com um plano ativo **Copilot Student, Pro, Pro+, Business ou Enterprise**
- [ ] Familiaridade básica com operações de terminal e linha de comando
- [ ] O Git instalado e configurado

> [!TIP]
> Não tem um plano pago? Estudantes verificados podem obter o GitHub Copilot gratuitamente por meio do [GitHub Education][callout-student-plan-education]. O plano **Copilot Student** inclui os recursos de agente, MCP, revisão de código e Copilot CLI usados neste workshop. Portanto, você pode concluir todos os percursos com esse plano.

> [!NOTE]
> Se você usa o Copilot Business ou o Copilot Enterprise, verifique se o administrador habilitou o Copilot CLI para uso.

## Começar

[**Comece pela Lição 0: Pré-requisitos →**][ex0]

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[foundry]: 8-foundry-agent/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[callout-student-plan-education]: https://github.com/education/students
