# Site Téo Lima — Psicólogo Online

Site institucional de Téo Lima (psicólogo, CRP 03/20310), Consultório Online.

**Produção:** [teolima.com](https://teolima.com)

## Stack

HTML/CSS/JS estático, sem framework. 8 páginas:

- `index.html` — página principal (Hero, Sobre Mim, Abordagem, Especialidades, Como Funciona, Depoimentos, Dúvidas)
- `afirmativa.html`, `compulsao.html`, `luto.html`, `paliativos.html`, `pcd.html`, `psicopatologias.html` — páginas de especialidades
- `marcar-consulta.html` — agendamento

## Hospedagem

Deploy automático via Vercel a cada push na branch `main`. Analytics via GA4, Vercel Web Analytics e Speed Insights.

## Segurança

`vercel.json` define os cabeçalhos de segurança (HSTS, CSP com Trusted Types, X-Frame-Options, entre outros).
