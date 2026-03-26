```mermaid
gantt
title Sistema de Cadastro de Empresas Parceiras - TechConnect-Solution
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m

section PLANEJAMENTO (Analista)
Levantamento de requisitos :a1, 2026-01-06, 10d
Documentação Funcional :a2, after a1, 7d

section DESIGN
Rascunhos das telas :b1, 2026-02-06, 10d
Layout do Sitema :b2, after b2, 15d

section CONFIGURAÇÃO
Configuração do ambiente de desenvolvimento :c1, 2026-03-06, 15d
Criação do banco de dados :c2, after c1, 10d

section LOGIN
Programação do módulo de login :crit, d1, 2026-04-06, 10d
Marco E1 - Login validado :milestone, after d1, 0d

section CRUD
Progração do CRUD de empresas :crit, e1, 2026-04-16, 10d
Marco E2 - CRUD validado :milestone, after e1, 0d

section UPLOAD
Implementação de Upload :crit, f1, 2026-05-6, 7d
Marco E3 - Upload validade :milestone, after f1, 0d

section RELATORIOS
Desenvolvimento dos relátorios :crit, g1, 2026-05-13, 7d
Marco E4 - Relatórios validades :milestone, after g1, 0d

section PAINEL
Configuração do painel administrativo :crit, h1, 2026-05-7d
Marco E5 - Painel validado :milestone, after h1, 0d

section TESTES
Testes unitários :crit, i1, 2026-06-06, 7d
Testes de usabilidade :i2, after i1, 10d

section ENTREGA
Implantação final :j1, 2026-06-13, 7d
Entrega ao cliente :j2, after j1, 5d
Marco E6 - Entrega final :milestone, after j2, 0d
```
