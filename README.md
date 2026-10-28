<div align="center">

[🇧🇷 Português](#-oi-eu-sou-o-bruno-barros) · [🇺🇸 English](#-hi-im-bruno-barros)

</div>

# 🖖 Oi, eu sou o Bruno Barros

Desenvolvedor sênior, back-end de coração, hoje construindo produtos com agentes de IA. Brasileiro, remote-only,
falo PT-BR :brazil: / ES :colombia: / EN 🏴󠁧󠁢󠁥󠁮󠁧󠁿.

## 🚀 Founder & maintainer

| Produto | O que é |
|---|---|
| **[EstagiarIA](https://estagiaria.online)** | Landing pages, sites e sistemas feitos por uma equipe de agentes de IA, com revisão e aprovação do cliente em cada etapa. |
| **[pulpito.tech](https://pulpito.tech)** | Preparo de pregação e de aula da Escola Bíblica Dominical a partir do texto bíblico, com Bíblias e obras de apoio de licença livre. |

## 🤖 A engine por trás: narok

O **narok** (repositório ainda privado) é o harness multi-agente que move a EstagiarIA: recebe 1..N repositórios,
uma issue e N agentes, e entrega branches com a implementação, testes unitários verdes e um relatório.

- **Analista** escreve o plano e divide o trabalho em frentes; **executores** implementam em paralelo; **testadores**
  escrevem e rodam os testes; o próprio harness roda a suíte completa e devolve a falha até ficar verde.
- Cada tarefa roda numa **sandbox descartável** (contêiner sem rede interna, sem segredos, com limites de CPU,
  memória e processos); prompts, orquestração e chaves ficam no control plane.
- Git é exclusivo do harness, comandos destrutivos são bloqueados e testes desligados no diff (`@Disabled`, `.skip`,
  `-DskipTests`) são barrados.

E o desenvolvimento do próprio narok também é feito por agentes, cada um com seu papel: **dev** (implementa um item
por vez), **product owner** (critérios de aceite e regras de produto), **decisor** (pontos em aberto dentro dos
limites que eu defini), **ideia-scout** e **ideia-juiz** (propõem e fazem a triagem de ideias), **marketing**
(copy do site), um **conselho** estratégico (engenharia, produto, UX e marketing), um **advogado** de LGPD/CDC e um
**revisor de código** que trava o deploy quando acha algo bloqueante.

## 🛠️ Stack

**Back-end:** Java (Spring Boot, JPA, JUnit) · Go · Python (FastAPI) · Kafka · RabbitMQ · PostgreSQL<br>
**Front-end:** TypeScript · Angular · Next.js · Payload CMS · Tailwind<br>
**Infra:** Docker · Linux/VPS · Cloudflare<br>
**IA:** orquestração multi-agente, LLMs em produção<br>
**Estudos e hobby:** Rust, C (embarcados, Arduino/ESP32, emulador Chip-8), desenvolvimento de jogos (LibGDX)

## 💚 Open source

Gosto de open source e busco contribuir sempre: código, correções e material para quem está começando.

- **[alerta-master](https://github.com/brunobarros2093/alerta-master)**: extensão gratuita e de código aberto
  (Chrome e Firefox) que avisa quem está ligado ao caso Banco Master, com fonte e a versão de cada um, sem coletar dados.
- **[kafka-4-noobs](https://github.com/brunobarros2093/kafka-4-noobs)** e
  **[golang4noobs](https://github.com/brunobarros2093/golang4noobs)**: guias em português para começar com Kafka e com
  Go (este usado num mini-curso que ministro para times).
- Contribuições em projetos como o **[Eclipse JNoSQL](https://github.com/JNOSQL/demos-se)** e o
  **[He4rtoberfest](https://github.com/he4rt/he4rtoberfest-2022)**.

## ✍️ Conteúdo

Escrevo sobre tecnologia em **[dev.to/brunobarros2093](https://dev.to/brunobarros2093)** e faço build in public.

---

# 🖖 Hi, I'm Bruno Barros

Senior developer, back-end at heart, currently building products with AI agents. Brazilian, remote-only,
I speak PT-BR :brazil: / ES :colombia: / EN 🏴󠁧󠁢󠁥󠁮󠁧󠁿.

## 🚀 Founder & maintainer

| Product | What it is |
|---|---|
| **[EstagiarIA](https://estagiaria.online)** | Landing pages, websites and systems built by a team of AI agents, with the client reviewing and approving each step. |
| **[pulpito.tech](https://pulpito.tech)** | Sermon and Sunday school lesson preparation from the biblical text, with openly licensed Bibles and study resources. |

## 🤖 The engine behind it: narok

**narok** (still a private repository) is the multi-agent harness that powers EstagiarIA: it takes 1..N repositories,
an issue and N agents, and delivers branches with the implementation, green unit tests and a report.

- An **analyst** writes the plan and splits the work into workstreams; **executors** implement in parallel;
  **testers** write and run the tests; the harness itself runs the full suite and sends failures back until it's green.
- Each task runs in a **disposable sandbox** (a container with no internal network, no secrets, and CPU, memory and
  process limits); prompts, orchestration and keys stay in the control plane.
- Git belongs to the harness only, destructive commands are blocked, and tests disabled in the diff (`@Disabled`,
  `.skip`, `-DskipTests`) are rejected.

narok itself is also developed by agents, each with its own role: **dev** (implements one item at a time),
**product owner** (acceptance criteria and product rules), **decider** (settles open questions within the limits I
set), **idea scout** and **idea judge** (propose and triage ideas), **marketing** (site copy), a strategic
**council** (engineering, product, UX and marketing), a **lawyer** for Brazilian privacy and consumer law, and a
**code reviewer** that blocks the deploy when it finds something blocking.

## 🛠️ Stack

**Back-end:** Java (Spring Boot, JPA, JUnit) · Go · Python (FastAPI) · Kafka · RabbitMQ · PostgreSQL<br>
**Front-end:** TypeScript · Angular · Next.js · Payload CMS · Tailwind<br>
**Infra:** Docker · Linux/VPS · Cloudflare<br>
**AI:** multi-agent orchestration, LLMs in production<br>
**Studies and hobbies:** Rust, C (embedded, Arduino/ESP32, Chip-8 emulator), game development (LibGDX)

## 💚 Open source

I love open source and always try to contribute: code, fixes and material for people getting started.

- **[alerta-master](https://github.com/brunobarros2093/alerta-master)**: a free, open source browser extension
  (Chrome and Firefox) that flags who is linked to the Banco Master case, with sources and each party's side, collecting no data.
- **[kafka-4-noobs](https://github.com/brunobarros2093/kafka-4-noobs)** and
  **[golang4noobs](https://github.com/brunobarros2093/golang4noobs)**: Portuguese guides to get started with Kafka and
  Go (the latter used in a mini-course I teach to teams).
- Contributions to projects such as **[Eclipse JNoSQL](https://github.com/JNOSQL/demos-se)** and
  **[He4rtoberfest](https://github.com/he4rt/he4rtoberfest-2022)**.

## ✍️ Content

I write about tech at **[dev.to/brunobarros2093](https://dev.to/brunobarros2093)** and build in public.

---

[![@bbwithpointers's Holopin board](https://holopin.me/bbwithpointers)](https://holopin.io/@bbwithpointers)
