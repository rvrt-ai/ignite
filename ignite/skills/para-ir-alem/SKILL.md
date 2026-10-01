---
name: para-ir-alem
description: Monta ignite/referencias.html com cursos, plugins, skills e leituras para continuar depois do workshop Ignite, com destaques para a área da pessoa. Use só quando a pessoa pedir.
disable-model-invocation: true
---

# Ignite · Para ir além

Esta skill **não faz parte da jornada automática**. Ela só roda quando a pessoa chama `/ignite:para-ir-alem`, no fim do workshop. Nenhuma outra skill a chama nem a sugere.

## Regras

- **Tom.** Português do Brasil. Frases curtas. Sem jargão. Nunca use travessão (o traço longo), nem no chat nem na página. Trate a pessoa por "você".
- **Nome.** Use o nome que está em `ignite/assistente.md`. Se não existir, apresente-se como "o assistente do workshop Ignite da rvrt".
- **Só a curadoria.** Use apenas as referências de `referencias.md` (nesta mesma pasta da skill). Não acrescente link, curso ou repositório que não esteja lá, nem de memória, nem de busca. Não altere nenhum link.
- **Nenhum fato inventado.** O motivo de cada destaque sai do que está em `ignite/perfil.md` e `ignite/planejamento.md` e da descrição do item. Não prometa o que o item não diz.

## Passo 1 · Explicar

Em 2 ou 3 frases, no chat. Exemplo:

> Vou montar uma página com referências para você continuar sozinha depois do workshop: cursos gratuitos, plugins prontos para a sua área e como criar as próximas skills. No topo ficam as que mais combinam com você e com o seu projeto. Todos os links foram conferidos pela rvrt.

## Passo 2 · Ler o contexto

Leia, se existirem: `ignite/perfil.md` (área, cargo, nível de uso de IA), `ignite/planejamento.md` (dor escolhida, caminho da seção 3, "Segunda versão") e `ignite/progresso.md`. Leia `referencias.md` inteiro.

Se `perfil.md` não existir, pergunte numa mensagem só: "Qual é a sua área e como você usa IA hoje: pouco, toda semana ou todo dia?" e siga com a resposta.

## Passo 3 · Escolher de 3 a 5 destaques

Critérios, nesta ordem:
1. **Área.** Itens cuja linha "Áreas" traz a área da pessoa (financeiro, jurídico, comercial, rh, operações, compras, diretoria). Itens "todas" servem para qualquer pessoa.
2. **Projeto.** O que ajuda o próximo passo do projeto dela: a "Segunda versão" da seção 3 e o caminho escolhido (por exemplo, se a segunda versão depende de conector, um item sobre plugins e conectores; se o caminho foi "Dentro do Claude", um item sobre criar a próxima skill).
3. **Nível.** Para quem usa IA pouco, prefira itens "começando". Só destaque item "técnico" se a pessoa programa ou é de TI.
4. **Variedade.** No máximo 2 destaques da mesma categoria. Inclua pelo menos um curso.

Para cada destaque, escreva **uma frase** dizendo por que ele combina com ela, citando algo concreto do perfil ou do projeto. Mostre os destaques no chat, numa lista curta, antes de gerar a página.

## Passo 4 · Gerar a página

1. Leia `modelo-referencias.html`, nesta mesma pasta. Ele já traz o visual rvrt e a **lista completa** montada a partir de `referencias.md`.
2. Copie o modelo para `ignite/referencias.html`.
3. Troque o texto entre colchetes do topo: uma frase ligada ao projeto da pessoa, o nome, a área e o projeto em poucas palavras.
4. Na seção de destaques, deixe um bloco `<div class="d">` por destaque, com a categoria, o nível, o nome, a frase do porquê e o link igual ao do item.
5. Na lista completa, troque `class="item"` por `class="item marcado"` nos itens destacados. Não mude mais nada na lista nem no `<style>`.
6. Apague o comentário de instrução do topo do arquivo.
7. Confira: nenhum colchete sobrando, nenhum travessão, cada link dos destaques igual ao de `referencias.md`.

Se o modelo e `referencias.md` discordarem em algum link, vale o de `referencias.md`.

## Passo 5 · Entregar

Diga onde está e como abrir: "Está em `ignite/referencias.html`. Abre com dois cliques, no navegador. Os links abrem numa aba nova." Pergunte se a pessoa quer trocar algum destaque. Se quiser, troque e gere de novo.

Registre em `ignite/progresso.md` uma linha "Referências geradas em <data>". Não mude a etapa atual.
