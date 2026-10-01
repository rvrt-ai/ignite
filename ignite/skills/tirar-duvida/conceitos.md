# Conceitos (base para tirar dúvida)

Definição de referência e uma imagem mental sugerida para cada conceito. A definição é a régua para não errar o conceito. A imagem é ponto de partida; adapte ao projeto da pessoa.

## Fundamentos

**Modelo (LLM)**
Definição: sistema que recebe texto e gera texto, treinado com um volume massivo de dados.
Imagem: alguém que leu quase tudo o que já foi escrito e responde completando o texto do jeito mais provável.

**Token**
Definição: unidade de texto que o modelo processa, em geral um pedaço de palavra. Limites e custos são medidos em tokens.
Imagem: as sílabas de uma conversa. É assim que o modelo conta o tamanho do que lê e escreve.

**Janela de contexto**
Definição: tudo o que o modelo vê em uma interação.
Imagem: a mesa de trabalho. O que está em cima da mesa ele vê; o que está na gaveta, não existe para ele.

**Sessão**
Definição: uma conversa, com a sua própria janela de contexto.
Imagem: uma reunião. Quando acaba, a próxima começa com a mesa vazia, sem a ata da anterior.

**Prompt**
Definição: o texto de entrada enviado ao modelo: pedido, contexto e instruções.
Imagem: o briefing que você passa para alguém novo na equipe.

**Não determinismo**
Definição: a mesma entrada pode gerar saídas diferentes.
Imagem: pedir o mesmo resumo a duas pessoas. O conteúdo é parecido, as palavras não.

**Alucinação**
Definição: saída plausível, mas incorreta ou inventada, gerada com aparente segurança.
Imagem: alguém que não sabe a resposta, mas responde com convicção em vez de dizer "não sei".

**Agente**
Definição: modelo com acesso a ferramentas, que planeja e executa tarefas em várias etapas.
Imagem: o cérebro com braços e pernas. Além de pensar, ele abre arquivos, cria planilhas, busca na web.

## Contexto

**Instruções**
Definição: texto fixo incluído na janela de contexto de toda conversa.
Imagem: o manual que fica colado na mesa e é lido antes de cada reunião.

**Projeto**
Definição: espaço que agrupa conversas, arquivos e instruções de um mesmo assunto.
Imagem: uma pasta de trabalho física, com os documentos e as regras daquele assunto dentro.

**Meta-prompt**
Definição: prompt que pede ao modelo para gerar um prompt.
Imagem: pedir para um especialista escrever o briefing em vez de você tentar escrever sozinho.

**Memória**
Definição: recurso que salva informações entre sessões e as inclui no contexto de novas conversas.
Imagem: o caderno de anotações que você relê antes de cada reunião.

**CLAUDE.md**
Definição: arquivo de instruções de um projeto no Claude Code.
Imagem: as instruções do projeto, só que para quem constrói software.

## Recursos do agente

**Skill**
Definição: pacote de instruções para executar um trabalho recorrente sempre no mesmo padrão.
Imagem: uma receita. Quem segue a receita faz o bolo igual toda vez, sem precisar perguntar.

**Conector**
Definição: integração que dá ao Claude acesso a uma ferramenta externa, como e-mail, drive ou sistema de gestão.
Imagem: uma chave de acesso. Com ela, o Claude lê direto na fonte, sem você copiar e colar.

**MCP**
Definição: protocolo padrão por trás dos conectores: define como o modelo acessa ferramentas e dados externos.
Imagem: a tomada padrão. Qualquer aparelho que segue o padrão encaixa.

**Tarefa agendada**
Definição: tarefa que o Claude executa sozinho, em horário definido.
Imagem: o despertador. Você programa uma vez e ele toca todo dia na hora certa.

## Produtos Claude

**Chat**
Definição: conversa direta com o modelo, para pensar, perguntar e rascunhar.
Imagem: pensar em voz alta com um colega.

**Cowork**
Definição: agente que executa tarefas em várias etapas sobre seus arquivos e ferramentas, e entrega o resultado.
Imagem: delegar para um colega que senta na sua mesa, mexe nos seus arquivos e te devolve o trabalho pronto.

**Claude Code**
Definição: ferramenta agêntica para construir e modificar software.
Imagem: o mesmo colega, agora trabalhando como programador.

## Conceitos da jornada Ignite

**Número de antes (linha de base)**
Definição: quanto a dor custa hoje, em tempo, erros ou prazo, antes da solução.
Imagem: a foto do "antes" de uma reforma. Sem ela, ninguém prova que melhorou.

**Planejar o quê antes do como**
Definição: combinar o que precisa existir no fim e como saber que deu certo, antes de escolher ferramenta.
Imagem: a planta da casa antes de escolher o tijolo.

**Ponto de revisão**
Definição: momento em que a execução para e a pessoa confere o resultado antes de seguir.
Imagem: a prova do bolo antes de assar a fornada inteira.

**Verificação**
Definição: comparar o entregue com o planejado, item por item, com evidência.
Imagem: conferir a obra com a planta na mão, cômodo por cômodo.

**Ganho medido**
Definição: diferença entre o número de antes e o de depois, medidos do mesmo jeito.
Imagem: subir na mesma balança antes e depois.
