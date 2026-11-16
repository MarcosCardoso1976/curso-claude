# Claude Code: do zero ao avançado

Curso interativo e gratuito de Claude Code, em português, com 52 aulas, testes rápidos e 4 projetos práticos.

## 👉 Acesse o curso

**https://marcoscardoso1976.github.io/curso-claude/**

Não precisa de cadastro nem de instalação: é só abrir no navegador (computador ou celular).

---

## Para quem é

| Seu nível | Por onde começar |
|---|---|
| Nunca usei o Claude Code | Módulo **Essencial** |
| Já uso no dia a dia | Módulo **Intermediário** |
| Quero automatizar, integrar e escalar | Módulo **Avançado** |
| Aprendo fazendo | Módulo **Projetos** |

Pré-requisitos: saber o básico de terminal e de Git. Para os projetos, ter Node.js instalado e uma conta no GitHub. Para usar o Claude Code, é necessária uma conta Claude (plano pago) ou uma chave de API.

---

## Como o curso está organizado

### 1. Essencial (6 aulas)
1. O que é o Claude Code
2. Instalação e primeira sessão
3. Sessões e comandos essenciais
4. CLAUDE.md: memória do projeto
5. Permissões e Plan Mode
6. Prompts eficazes e erros comuns

### 2. Intermediário (9 aulas)
1. Hierarquia de configurações
2. Gestão de contexto a fundo
3. Modelos e esforço
4. Skills e slash commands
5. MCP: conectando ferramentas externas
6. MCP a fundo
7. Hooks: automação garantida
8. Git e GitHub no dia a dia
9. Claude Code no VS Code, JetBrains e Desktop

### 3. Avançado (10 aulas)
1. Subagents e trabalho em paralelo
2. Agent teams e worktrees
3. Hooks avançados: bloqueios e validações
4. Criando seu próprio servidor MCP
5. Plugins e marketplaces
6. Headless, CI, plugins e custos
7. GitHub Actions: bot revisor de PRs
8. Agent SDK: construindo seus agentes
9. Segurança para equipes
10. Custos e repositórios grandes

### 4. Projetos (24 aulas)
Cada projeto tem uma aula de **preparação** e **5 etapas**, com prompts prontos, checklist de entrega e desafios extras.

| Projeto | O que você constrói | O que você pratica |
|---|---|---|
| **1. TaskFlow** | App de tarefas com Next.js, TypeScript e SQLite | CLAUDE.md, permissões, Plan Mode, skill, hook e subagent |
| **2. notas-cli** | Ferramenta de linha de comando em Node e TypeScript | Especificação, TDD e publicação de pacote |
| **3. Bot PR** | Revisor automático de pull requests | Modo headless, saída JSON, GitHub Actions e segurança |
| **4. Plugin** | Plugin `time-toolkit` com skill, agent, hook e MCP | Empacotamento, teste local e marketplace |

### 5. Extras (3 aulas)
- Atualizando o curso toda semana
- Glossário de comandos
- Novidades da semana

---

## Como aproveitar

- **Siga a ordem do menu.** Cada aula termina com um teste rápido.
- **Seu progresso é salvo no navegador:** a aula atual, as respostas e os ✓ de cada módulo. Ele não passa de um dispositivo para outro.
- **Use a busca** no topo para achar um tema (por exemplo: `hooks`, `MCP`, `worktree`).
- **Copie os comandos** com o botão *Copiar* nos blocos de código.
- **Faça os exercícios "mão na massa".** Você aprende mais executando do que lendo.
- Faça **um commit antes de cada etapa dos projetos**, para poder desfazer qualquer erro.

---

## Atualizações

O Claude Code muda rápido, então o curso é revisado toda semana. A aula **Novidades da semana** reúne as mudanças recentes de versões, modelos e permissões, e cada aula mostra a data da última revisão.

Alguns detalhes, como nomes de flags, eventos de hooks, pacotes do Agent SDK e comandos de marketplace, podem mudar entre versões. Em caso de dúvida, a fonte oficial é a documentação em **https://code.claude.com/docs**.

---

## Rodar localmente

O curso é um único arquivo, sem dependências:

```bash
git clone https://github.com/MarcosCardoso1976/curso-claude.git
cd curso-claude
# abra o index.html no navegador, ou sirva a pasta:
npx serve .
```

## Publicação

O site é servido pelo **GitHub Pages**, a partir da branch `main` (pasta raiz). Para atualizar, edite o `index.html`, faça commit e push. Em 1 a 2 minutos a nova versão está no ar.

---

## Observação

Este é um material de estudo independente e não é um produto oficial da Anthropic. Claude e Claude Code são produtos da Anthropic.
