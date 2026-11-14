**Piloto — A Caixa (The Box, 2009), em estética 3D de PS1**

Estado: roteiro preservado; primeira imagem-âncora fornecida pelo usuário. O pacote detalhado está em `a-caixa/cenas-e-prompts.md` e `a-caixa/producao.json`. O storyboard resumido abaixo foi substituído por dez tomadas nesse pacote. As outras oito âncoras, a narração e os vídeos ainda não foram gerados. Referência de premissa: [Icon Film Distribution](https://iconfilmdistribution.co.uk/our-films/the-box). O dilema envolve a promessa de um milhão de dólares e a morte de alguém que o casal não conhece.

Escolha de produção: imagens-âncora criadas no ChatGPT e animadas por IA no Flow, com aparência 3D de PS1 e narração externa. Sem Blender ou modelagem manual. Os seis momentos narrativos abaixo podem ser divididos em 9–12 tomadas curtas, conforme a duração da voz. Sem diálogo sincronizado com a boca, sem copiar o rosto dos atores ou reconstruir planos exatos do filme. A reflexão pertence à nossa indicação editorial.

**Narração para teste**

> Você apertaria um botão por um milhão de dólares, sabendo que um desconhecido morreria?
>
> Em A Caixa, de dois mil e nove, um casal recebe uma proposta: apertar o botão de uma caixa e ganhar o dinheiro. Mas alguém que eles não conhecem vai morrer.
>
> A oferta parece separar duas coisas que deveriam continuar juntas: o benefício que você recebe e o sofrimento que ele provoca.
>
> O dinheiro está ali, perto. A vítima está longe. Você não sabe o nome dela, não vê o rosto e não precisa encarar quem vai sentir sua falta.
>
> Será que isso muda o que é certo? Ou só torna mais fácil encontrar uma desculpa?
>
> A situação também permite pensar em escolhas comuns: quando alguém lucra e o prejuízo fica escondido, quem assume a responsabilidade?
>
> O filme transforma essa pergunta num suspense. Não vou contar a decisão do casal nem suas consequências.
>
> Procure A Caixa, de dois mil e nove. Antes de assistir, pense: sua resposta mudaria se você conhecesse a vítima?

Confirmar duração com o áudio: alvo aproximado de 70–80 segundos, sem esticar a gravação para cumprir duração. Testar pronúncia e pausas; escrever o ano por extenso para facilitar a síntese. A conexão com decisões econômicas é uma interpretação, não uma conclusão demonstrada pelo filme sobre o mundo real.

**Storyboard**

| Tempo inicial | Plano e movimento | Relação com a fala |
|---|---|---|
| 0–8 s | Close de botão vermelho numa caixa sobre uma mesa. Câmera avança lentamente; mão para antes de tocar. | Apresentar a escolha imediatamente |
| 8–22 s | Plano mais aberto de uma sala simples; duas silhuetas angulosas e a caixa no centro. | Apresentar casal, proposta e consequência |
| 22–35 s | Câmera percorre a mesa entre a caixa e uma representação estilizada do dinheiro. | Mostrar proximidade do benefício |
| 35–47 s | A câmera revela uma porta distante, iluminada, com uma silhueta genérica. | Metáfora do desconhecido; não é uma cena alegada do filme |
| 47–62 s | Dois lados da mesa: dinheiro iluminado e cadeira vazia. A mão recua e volta a hesitar. | Relacionar ganho, distância e responsabilidade |
| 62–78 s | Volta à caixa; a câmera para antes de qualquer decisão. Título e ano entram na edição. | Preservar o desfecho e convidar a assistir |

Ajustar cortes à fala final. Não mostrar o botão sendo apertado; não inventar um resultado da escolha. Não representar morte de forma gráfica.

**Guia visual**

- Objetos e personagens tridimensionais com poucos polígonos; contornos angulosos e volume legível.
- Texturas pequenas e visivelmente pixeladas; filtragem sem suavização nas superfícies que pedirem esse efeito.
- Continuidade aprovada pela referência enviada: mesa de madeira, caixa metálica cinza, botão vermelho com base preta, mão com manga azul-escura quadriculada; luminária bege à esquerda, janela noturna e cortinas rosadas. Luz quente interna e azul da noite.
- Câmera com enquadramentos de cinema, movimentos curtos e cortes claros.
- Sujeira visual e tremor discretos, opcionais; não prejudicar leitura ou conforto.
- Proposta de renderização base: 360 × 640, ampliada 3× para 1080 × 1920; legendas compostas na resolução final. Isso aproxima o visual retrô, sem pretender simular fielmente o hardware do PS1.
- Evitar aparência de sprite 2D, voxel, desenho de 8 bits ou 3D moderno excessivamente polido.

**Primeiro teste de geração de vídeo**

A imagem-âncora inicial já foi fornecida e está preservada em `a-caixa/A01-referencia.png`. Antes do vídeo inteiro, animá-la em um clipe curto, ajustado à fala: mesa, caixa, mão aproximando-se e recuando, câmera curta. Avaliar três itens: o visual lembra as referências? O movimento comunica hesitação? Quantos créditos, tentativas e minutos de trabalho ativo foram necessários?

Prompt para gerar a imagem-âncora no ChatGPT:

> Quadro vertical 9:16 de uma animação tridimensional retrô inspirada em jogos de PlayStation 1. Sala doméstica simples à noite, mesa de madeira, pequena caixa com um único botão vermelho; mão humana estilizada suspensa antes de tocar. Aparência de modelos low-poly com superfícies angulosas, texturas pequenas e pixeladas, perspectiva e volume claramente 3D, iluminação simples e atmosfera de dilema moral. Composição original, sem reproduzir fotogramas, atores ou objetos idênticos de filmes. Sem texto, logotipos, interface de jogo, visual de sprites 2D, voxels ou renderização moderna brilhante. Não mostrar o botão pressionado.

Usar a imagem aprovada como frame inicial no Flow. Não é necessário gerar um modelo 3D editável.

Prompt de movimento:

> Preserve exatamente a estética tridimensional retrô da imagem inicial: poucos polígonos, texturas pixeladas e iluminação simples. Em uma única tomada contínua, a câmera avança lentamente em direção à caixa. A mão se aproxima do botão, para antes de tocar e recua um pouco, expressando hesitação. A caixa e o botão mantêm forma e posição. Não pressionar o botão. Manter o ambiente e a identidade visual durante todo o clipe. Sem cortes, novos objetos, falas, texto ou transformação em aparência fotorrealista.

Configuração de teste: vertical 9:16, 8 segundos, um resultado. Começar com Veo 3.1 Lite; comparar Omni Flash 1.2 apenas se necessário. Conferir o custo exibido. Geração não executada nesta etapa; preservação visual é uma instrução, não uma garantia.

**Voz**

Voz sintética em português brasileiro; próxima de uma conversa, curiosa e sóbria. Evitar tom de anúncio, dramatização excessiva e aceleração artificial. Testar o primeiro parágrafo em duas vozes ou configurações; escolher antes de gerar o roteiro inteiro. A voz final e sua licença ainda estão pendentes de seleção.

**Publicação proposta**

Título: “Um milhão de dólares por uma vida que você nunca viu? | A Caixa”

Descrição: “A Caixa (The Box, 2009) coloca dinheiro e responsabilidade na mesma mesa. Uma indicação sem revelar a decisão do casal. Sua resposta mudaria se você conhecesse a pessoa?”

Identificar na versão final o uso efetivo de voz sintética e de IA. Não declarar “animação gerada por IA” se a animação for feita em 3D convencional com assistência de código; descrever o processo com precisão. Não afirmar disponibilidade em streaming sem verificação atual.
