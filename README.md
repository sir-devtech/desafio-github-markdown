# Desafio GitHub + Markdown

Lab da DIO pra treinar colaboração. Eu usei o tema do **Shardspire** (jogo que eu tô construindo) e um pouco de **Dota 2**, porque versionar sozinho é fácil — o negócio é não bagunçar o trampo quando outra pessoa entra.

## Por que esse tema

No Dota, se o mid some do mapa e ninguém fala, o time implode. No Git é a mesma coisa: branch sem aviso, commit genérico, PR sem contexto.

O Shardspire ainda tá no começo (trailer, combate, mundo). Antes de crescer o código, eu quis deixar claro o fluxo: quem mexe, o que muda, e como isso chega na `main` sem apagar o trabalho do outro.

## O que eu fiz aqui

- [x] Repo público  
- [x] README em Markdown de verdade (não só um título)  
- [x] Segunda conta como colaboradora: [`vincency3-sys`](https://github.com/vincency3-sys)  
- [x] Issue aberta  
- [x] Branch + pull request + merge  

Dono do repo: [`sir-devtech`](https://github.com/sir-devtech)

## Como eu penso a “partida”

| Momento no Dota | Equivalente no Git |
| --- | --- |
| Draft / pick | Abrir issue e alinhar o que vai entrar |
| Farm na lane | Commit pequeno e com mensagem clara |
| Smoke / gank | Abrir PR pra review antes de mergear |
| Throne | `main` estável, pronto pra build |

Não é tutorial oficial. É o jeito que faz sentido pra mim.

## Clonar

```bash
git clone https://github.com/sir-devtech/desafio-github-markdown.git
cd desafio-github-markdown
```

## Fluxo que rodei

```text
sir-devtech cria o repo e o README
        |
        | convida vincency3-sys
        v
issue #1  ->  branch docs/contribuicao  ->  PR #2  ->  merge
```

Comandos que eu usei de verdade:

```bash
git checkout -b docs/contribuicao
git add README.md
git commit -m "docs: nota do colaborador"
git push -u origin HEAD
```

## Nota do colaborador

Ajuste feito pela conta `vincency3-sys`: entrou na issue, mexeu no README e mandou o PR.  
Issue: #1 · PR: #2

## Shardspire (contexto rápido)

Projeto próprio. Ainda não é o repo do jogo — este aqui é só o exercício de Git/Markdown da DIO, escrito do meu jeito, pra não entregar mais um README de checklist robótico.

> Time que não comunica perde. Código sem PR também.

## Links

- Este repo: https://github.com/sir-devtech/desafio-github-markdown  
- Conta principal: https://github.com/sir-devtech  
- Conta colaboradora: https://github.com/vincency3-sys  
