# Plano de Desenvolvimento Individual (PDI)

## Objetivo do Semestre

Neste último ano de faculdade, meu foco principal é desenvolver e validar o meu TCC: a **Plataforma Web P2P de Nivelamento Acadêmico**. Como Assistente de Sistemas em transição para me tornar um desenvolvedor com mentalidade de liderança técnica (*lead mentality*), considero essencial não apenas entregar a plataforma, mas construí-la com excelência técnica. 

Até o final deste semestre, quero dominar a arquitetura do projeto utilizando Node.js, TypeScript e React, implementar com sucesso os algoritmos de matchmaking e agendamento, e aplicar práticas sólidas de auditoria de código e debugging. Todo esse conhecimento é fundamental para a minha graduação e para o meu salto profissional na área de desenvolvimento.

---

## Diagnóstico Inicial

### Arquitetura de Software e Desenvolvimento Web
* **O que já sei:** Tenho a base de Node.js, TypeScript e React. Consigo estruturar o início de aplicações e entendo a lógica geral do desenvolvimento web moderno.
* **Dificuldades:** Integrar o back-end e o front-end em uma arquitetura complexa, garantindo que o código seja limpo, escalável e bem estruturado do início ao fim.

### Lógica de Negócio (Matchmaking e Agendamento)
* **O que já sei:** A regra de negócio está definida e validada: conectar alunos que precisam de ajuda acadêmica com aqueles que têm domínio para ensinar.
* **Dificuldades:** Transformar essa regra de negócio em algoritmos eficientes, lidando com a complexidade de cruzar horários disponíveis e perfis de forma otimizada.

### Code Auditing e Debugging
* **O que já sei:** Entendo a importância da qualidade de código e conheço conceitos básicos de revisão e identificação de erros.
* **Dificuldades:** Aplicar um processo rigoroso e autônomo de auditoria no meu próprio código, identificando gargalos de performance e bugs difíceis antes que eles escalem.

### Gamificação e Engajamento
* **O que já sei:** Entendo o conceito de gamificação e como ele pode incentivar o uso da plataforma pelos alunos.
* **Dificuldades:** Implementar os sistemas de pontuação e recompensas no banco de dados e refleti-los dinamicamente na interface em React.

---

## Metas Técnicas

### Meta 1 — Desenvolver e estruturar a API do TCC
* **Contexto:** O coração da plataforma P2P precisa ser robusto para conectar os alunos corretamente.
* **Descrição:** Criar o back-end em Node.js com TypeScript, focando na lógica de perfis, sistema de agendamento e matchmaking.
* **Plano de ação:** Desenhar a modelagem do banco de dados, criar as rotas da API e aplicar técnicas de debugging durante o desenvolvimento.
* **Medição:** Ter o fluxo completo de agendamento entre um aluno tutor e um aluno aprendiz funcionando com sucesso via API.
* **Prazo:** Até o final do segundo mês do semestre.

### Meta 2 — Construir a Interface e Gamificação em React
* **Contexto:** A usabilidade da plataforma determinará o engajamento dos alunos.
* **Descrição:** Desenvolver o front-end da plataforma, consumindo a API construída na Meta 1 e aplicando a interface de gamificação.
* **Plano de ação:** Criar componentes reutilizáveis, gerenciar o estado global da aplicação e integrar os dados de pontuação/perfil na tela.
* **Medição:** Entregar as telas de busca, perfil do usuário e painel de agendamento 100% funcionais e responsivas.
* **Prazo:**

### Meta 3 — Aplicar "Lead Mentality" e Auditoria de Código
* **Contexto:** Desenvolver não apenas como um estudante, mas com o rigor de um desenvolvedor pleno/sênior.
* **Descrição:** Realizar revisões constantes da arquitetura do TCC, garantindo que o código escrito nas Metas 1 e 2 seja escalável, auditável e livre de "code smells".
* **Plano de ação:** Dedicar um dia da semana exclusivamente para refatoração, documentação do projeto e simulação de *code reviews*.
* **Medição:** Ter a base de código do TCC validada sem erros de linting, com documentação clara e pronta para ser defendida perante a banca.
* **Prazo:** Contínuo ao longo de todo o semestre.

---

## Rotina Semanal de Estudo e Desenvolvimento

| Dia da Semana | Horário | Atividade Foco |
| :--- | :--- | :--- |
| **Segunda e Quarta** | 22:30 às 23:30 | Desenvolvimento focado no back-end (Node.js/TypeScript) e integração de regras de negócio (Matchmaking). |
| **Terça e Quinta** | 22:30 às 23:30 | Desenvolvimento do front-end (React), construção de telas e documentação da monografia do TCC. |
| **Sábado** | 09:00 às 11:30 | Auditoria de código, debugging avançado, testes e refatoração estrutural (Prática de Lead Mentality). |

---

## Plano de Uso de IA

Pretendo usar a inteligência artificial como um *pair programmer* sênior. O foco será fazer consultas arquiteturais quando estiver em dúvida sobre qual padrão de design usar no Node.js ou no React, ou pedir auxílio para debugar erros complexos no TypeScript que estejam travando o avanço do TCC. 

Primeiro, tentarei estruturar a lógica do matchmaking, do agendamento e da gamificação por conta própria. A IA entrará como apoio para revisar trechos de código buscando melhorias de performance e segurança (auditoria), garantindo que eu entenda o "porquê" de cada sugestão e não apenas copie o código, absorvendo assim a mentalidade técnica mais avançada que busco para a minha carreira.
