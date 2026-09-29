# Aula 06 — Deploy Seguro — Laboratório
Actuator, SCA (Dependency-Check), Dockerfile/Trivy e gates de CI. Parte do **Curso CASE Java (Certified Application Security Engineer)**.

> ⚠️ Aplicação **propositalmente vulnerável**, para fins didáticos. Não use em produção.

## Como rodar (sem Docker, banco H2 em memória)
```bash
git clone https://github.com/tiagocanatelliretechers/curso-case-java-aula-6-deploy-seguro.git
cd curso-case-java-aula-6-deploy-seguro
./scripts/start.sh --no-docker        # Windows: .\scripts\start.ps1 -NoDocker
```
Acesse <http://localhost:8080> — contas: `admin@portal.com/admin123`, `joao@acme.com/senha123`.

## Branches
- **main** — *baseline*: código vulnerável, ponto de partida do laboratório.
- **hardened** — solução de referência: `git checkout hardened` para comparar.

## Materiais (`materiais/`)
- **lab.md** — guia do aluno (autoguiado).
- **roteiro-demonstracao.md** — pré-lab para o **instrutor demonstrar**.
- **lab-aula-6.pptx** — deck do laboratório · **conteudo-…pptx** — teoria.
- **GUIA-DO-INSTRUTOR.md** — a dinâmica de aula e o roteiro.

## Fluxo
1. Leia `materiais/lab.md`. 2. Rode e explore (main). 3. Corrija — ou compare com **hardened**.
