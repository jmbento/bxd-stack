# bxd-stack

**Setup automatizado de infraestrutura em 1 comando**

GitHub + Vercel + Supabase + n8n configurados e conectados automaticamente.

## Como Funciona

Você termina um projeto no Google AI Studio, gera o código, e a partir daqui:

```bash
python3 setup.py seu-projeto-aqui
```

**Prontão!** Seu projeto está em:
- GitHub (repo criado)
- Vercel (deployment próximo)
- Supabase (database pronto)
- .env.local (variáveis geradas)

## Pré-requisitos

Tenha essas variáveis de ambiente configuradas:

```bash
export GITHUB_TOKEN="seu_token_github"
export VERCEL_TOKEN="seu_token_vercel"
export SUPABASE_KEY="sua_chave_supabase"
export SUPABASE_URL="sua_url_supabase"
```

## Status

- [x] Repositório criado
- [ ] Script Python funcional (SPRINT 1)
- [ ] Integração GitHub API
- [ ] Integração Vercel API
- [ ] Integração Supabase
- [ ] n8n automation
- [ ] Templates de projetos
- [ ] Versão Pro com Dashboard

## Roadmap

**Janeiro 2026**: MVP + testes com micro SaaS reais
**Fevereiro**: Beta pública
**Março**: Primera versão paga

---

Mantido por [@jmbento](https://github.com/jmbento)
