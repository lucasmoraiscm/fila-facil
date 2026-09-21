# 2026-09-21 — Emitir senha

- **Autoria:** Lucas
- **Ferramenta e modelo:** OpenCode com modelo Gemini 3.5 flash lite
- **Trilha:** Local
- **Ambiente:** Local com acesso ao modelo por API

## Ponto de partida

No início, estavam passando 6 testes dos 24 definidos previamente.

## Resultado

| Métrica | Valor |
|---|---|
| Testes passando antes | 6 testes |
| Testes passando depois | 10 testes |
| Tempo total da sessão | 2m e 52s |
| Rodadas até passar | 1 rodada |
| Correções manuais necessárias | sem correções |

## O que precisou de retrabalho

Não foram necessárias correções manuais.

## O que eu entendi do código

O código implementado emite novas senhas, além de atualizar as senhas que estão aguardando e a próxima senha a ser emitida.


# 2026-09-21 — Chamar próxima senha

- **Autoria:** Lucas
- **Ferramenta e modelo:** OpenCode com modelo Gemini 3.5 flash lite
- **Trilha:** Local
- **Ambiente:** Local com acesso ao modelo por API

## Ponto de partida

No início, estavam passando 10 testes dos 24 definidos previamente.

## Resultado

| Métrica | Valor |
|---|---|
| Testes passando antes | 10 testes |
| Testes passando depois | 20 testes |
| Tempo total da sessão | 8s |
| Rodadas até passar | 1 rodada |
| Correções manuais necessárias | sem correções |

## O que precisou de retrabalho

Não foram necessárias correções manuais.

## O que eu entendi do código

O código implementado o procedimento para chamar a próxima senha, no qual a senha é retirada das que estão aguardando e o contador de senhas chamadas é incrementado.


# 2026-09-21 — Reiniciar fila

- **Autoria:** Lucas
- **Ferramenta e modelo:** OpenCode com modelo Gemini 3.5 flash lite
- **Trilha:** Local
- **Ambiente:** Local com acesso ao modelo por API

## Ponto de partida

No início, estavam passando 20 testes dos 24 definidos previamente.

## Resultado

| Métrica | Valor |
|---|---|
| Testes passando antes | 20 testes |
| Testes passando depois | 24 testes |
| Tempo total da sessão | 10s |
| Rodadas até passar | 1 rodada |
| Correções manuais necessárias | sem correções |

## O que precisou de retrabalho

Não foram necessárias correções manuais.

## O que eu entendi do código

O código implementado reinicializa a fila, redefinindo a próxima senha a ser emitida para 1 e a quantidade de senhas aguardando e chamadas para 0.
