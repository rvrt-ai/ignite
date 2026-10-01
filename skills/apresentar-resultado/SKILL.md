---
name: apresentar-resultado
description: Monta a apresentação em HTML do resultado do projeto Ignite (ignite/apresentacao.html), só com dados do planejamento. Use apenas quando a pessoa pedir para apresentar o resultado.
disable-model-invocation: true
---

# Ignite · Apresentar o resultado

Esta skill **não faz parte da jornada automática**. Ela só roda quando a pessoa chama `/ignite:apresentar-resultado`, no fim do workshop. Nenhuma outra skill a chama, e ela também não sugere outra skill.

## Regras

- **Leia antes:** `ignite/assistente.md`, `perfil.md`, `planejamento.md` e `progresso.md`, e os arquivos produzidos na execução (o lugar está na seção 3 do planejamento).
- **Tom.** Português do Brasil. Frases curtas. Sem jargão. Nunca use travessão (o traço longo), nem no chat nem nos slides. Trate a pessoa por "você".
- **Nenhum número inventado.** Todo número nos slides está no `planejamento.md` ou nos arquivos produzidos. Cada número de antes, depois e ganho leva a marca "medido" ou "estimado", igual ao planejamento. Se um número não existe, o slide fala disso sem número ou sai da apresentação.
- **Exemplos reais.** O slide "o que foi feito" mostra um trecho de verdade do que foi produzido (uma linha de planilha, uma resposta, um item de relatório), nunca um exemplo inventado. Se o trecho tiver dado pessoal ou sensível, pergunte antes e troque por um exemplo anonimizado.
- **Um ponto por slide.** Um título que afirma uma coisa, e o mínimo para sustentá-la. Texto curto.
- **A pessoa revisa antes.** Nada é dado como pronto sem ela aprovar o roteiro e olhar o arquivo.

## Passo 1 · Conferir se dá para apresentar

Veja `progresso.md` e o planejamento:
- Se a seção 5 (verificação) estiver preenchida, siga.
- Se não estiver, diga o que falta em uma frase e pergunte se a pessoa quer montar mesmo assim. Se sim, os slides de antes e depois e de ganho saem com "a medir", sem número.

## Passo 2 · Explicar e propor o roteiro

Em 2 frases, explique o que vai fazer: "Vou montar a apresentação do seu projeto só com o que está no planejamento e no que a gente produziu. Primeiro te mostro o roteiro, slide por slide, para você aprovar." Depois mostre o roteiro, numa lista, com o título de cada slide e o número ou exemplo que ele usa:

1. **Capa:** título curto do resultado, nome, área, empresa.
2. **A dor:** a dor em uma frase e o número de antes (seção 1).
3. **O que planejamos:** resultado, regras principais, o que fica de fora, "Deu certo se" (seção 2).
4. **Como fizemos:** o caminho e as etapas, com os pontos de revisão (seções 3 e 4).
5. **O que foi feito:** um exemplo real do que foi produzido.
6. **Antes e depois:** os dois números, medidos do mesmo jeito (seção 5).
7. **Ganho medido:** o ganho e a conta (seção 5).
8. **Verificação:** os itens com atendido ou parcial (seção 5).
9. **Próximos passos:** a segunda versão (seções 3 e 5).
10. **Fecho.**

Pergunte: "Quer tirar, trocar ou mudar a ordem de algum? Qual caso real você prefere mostrar no slide 5?" Ajuste até ela aprovar.

## Passo 3 · Gerar o HTML

1. Leia `modelo-apresentacao.html`, nesta mesma pasta da skill. É o modelo visual rvrt.
2. Copie o modelo para `ignite/apresentacao.html` e troque o texto entre colchetes pelo conteúdo aprovado. **Não mude o `<style>`**: é ele que garante o mesmo padrão visual para todo mundo.
3. Apague os slides do modelo que ficaram sem conteúdo e os comentários de instrução.
4. Na barra "depois" do slide de antes e depois, a largura é depois ÷ antes × 100%.
5. O arquivo é autocontido: CSS dentro do próprio arquivo, sem script externo, sem imagem de fora. A única exceção são as fontes do Google Fonts, que já estão no modelo.
6. Confira antes de mostrar: cada número do HTML aparece no planejamento? Tem travessão em algum lugar? Algum colchete ficou sem trocar?

## Passo 4 · Revisão da pessoa

Diga onde está o arquivo e como abrir: "Está em `ignite/apresentacao.html`. Abre com dois cliques, no navegador. Use as setas ou a rolagem para passar os slides." Peça para ela olhar slide por slide e dizer o que mudar. Ajuste e avise quando estiver pronto.

Registre em `ignite/progresso.md` uma linha "Apresentação gerada em <data>". Não mude a etapa atual.
