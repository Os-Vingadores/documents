# 🛠️ Processo do Projeto

## 📌 Visão Geral
Este projeto adota a abordagem **Kanban** para gerenciar o fluxo de trabalho. Isso permite acompanhar as atividades de forma contínua, sem necessidade de sprints fechados, facilitando ajustes conforme as prioridades mudam.

## 🧭 Etapas do Fluxo

| Etapa          | Descrição                                                                 |
|----------------|--------------------------------------------------------------------------|
| **Backlog**    | Onde ficam as ideias, melhorias, bugs ou demandas ainda não priorizadas. |
| **To Do**      | Tarefas validadas e prontas para começar.                                |
| **In Progress**| Tarefas em desenvolvimento ou em andamento.                              |
| **Review**     | Tarefas finalizadas aguardando revisão ou testes.                        |
| **Done**       | Tarefas já concluídas e aprovadas.                                       |

## 🧩 Organização das Tarefas (Issues)

Cada tarefa deve conter:

- **Título**: direto ao ponto;
- **Descrição**: com história de usuário no formato:
  > *Como* [papel], *quero* [ação], *para que* [objetivo];
- **Prioridade**:
  - `P0` – Urgente, bloqueia o sistema;
  - `P1` – Importante, mas não bloqueia;
  - `P2` – Desejável, sem impacto crítico;
- **Estimativa**: tempo previsto em horas;
- **Tipo**: `bug`, `feature`, `melhoria`, `documentação`, etc.;
- **Tamanho**:
  - `XS`: tarefa muito simples;
  - `S`: pequena;
  - `M`: média;
  - `L`: grande;
  - `XL`: complexa, envolve pesquisa ou integração externa;
- **Responsável (Assignee)**: quem vai executar;
- **Datas**: de início e de conclusão (quando possível);
- **Labels**: ajudam a filtrar visualmente por tipo de tarefa.

## 🔁 Desenvolvimento e Versionamento

- Cada feature ou correção deve ser feita em **branch própria**, criada a partir da `dev` ou `main`;
- Após o desenvolvimento, deve-se abrir um **Pull Request** para a `dev`;
- A branch `dev` é usada para **homologações** e testes de integração;
- Quando validado, o código é enviado para a `main` (produção);
- **Hotfixes** seguem o mesmo fluxo: uma branch específica, validada e mergeada nas linhas principais.

---

