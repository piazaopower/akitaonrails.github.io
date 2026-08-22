---
title: "Home"
date: 2026-08-22T18:00:00-03:00
---

# Bem-vindo ao Meu Blog

Este é o novo espaço para documentação, tutoriais e anotações técnicas.

---

## Últimos Posts

{{ range first 5 (where .Site.RegularPages "Section" "posts") }}
- [{{ .Title }}]({{ .RelPermalink }}) — {{ .Date.Format "02/01/2006" }}
{{ end }}

[Ver todos os posts →](/posts/)