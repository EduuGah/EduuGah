# Carlos Eduardo

Desenvolvedor front-end em formação. React, Next.js e TypeScript.
Estudante de Análise e Desenvolvimento de Sistemas na UNIP, 4º semestre.
**Buscando a primeira oportunidade como front-end.**

Já passei por back-end, banco de dados e deploy nos meus projetos pessoais, e foi assim
que descobri onde quero estar: construindo interface. O que eu levo dessa volta é que
autorização é problema de banco, regra de negócio não deve morar dentro de componente,
e projeto que não está no ar não terminou.

```ts
const eduardo = {
  formacao: "Análise e Desenvolvimento de Sistemas — UNIP, 4º semestre",
  foco:     "Front-end",
  stack:    ["React", "Next.js", "TypeScript", "Tailwind CSS"],
  tambem:   ["Node.js", "Supabase", "PostgreSQL", "MongoDB"],
  objetivo: "Primeira oportunidade como desenvolvedor front-end",
};
```

---

## Projetos

### MetaFlow — divisão de projetos em tarefas

Aplicativo web instalável para quebrar projetos pessoais em tarefas e subtarefas. O progresso
é calculado do que foi concluído: não existe barra para arrastar. Importa planos em markdown,
tem quadro kanban e tarefas recorrentes.

Sete dependências de runtime, 65 testes sobre a lógica de negócio, 83 kB no carregamento inicial,
contraste medido token a token e navegação completa por teclado. A separação entre contas é feita
por Row Level Security no PostgreSQL, não por verificação na interface.

`React 19` `TypeScript` `Vite` `Tailwind` `Supabase` `PWA`

**[Ver funcionando](https://meta-flow-psi.vercel.app)** · [Código](https://github.com/EduuGah/MetaFlow)

---

### DineFlow — pedidos em tempo real para restaurantes

O garçom lança o pedido no celular, a cozinha recebe na hora, marca como pronto e o garçom é
avisado. A regra do projeto é que o fluxo principal seja confiável antes de qualquer coisa:
um restaurante tolera um sistema simples, não tolera perder um pedido.

Multi-tenant com isolamento por RLS no banco. Os 105 testes rodam contra um Postgres real com as
migrations de produção aplicadas, e cobrem um restaurante tentando ler dados de outro, garçom
tentando virar admin e dois cliques no botão de enviar. CI roda tipos, lint, testes e build a cada PR.

`Next.js 16` `React 19` `TypeScript` `Supabase` `PostgreSQL` `Realtime`

**[Ver funcionando](https://dine-flow-zeta-snowy.vercel.app)** · [Código](https://github.com/EduuGah/DineFlow)

---

### ForgeFlow — registro de treinos de musculação

Aplicação full-stack para registrar série, carga e repetição durante o treino. Calcula recordes
pessoais de carga e de volume, histórico, consistência e recuperação muscular por grupo. Meu
projeto mais longo, com API própria e versão instalável no Android.

`React` `Node.js` `Express` `MongoDB` `Cloudinary` `PWA` `Capacitor`

**[Ver funcionando](https://forge-flow-five.vercel.app)** · [Código](https://github.com/EduuGah/ForgeFlow)

---

### CutFlow — agendamento para barbearias

O cliente escolhe data, serviço, barbeiro e horário vendo apenas o que está livre de verdade,
sem precisar mandar mensagem perguntando. A barbearia administra profissionais, serviços,
jornada, folgas e bloqueios em um painel próprio.

`React` `TypeScript` `Vite` `Tailwind` `Supabase`

**[Ver funcionando](https://cut-flow-sandy.vercel.app)** · [Código](https://github.com/EduuGah/CutFlow)

---

## Como eu construo

- **Autorização no banco.** Row Level Security no PostgreSQL em vez de checagem no front-end.
- **Regra de negócio fora do React.** Prazos, progressão, disponibilidade e máquina de estados são funções puras, testáveis sem montar componente.
- **Acessibilidade e responsividade verificadas**, não presumidas: teclado, `aria-live`, contraste medido, de 320px a 1920px.
- **Tudo no ar.** Todo projeto acima tem link que abre e funciona.

---

## Tecnologias

| | |
| --- | --- |
| **Uso com confiança** | React, TypeScript, Tailwind CSS, Vite, React Router, Supabase, PostgreSQL, Git |
| **Uso e continuo aprendendo** | Next.js (App Router), Node.js, Express, MongoDB, Vitest, PWA |
| **Já mexi** | Python, Firebase, Capacitor, Kotlin |

---

## Contato

<!-- IMPORTANTE: você tem dois perfis no LinkedIn (in/eduugah e in/carlos-eduardo-863015377).
     Escolha um, defina a URL personalizada e use o mesmo link aqui e na barra lateral do GitHub. -->

- LinkedIn: [EduuGah](https://www.linkedin.com/in/EduuGah/](https://www.linkedin.com/in/carlos-eduardo-863015377/))
- E-mail: edugah1809@gmail.com

Aberto a oportunidades como desenvolvedor front-end júnior ou estágio.
