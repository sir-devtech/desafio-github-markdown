# Desafio GitHub Markdown

Lab da DIO: **Explorando Colaboração e Markdown**.

Repo público para praticar Git/GitHub de verdade — README formatado, colaborador, issue, commits em duas contas e pull request.

## Objetivo

Montar um repositório que mostre o básico do fluxo profissional:

1. Conta no GitHub  
2. Repositório público com `README.md`  
3. Colaboração (segunda conta ou colega)  
4. Formatação com Markdown  

## Contas usadas

| Papel | Conta |
| --- | --- |
| Dono do repo | [`sir-devtech`](https://github.com/sir-devtech) |
| Colaborador | [`vincency3-sys`](https://github.com/vincency3-sys) |

## Passo a passo que eu executei

1. Criei o repositório público `desafio-github-markdown`  
2. Escrevi este README com Markdown (títulos, tabelas, listas, código, links)  
3. Convidei `vincency3-sys` como colaborador  
4. Abri uma issue descrevendo a melhoria  
5. A segunda conta criou uma branch, fez commit e abriu um pull request  
6. Mergeei o PR na `main`  

## Como clonar

```bash
git clone https://github.com/sir-devtech/desafio-github-markdown.git
cd desafio-github-markdown
```

## Exemplos de Markdown usados aqui

### Lista de tarefas

- [x] Repo público  
- [x] README formatado  
- [x] Colaborador adicionado  
- [x] Issue aberta  
- [x] Pull request mergeado  

### Código inline e bloco

Comando útil: `git status`

```bash
git checkout -b docs/contribuicao
git add .
git commit -m "docs: contribui no README como colaborador"
git push -u origin HEAD
```

### Citação

> “Se o expert forneceu um repositório, você pode dar um fork… ou adicionar um colaborador (pode ser você mesmo com outra conta).” — orientação da DIO

### Tabela rápida de comandos

| Comando | Para quê |
| --- | --- |
| `git clone` | Baixar o repo |
| `git checkout -b` | Criar branch |
| `git commit` | Registrar mudança |
| `gh pr create` | Abrir pull request |

## Colaboração

Fluxo deste desafio:

```text
sir-devtech (main)
        |
        | convida vincency3-sys
        v
branch docs/contribuicao  -->  Pull Request  -->  merge na main
```

## Links

- Repo: https://github.com/sir-devtech/desafio-github-markdown  
- Dono: https://github.com/sir-devtech  
- Colaborador: https://github.com/vincency3-sys  

## Observação

Desafio bem direto (e um pouco tosco mesmo), mas cobre o que importa no mercado: versionar, colaborar e documentar.
