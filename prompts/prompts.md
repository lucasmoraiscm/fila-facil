# 01 — Inspensão

- **Data:** 2026-09-21
- **Autoria:** Lucas
- **Ferramenta:** OpenCode
- **Modelo:** Gemini 3.5 flash lite
- **Trilha:** local
- **Requisito ou critério alvo:** Critério geral do lab

## O que foi pedido

Leia AGENTS.md da raiz, labs/lab-02-fila-facil/AGENTS.md, a especificação completa
e src/fila.js desse lab. Ainda não edite arquivos.
Resuma o contrato, identifique as três funções pendentes e proponha três incrementos.
Explique como verificar cada um e quais arquivos você não pode alterar.
Se tiver ferramentas, mostre as leituras reais. Não imprima chamadas fictícias.

## Contexto fornecido

A ferramenta tinha à disposição arquivos abertos, `AGENTS.md` e os resultado de testes anteriores.

## O que veio

O modelo analisou a estrutura do contrato e as funções estabelecidas. Além do mais, destacou as funções pendentes de implmentação e os incrementos propostos. Ademais, executou a suíte de testes JavaScript via Node. Por fim, citou os arquivos imutáveis do projeto.

## O que eu fiz com isso

Aceitei como veio.


# 02 — Emitir senha

- **Data:** 2026-09-21
- **Autoria:** Lucas
- **Ferramenta:** OpenCode
- **Modelo:** Gemini 3.5 flash lite
- **Trilha:** local
- **Requisito ou critério alvo:** RF-02

## O que foi pedido

Implemente somente o corpo de emitirSenha em labs/lab-02-fila-facil/src/fila.js,
conforme RF-02. Preserve o restante do arquivo, a interface e os testes.
Não implemente as outras duas funções agora. Explique o efeito em cada campo do estado.
Se Node já estiver disponível, execute node labs/lab-02-fila-facil/tests/executar.mjs
na raiz e relate a saída real. Se não estiver, eu executarei a suíte no navegador;
não instale dependências nem declare testes aprovados sem execução.

## Contexto fornecido

A ferramenta tinha à disposição arquivos abertos, `AGENTS.md` e os resultado de testes anteriores.

## O que veio

O modelo modificou a função emitirSenha, destacou os efeitos das modificações em cada campo do estado e executou os testes.

## O que eu fiz com isso

Aceitei como veio.


# 03 — Chamar próxima senha

- **Data:** 2026-09-21
- **Autoria:** Lucas
- **Ferramenta:** OpenCode
- **Modelo:** Gemini 3.5 flash lite
- **Trilha:** local
- **Requisito ou critério alvo:** RF-03 e RF-04

## O que foi pedido

Agora implemente somente chamarProxima em labs/lab-02-fila-facil/src/fila.js.
Cumpra RF-03 e RF-04: atender FIFO, retirar da espera, atualizar a senha atual e
contar chamadas efetivas. Fila vazia retorna null e preserva todo o estado.
Preserve emitirSenha, a interface, reiniciarFila e os testes. Verifique pelo caminho
disponível e explique como tratou o caso vazio. Não acrescente prioridade ainda.

## Contexto fornecido

A ferramenta tinha à disposição arquivos abertos, `AGENTS.md` e os resultado de testes anteriores.

## O que veio

O modelo modificou a função chamarProxima, destacou o tratamento do caso de fila vazia e executou os testes.

## O que eu fiz com isso

Aceitei como veio.


# 04 — Reiniciar fila

- **Data:** 2026-09-21
- **Autoria:** Lucas
- **Ferramenta:** OpenCode
- **Modelo:** Gemini 3.5 flash lite
- **Trilha:** local
- **Requisito ou critério alvo:** RF-05

## O que foi pedido

Implemente somente reiniciarFila em labs/lab-02-fila-facil/src/fila.js, conforme RF-05.
Restaure os quatro campos no mesmo objeto recebido. A confirmação já é feita pela
interface; não coloque confirm(), HTML ou eventos nesta função. Preserve as operações
anteriores e a suíte. Execute a verificação disponível e informe o resultado real.

## Contexto fornecido

A ferramenta tinha à disposição arquivos abertos, `AGENTS.md` e os resultado de testes anteriores.

## O que veio

O modelo modificou a função reiniciarFila e executou os testes.

## O que eu fiz com isso

Aceitei como veio.
