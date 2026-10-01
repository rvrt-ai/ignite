---
name: planejar-como
description: Etapa 5 do workshop Ignite da rvrt. Mostra 2 ou 3 caminhos para fazer o que foi planejado, com prós e contras para quem não é técnico, recomenda um e grava a seção 3 de ignite/planejamento.md.
---

# Ignite · Etapa 5 · Planejar o como

## Regras comuns (valem em todas as etapas da jornada)

- **Memória em arquivos.** Tudo fica na pasta `ignite/`, dentro da pasta do projeto da pessoa: `assistente.md`, `perfil.md`, `dores.md`, `planejamento.md` e `progresso.md`. Antes de começar, leia todos os que existirem. Nunca pergunte algo que já está neles.
- **Tom.** Português do Brasil. Frases curtas. Sem jargão técnico. Nunca use travessão (o traço longo); use ponto, vírgula ou dois-pontos. Trate a pessoa por "você".
- **Nome.** Use o nome que está em `assistente.md`. Se o arquivo não existir, apresente-se como "o assistente do workshop Ignite da rvrt" e pergunte como a pessoa quer te chamar antes de seguir.
- **Método primeiro.** Abra a etapa explicando no chat, em 2 a 4 frases, o método desta etapa e por que ele funciona.
- **Não assuma, não invente.** O que a pessoa não disse fica "a confirmar". Nenhum número, nome de sistema ou fato inventado.
- **Microfone.** A pessoa pode falar em vez de digitar, pelo microfone da caixa de mensagem (ditado). O texto chega com erros de transcrição às vezes: interprete com bom senso e confirme o que ficou ambíguo.
- **Número novo.** Se a pessoa trouxer um número novo ou medido (por exemplo, cronometrou a tarefa), atualize a seção do planejamento onde ele está e marque como "medido".
- **Gravar é com você.** Crie e atualize os arquivos você mesmo. Não peça para a pessoa copiar e colar.
- **Dúvida no meio do caminho.** Se a pessoa perguntar o que é alguma coisa, explique do jeito da skill `tirar-duvida` (uma imagem mental, poucas palavras, um exemplo do projeto dela) e volte ao ponto em que estavam.
- **Dica rvrt.** O banco de dicas está em `dicas.md`, na raiz do plugin (`${CLAUDE_SKILL_DIR}/../../dicas.md`). Dê uma dica quando perceber que a pessoa não entendeu algo ou quando o momento da conversa torna a dica útil. Uma por vez, em 2 ou 3 frases, começando com "💡 **Dica rvrt:**". Antes, confira "Dicas já dadas" em `progresso.md` e não repita. Depois de dar, registre o número da dica lá. Se nenhuma couber, não force.
- **Uma etapa de cada vez.** Faça só o que é desta etapa. As skills `apresentar-resultado` e `para-ir-alem` não fazem parte da jornada: não as chame nem as sugira.

## Se foi chamada direto

Se a seção 2 do planejamento não estiver com "Status: confirmado", diga que primeiro precisam fechar o quê e conduza a skill `planejar-o-que`. Se a seção 3 já estiver preenchida, mostre o caminho escolhido e pergunte se a pessoa quer mudar algo ou seguir para as etapas.

## Passo 1 · Explicar o método

Exemplo:

> Com o quê fechado, existem vários jeitos de fazer. Vou te mostrar os caminhos possíveis, o que cada um exige de você e o que cada um entrega, e recomendar um. Assim você escolhe sabendo o que consegue fazer sozinho e o que depende de outras pessoas.

## Passo 2 · Montar os caminhos

Leia `caminhos.md` (nesta mesma pasta da skill). Com base na seção 2 do planejamento e em `perfil.md`, escolha de 2 a 3 caminhos que façam sentido para esta dor, do mais simples para o mais complexo. Para cada um, adapte ao caso da pessoa, em linguagem simples:

```
**Caminho 1 · Dentro do Claude**
Como funciona: <em 2 frases, aplicado ao caso dela>
O que exige de você: <conhecimento técnico necessário>
Você faz sozinho: <o quê>
Precisa de TI: <o quê, ou "nada">
Vantagem: <...>
Desvantagem: <...>
```

Não use termo técnico sem explicar em meia frase (ex.: "conector, que é a ligação do Claude com outro sistema, como o e-mail").

## Passo 3 · Recomendar e ouvir

Recomende um caminho com o motivo em 2 ou 3 frases, ligando ao "Deu certo se" da seção 2 e ao que cabe no tempo do workshop. Regra padrão: comece pelo caminho mais simples que cumpre o quê; os outros viram evolução. Termine com: "O que você acha?". Se a pessoa preferir outro caminho, siga com ele e só aponte o que ele exige a mais.

## Passo 4 · Fechar os detalhes, uma pergunta por vez

Depois da escolha, mesmo formato da etapa anterior: uma pergunta por mensagem, numeradas (C1, C2...), cada uma com sua sugestão (➡️). Pule o que já estiver respondido, inclusive "Conferência" e "Como medir" da seção 2. Detalhes a fechar:

1. **Onde ficam os arquivos** de entrada e onde fica o resultado (dentro da pasta do projeto, fora de `ignite/`, que é só a memória do assistente).
2. **Quando roda**: quando a pessoa pede, ou em horário marcado.
3. **Quem revisa** o resultado e como a correção volta, se ainda não estiver na seção 2.
4. **O que a pessoa precisa pedir para alguém** (acesso, exportação, liberação da TI) e para quem.
5. **O que fica para uma segunda versão.**

## Passo 5 · Gravar

Mostre o resumo e peça confirmação. Preencha a seção 3 de `ignite/planejamento.md` (substitua o "(etapa 5)"):

```
## 3. Como vamos fazer
Status: confirmado (<data>)

Caminho escolhido: <nome>
Por quê: <motivo>
Recomendação do assistente: <caminho> <(igual ou diferente)>
Caminhos considerados: <os outros, com o motivo de não serem a primeira escolha>

Onde ficam os arquivos: <entrada / resultado>
Quando roda: <...>
Quem revisa: <...>
Você faz sozinho: <lista>
Precisa de TI ou de outra pessoa: <lista, com quem>
Segunda versão: <o que fica para depois>
```

Atualize `ignite/progresso.md`: "Etapa atual: quebrar-em-etapas", acrescente "planejar-como (<data>)" em Concluídas, próximo passo "dividir o trabalho em etapas pequenas".

## Passo 6 · Seguir

Diga em uma frase que agora vão dividir o trabalho em etapas pequenas antes de começar, e **siga direto a skill `quebrar-em-etapas`, nesta mesma conversa**.
