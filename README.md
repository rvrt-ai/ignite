# Assistente Ignite rvrt

Este é o seu assistente no workshop Ignite da rvrt. Ele te acompanha do primeiro contato até o seu projeto rodando e conferido: te conhece, levanta as dores do seu dia a dia, ajuda a escolher uma, planeja a solução com você, executa em etapas e confere se o resultado cumpre o que foi planejado.

## O que ele faz com você

1. **Te conhece.** Se apresenta, você escolhe como chamá-lo e conta um pouco do seu trabalho.
2. **Levanta suas dores.** Conversa sobre a sua rotina e o que toma seu tempo. Se o assunto já foi discutido numa reunião, você pode colar a transcrição.
3. **Ajuda a escolher uma dor.** Dá uma nota para cada dor, monta uma fila e recomenda uma. A escolha é sua.
4. **Planeja o que vai existir no fim.** Uma entrevista, uma pergunta por vez, até ficar claro o resultado e como saber que deu certo.
5. **Planeja como fazer.** Mostra 2 ou 3 caminhos, do mais simples ao mais completo, com prós e contras, e recomenda um.
6. **Divide o trabalho em etapas pequenas.** Cada uma com o que entrega e como conferir. A primeira testa com um caso só.
7. **Executa, uma etapa de cada vez.** Mostra o que fez e o que conferiu, e para quando é hora de você revisar.
8. **Verifica.** Compara o que foi entregue com o que foi planejado, testa com casos reais seus e mede o ganho contra o número de antes.

Tudo acontece numa conversa só. Você não precisa chamar outro comando.

## A qualquer momento

- **Não entendeu algum termo?** Digite `/ignite:tirar-duvida` e o que você quer saber, por exemplo "o que é janela de contexto?". Ou só pergunte no meio da conversa. Ele explica com um exemplo do seu próprio projeto e te diz como voltar para onde estava.
- **Dicas.** Ao longo do caminho, o assistente dá dicas curtas quando elas ajudam. Elas aparecem marcadas como "Dica rvrt".

## No fim do workshop

Quando a equipe do workshop orientar, digite `/ignite:apresentar-resultado`. O assistente monta uma apresentação do seu projeto (a dor, o que foi feito, o antes e depois e o ganho), só com dados reais do seu planejamento. Você revisa antes de apresentar.

Depois da apresentação, digite `/ignite:para-ir-alem`. O assistente monta uma página com referências para você continuar sozinho: cursos gratuitos da Anthropic, plugins prontos para a sua área, como criar as próximas skills e boas leituras. No topo ficam as que mais combinam com você e com o seu projeto. Todos os links foram conferidos pela rvrt.

## Antes de começar

- Claude com plano pago (Pro, Max, Team ou Enterprise).
- App **Claude Desktop** instalado no seu computador.
- Se a sua empresa usa o plano Team, quem administra a conta precisa liberar plugins e skills.

## Instalar

1. Baixe o arquivo `ignite.zip`.
2. No Claude Desktop, abra **Customize** na barra lateral e depois **Plugins**.
3. Escolha a opção de upload e selecione `ignite.zip`.
4. Confira se aparecem 11 skills no plugin.

## Começar

1. Crie uma pasta no seu computador chamada `Meu projeto Ignite`.
2. No Cowork, crie um projeto **a partir dessa pasta**.
3. Dentro do projeto, abra uma tarefa nova e digite `/ignite:onboarding` (ou digite `/` e escolha na lista).
4. Siga a conversa.

Prefere falar a digitar? Clique no microfone da caixa de mensagem e fale. O assistente lê o que você disse.

## Voltar outro dia

Abra o mesmo projeto, abra uma tarefa nova e digite `/ignite:onboarding` de novo. O assistente lembra de tudo e continua de onde vocês pararam. Na execução, ele retoma pela próxima etapa que ainda não foi feita.

## Onde fica o que ele aprende

Numa pasta `ignite/` dentro do seu projeto. Você pode abrir e corrigir qualquer arquivo:

| Arquivo | O que tem |
|---|---|
| `assistente.md` | o nome que você escolheu |
| `perfil.md` | o que você contou sobre você |
| `dores.md` | as dores levantadas |
| `planejamento.md` | o documento do seu projeto, que cresce a cada etapa |
| `progresso.md` | em que etapa vocês estão e as dicas já dadas |
| `apresentacao.html` | a apresentação do resultado, quando você pedir |
| `referencias.html` | as referências para ir além, quando você pedir |

O `planejamento.md` tem cinco seções:

1. **A dor escolhida:** a fila, a dor, o motivo e o número de antes.
2. **O que vamos fazer:** o resultado esperado e como saber que deu certo.
3. **Como vamos fazer:** o caminho escolhido e o que fica para uma segunda versão.
4. **Etapas de execução:** a lista de etapas, marcadas conforme ficam prontas.
5. **Verificação:** o que foi atendido, os casos testados e o ganho medido.

O que o assistente produz para o seu projeto (planilhas, relatórios, skills) fica na pasta do projeto, fora de `ignite/`.
