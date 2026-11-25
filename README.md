# Carlos Serra

**Desenvolvedor de IA e Web | Full Stack (Next.js, Node.js) | Agentes e automação com LLMs em produção**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carlos-augusto-serra/)
[![Site](https://img.shields.io/badge/Site-serra--dev-000000?style=flat&logo=vercel&logoColor=white)](https://serra-dev-next.vercel.app/)
[![Email](https://img.shields.io/badge/Email-carlos.a.serra.dev@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:carlos.a.serra.dev@gmail.com)

## Sobre

Desenvolvo IA e web na TD SYNNEX, em Ribeirão Preto. Antes disso, na Ideatore Americas, construí as plataformas de agentes que a agência opera hoje para conteúdo, e-mail, landing pages e relatórios.

Comecei em SEO técnico, GEO/AEO e analytics, e levei essa cabeça de dados para a engenharia: meço o que construo, valido a saída dos modelos e cuido do custo de cada chamada.

- Trabalhando em: agentes de IA aplicados a fluxos de marketing e produtos próprios
- Azure AI (trilha AI-103), arquitetura de plataformas de IA (RAG, AI Gateway, LLMOps, guardrails) e Spec-Driven Development

## Stack

| | |
|---|---|
| **IA / LLM** | ![LLM APIs](https://img.shields.io/badge/LLM_APIs-444?style=flat) ![MCP](https://img.shields.io/badge/MCP-444?style=flat) ![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-444?style=flat) ![RAG](https://img.shields.io/badge/RAG-444?style=flat) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-444?style=flat&logo=express&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000?style=flat&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat&logo=framer&logoColor=white) |
| **Banco de dados** | ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) |
| **DevOps / Infra** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000?style=flat&logo=vercel&logoColor=white) ![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white) |
| **Analytics / SEO** | ![GA4](https://img.shields.io/badge/GA4-E37400?style=flat&logo=googleanalytics&logoColor=white) ![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white) |

## Projetos

Os de empresa e de cliente têm código privado. Aqui estão o que cada um faz e como foi feito, sem dados de cliente.

| Projeto | Descrição | Stack |
|---|---|---|
| Agent (Ideatore / TD SYNNEX), privado | Plataforma que gera conteúdo com IA para blog, e-mail e relatórios. O Blog Agent roda em etapas (pesquisa, redação, validação, links internos) e está em produção há mais de 5 meses: a equipe publica no blog os artigos que ele gera. O Relatórios Agent é um chat conectado por MCP à plataforma de relatórios e responde com dados reais da conta. | Node.js, Express, MCP, web search, Railway |
| LP Agent (Ideatore / TD SYNNEX), privado | Gera landing pages e páginas de agradecimento por fabricante a partir de um briefing, no padrão visual e de SEO da conta. Em produção. | Node.js, Express, Railway |
| Agente de social media (cliente Ideatore), privado | App em produção que gera o cronograma mensal de posts com texto, arte e kit ZIP. Planeja com dados reais de performance, pesquisa em fontes oficiais e de imprensa, redige e valida cada post, e escolhe fotos por pontuação de qualidade e variedade. Registra o custo de cada etapa em log estruturado. | Next.js 16, TypeScript, Tailwind, MCP, Railway |
| Análise GEO e tráfego de bots (blog TD SYNNEX BR) | Mede quanto tráfego chega por citações de IAs generativas e diagnostica tráfego de bot (datacenters, origem atípica), com regras de WAF e rate limiting para mitigar. | GA4, Cloudflare |
| Banners e SEO/analytics (blog TD SYNNEX BR) | Gestão dos banners do blog e acompanhamento de SEO e analytics, com dados puxados por MCP. | Reportei (MCP), GA4 |
| SEO on-page (site de cliente de tecnologia) | Titles, meta descriptions, hierarquia de H1 e reestruturação de slugs. | SEO técnico |
| Site e painel de banners da Panini Panificadora | Migração do site de WordPress para HTML estático e um painel PHP próprio para o cliente trocar o banner promocional e o link de destino sem mexer em código. Login com bcrypt, CSRF e validação de imagem e de URL. Cada entrega passou por QA visual. | HTML, CSS, PHP 8.4, Playwright, cPanel |
| [projeto-engenharia](https://github.com/carlosserra-dev/projeto-engenharia) | SaaS para uma empresa de engenharia: contratos, orçamento e custos, compras e suprimentos, notas fiscais. Desenvolvido com orquestração multi-agente (specs por tarefa, revisão cruzada, aprovação granular). | TypeScript, Supabase |
| Agente de tratamento de fotos (freelance), privado | Gera imagens de anúncio para vendedores de marketplace a partir da foto real do produto. A composição é feita por código, sem IA generativa mexendo no produto. Protótipo com 8 de 10 imagens do padrão do anúncio. | Python, segmentação de imagem, composição por código |
| [zac-pwa](https://github.com/carlosserra-dev/zac-pwa) | PWA de controle de gastos domésticos para casal, em produção. | Next.js 16, TypeScript, Tailwind, Supabase |
| [serra-dev-next](https://github.com/carlosserra-dev/serra-dev-next) | Site pessoal, meu projeto de aprendizado full stack. | Next.js, TypeScript, Tailwind, Framer Motion, Canvas API |
| [serra-dev](https://github.com/carlosserra-dev/serra-dev) | Primeira versão do site pessoal. | HTML, CSS |
| [kaju-padaria-bistro-site](https://github.com/carlosserra-dev/kaju-padaria-bistro-site) | Site institucional para cliente. | HTML |
| Scaffold de orquestração multi-IA | Orquestrador para experimentar vários provedores de LLM: worktrees isolados por tarefa, contratos JSON entre implementador e revisor, revisão cruzada, build e testes antes do merge, limite de custo por execução e log por etapa. | Node.js, Git |
| Painéis de estudo e de perfil | Painel gamificado de trilha de estudos (missões, XP e progresso salvo) e painel do meu perfil de desenvolvedor. | HTML, CSS, JavaScript |

## Contato

[LinkedIn](https://www.linkedin.com/in/carlos-augusto-serra/) · [Site](https://serra-dev-next.vercel.app/) · [carlos.a.serra.dev@gmail.com](mailto:carlos.a.serra.dev@gmail.com)
