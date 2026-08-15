# DevPrint

> Seu currículo cresce com você. Cada projeto é uma prova. Cada produto, sua marca.

**DevPrint** é uma plataforma que transforma o histórico real de desenvolvimento de um programador — commits, pull requests, diffs e registros de aprendizado — em um portfólio vivo, narrativo e auto-atualizável, com evidências rastreáveis de trabalho real.

Currículos autodeclarados não convencem recrutadores técnicos. O DevPrint resolve isso: em vez de afirmações, entrega evidências — código real, datas reais, tecnologias reais, incluindo projetos privados.

🌐 [English](./README.en.md) · [Español](./README.es.md)

---

## O que faz

- Conecta repositórios GitHub (públicos **e** privados) via OAuth
- Importa currículo (PDF, LinkedIn ZIP ou formulário)
- Integra Diário de Aprendizado manual
- Detecta automaticamente o que foi praticado vs. aprendido do zero
- Gera narrativa em linguagem natural aprovada pelo próprio dev
- Publica perfil público em `devprint.io/username` com evidências rastreáveis
- (V2) Vitrine de produtos do dev em `devprint.io/username/solucoes`

---

## Status

| Milestone | Descrição | Status |
|---|---|---|
| M1 | Fundação (scaffold, auth GitHub OAuth, banco) | ⬜ Pendente |
| M2 | Portfólio Core (import repo, diário, narrativa IA) | ⬜ Pendente |
| M3 | Perfil público + validação dev | ⬜ Pendente |
| M4 | Monetização (planos Pro e Teams) | ⬜ Pendente |
| M5 | Vitrine de produtos (V2) | ⬜ Pendente |

---

## Stack

| Camada | Tecnologia |
|---|---|
| Framework | Next.js (App Router) · TypeScript |
| Styling | Tailwind CSS |
| Backend | Supabase (PostgreSQL · Auth · RLS) |
| Jobs assíncronos | Inngest |
| IA | Anthropic Claude API (análise de evolução · geração de narrativa) |
| CI/CD | Vercel · GitHub Actions |

---

## Contato

Sugestões e parcerias via site oficial da Kairos Labs:
**[kairos-labs-lake.vercel.app/pt](https://kairos-labs-lake.vercel.app/pt)**

---

## Licença

**Todos os direitos reservados** — Cesar Antonio Brito Pizarro / Kairos Labs

Veja [LICENSE](./LICENSE) · [LICENSE.en](./LICENSE.en) · [LICENSE.es](./LICENSE.es)
