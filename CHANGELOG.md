# Changelog

Todas as mudanças relevantes deste projeto são documentadas neste arquivo.

O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/)
e o projeto adota o [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [1.1.0] - 2026-09-27

### Adicionado

- Testes para notas inválidas.
- Formatação da média com uma casa decimal.
- Situação "Aprovado com distinção".

### Alterado

- Cálculo da média reescrito sem o laço `for`.

### Corrigido

- Situação de alunos com média exatamente 7,0.

## [1.0.0] - 2026-09-14

### Adicionado

- Cálculo da média aritmética das notas.
- Classificação da situação do aluno: Aprovado, Recuperação ou Reprovado.
- Execução pela linha de comando (`npm start -- <notas>`).
- Integração contínua com testes e verificação de Conventional Commits.