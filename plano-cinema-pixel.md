**Cinema e dilemas humanos — vídeos gerados por IA com estética de PS1**

Atualização de 13/11/2026. Decisões do usuário: seleção sem restrição de gênero; filmes que provoquem curiosidade e reflexão ética, humana ou social; preferência por voz sintetizada; quatro horas semanais; visual tridimensional inspirado em PS1. A proposta anterior em pixel art 2D foi substituída. Correção posterior: a produção será por geração de vídeo, sem modelagem ou animação no Blender. O nome deste arquivo foi mantido para preservar o link anterior.

**1. A proposta da página**

Promessa: “Filmes que deixam uma pergunta na sua cabeça, apresentados como pequenas cenas de um jogo antigo.”

O fio condutor será o dilema, e não o gênero. Selecionar uma premissa intrigante, desenvolver uma pergunta e convidar a assistir, sem revelar a decisão ou o desfecho. Não afirmar que são os filmes mais curiosos de forma objetiva: nossa lista é uma curadoria editorial a testar.

Formato proposto: 65–80 segundos, gancho → premissa → reflexão própria → identificação do filme e convite. O catálogo inicial está em `curadoria-filmes.md`; o novo piloto está em `piloto-a-caixa.md`. O Show de Truman continua como candidato futuro, mas seu storyboard antigo em pixel art não é o padrão atual.

**2. O que as referências mostram**

Observei quadros das duas publicações e consultei seus textos: [Whiplash PS1 PT2, no YouTube](https://www.youtube.com/shorts/ZhPKPZary6c), e [Un Poeta — PS1, no Instagram](https://www.instagram.com/fersetid_/reel/DfGJd1EzZRy/).

Os elementos relevantes são personagens e ambientes tridimensionais angulosos, texturas de baixa resolução, detalhes faciais em textura e enquadramentos de cinema. A referência do Instagram inclui a hashtag Blender3D. Isso é um indício de ferramenta, não prova do processo completo nem do uso ou ausência de IA. Não foi feita auditoria quadro a quadro.

Usaremos essas publicações para orientar a aparência dos vídeos gerados por IA. Não copiar falas, rostos, cenas ou a apresentação de um jogo fictício como se ele realmente existisse.

Direção visual: 3D low-poly, texturas pixeladas, iluminação simples, cortes legíveis e movimentos curtos. Começar com poucos objetos e personagens sem sincronização labial. Uma resolução interna baixa e ampliação sem suavização ajudam no aspecto retrô, mas não substituem modelagem, textura, câmera e animação.

**3. Ferramentas, custos e escolha de voz**

Meta atual: usar o ChatGPT Plus existente e testar geração de vídeo com créditos gratuitos do Google Flow. FFmpeg e Audacity já encontrados no computador servem para montagem e áudio. Não utilizar Blender nem construir modelos 3D.

O fluxo da documentação enviada — roteiro, referências de personagens, imagens-âncora, imagem para vídeo, montagem — é adequado ao objetivo. A adaptação principal é criar as imagens no ChatGPT, com aparência PS1, e animá-las em uma ferramenta de vídeo. Uma imagem-âncora é o quadro inicial que fixa aparência, cenário e composição.

A OpenAI informa que o Sora web/app foi encerrado em 26/04/2026 e a API em 24/09/2026. Não planejar o projeto com tutoriais antigos que prometem Sora no Plus. [Informação oficial](https://help.openai.com/en/articles/20001152-what-to-know-about-the-sora-discontinuation).

| Etapa | Ferramenta e procedimento |
|---|---|
| Roteiro e storyboard | ChatGPT: fala, seis momentos narrativos e lista de tomadas |
| Referência visual | ChatGPT: aprovar uma imagem no estilo PS1 antes de produzir o conjunto |
| Imagens-âncora | ChatGPT: gerar enquadramentos usando as mesmas referências de personagens, caixa e cenário |
| Animação | Flow: enviar imagem como quadro inicial e descrever uma ação simples |
| Narração | Síntese separada, conforme escolha e licença abaixo |
| Montagem | Cortar os clipes gerados, alinhar à narração e acrescentar legendas |

O [Flow oferece 50 créditos diários sem assinatura](https://support.google.com/flow/answer/16353333?hl=pt-BR), sujeito a requisitos e disponibilidade. Os créditos diários não acumulam; o acesso gratuito pode ficar indisponível em horários de pico. Não foram conferidos saldo ou acesso da sua conta.

Na [tabela oficial consultada](https://support.google.com/flow/answer/16526234?hl=en), Veo 3.1 Lite custa 10 créditos por geração de 4, 6 ou 8 segundos para usuários sem plano Ultra. Omni Flash 1.2 custa 1 crédito por segundo em 360p e 3 em 720p, até 10 segundos para usuários gratuitos. Confirmar modelo, custo e quantidade de resultados antes de gerar; os valores mudam.

Primeiro teste recomendado: a mesma imagem e ação em Veo 3.1 Lite, 8 segundos, 720p, um resultado. Se o visual ficar excessivamente suave ou moderno, testar Omni Flash 1.2 em 360p, 8 segundos. A comparação custaria 18 créditos pela tabela consultada, sem novas tentativas. A qualidade precisa ser avaliada; resolução baixa sozinha não cria estética PS1.

Preferir imagem para vídeo a começar todos os clipes só com texto: permite revisar a aparência antes de gastar créditos na animação. Isso melhora o controle, mas não garante identidade perfeita entre tomadas. Usar uma ação e uma câmera por clipe. Adotar quadro final apenas quando precisar controlar uma mudança específica e o modelo oferecer esse recurso. [Frames e referências no Flow](https://support.google.com/flow/answer/16353334?hl=pt-BR).

Para aproximadamente 70 segundos finais, planejar cerca de 9–12 clipes curtos e ajustar após a narração. Seis momentos do storyboard podem exigir mais de uma tomada cada. Nove gerações de 8 segundos no Veo Lite custariam 90 créditos e forneceriam 72 segundos brutos; cortes e tentativas extras aumentam o consumo. Não presumir que 50 créditos bastem para um episódio inteiro ou que todas as gerações sejam aproveitáveis.

Clonar sua voz não exige narrar cada episódio. No fluxo de texto para fala, você fornece uma amostra inicial e depois gera novas falas por texto. Voz pronta e clone ainda precisam de revisão de pronúncia, ritmo e naturalidade.

| Opção de voz | Custo e trabalho | Decisão proposta |
|---|---|---|
| Voz pronta local, por exemplo com Piper | Sem assinatura do motor; exige configurar, escolher voz em português e conferir licença específica | Primeiro teste sem gasto; qualidade ainda precisa ser ouvida |
| Voz pronta em serviço pago | Configuração simples; assinatura ou consumo | Alternativa se o teste local ficar artificial ou consumir tempo demais |
| Clone da sua própria voz | Preparação inicial e uso continuado do serviço/modelo | Continua sendo opção viável; não descartar por presumir gravação a cada vídeo |

O [Piper](https://github.com/OHF-Voice/piper1-gpl) é um motor local. A [licença da voz](https://github.com/OHF-Voice/piper1-gpl/blob/main/docs/LICENSING.md) deve ser verificada separadamente; nenhuma voz específica foi aprovada ainda para este projeto.

Como referência paga, a página consultada do [ElevenLabs](https://elevenlabs.io/pricing) informa Starter a US$ 6/mês no preço mensal regular, com licença comercial e clonagem instantânea. Não contar com promoções; confirmar valor e impostos antes de contratar. Sua documentação recomenda aproximadamente [1–2 minutos de áudio limpo para clonagem instantânea](https://elevenlabs.io/docs/eleven-creative/voices/voice-cloning/instant-voice-cloning). O [plano gratuito é destinado a uso não comercial com atribuição](https://elevenlabs.io/docs/overview/administration/billing); não adotá-lo como solução gratuita definitiva para a página comercial.

Usar o Plus atual para pesquisa, roteiro, revisão e assistência de criação, respeitando seus limites. Não presumir API de voz ou vídeo gratuita incluída. A distinção entre assinatura e API consta na [documentação OpenAI](https://developers.openai.com/api/docs/guides/chatgpt-api-credits).

**4. Preparar a marca e os perfis**

Nomes provisórios: “Depois dos Créditos”, “Dilema em Cena”, “Cinema em Baixa Resolução”. Disponibilidade de nome e marca ainda não verificada.

Bio sugerida:

> Filmes que deixam perguntas. 🎬 Dilemas humanos em animações 3D retrô.

Descrição ampliada:

> Indicações de filmes que provocam curiosidade e reflexão sobre escolhas, dinheiro, poder e relações humanas. Narração e cenas em 3D retrô, sem entregar o desfecho. Produção com apoio de IA e revisão humana.

Sequência: escolher nome e verificar disponibilidade → usar e-mail e dados reais → ativar autenticação em duas etapas → configurar avatar próprio e bio → conferir situação e recursos de monetização → preparar primeira publicação. TikTok pessoal para o objetivo de Recompensas; YouTube com a mesma identidade. Instagram pode receber o mesmo arquivo final quando couber na rotina.

Priorizar TikTok e YouTube Shorts; reservar o nome no Instagram. Não criar três rotinas editoriais distintas. Exportar o arquivo original para cada rede, conferindo legenda, música, rótulos e enquadramento em cada uma. Nenhuma conta foi criada ou alterada.

**5. Produção mínima de um episódio**

1. Escolher o filme e verificar premissa, pergunta central e limite de spoilers.
2. Finalizar a narração e medir sua duração antes de gerar todas as cenas.
3. Gerar no ChatGPT uma imagem-base vertical com aparência de jogo PS1. Ajustar até aprovar estética, caixa, mão e ambiente.
4. Usar as mesmas referências para produzir as imagens-âncora das demais tomadas. Não gerar cada cena sem contexto visual.
5. No Flow, selecionar vídeo por frames, enviar a imagem inicial, escolher 9:16, modelo, duração e um resultado. Conferir créditos antes de executar.
6. Pedir um movimento simples: câmera avança e mão hesita. Não pedir várias cenas, mudanças de estilo ou diálogo no mesmo clipe.
7. Revisar deformações, continuidade e manutenção do estilo. Refazer somente o que compromete a narrativa; registrar tentativas e custo.
8. Montar os clipes com a voz separada e legendas legíveis. Preservar sinais de proveniência; aplicar as identificações de IA necessárias.
9. Publicar e medir. Guardar imagens, prompts, áudio, clipes e projeto de edição.

Prompt editorial atualizado:

> Prepare uma indicação de [FILME/ANO] com base em [FONTES]. Use uma premissa curiosa e uma pergunta ética, humana ou social, sem restringir o gênero. Escreva aproximadamente 150–175 palavras em português brasileiro, para narração sintética natural, e planeje seis momentos narrativos, divididos em tomadas curtas para imagem-para-vídeo com aparência tridimensional de PS1. Para cada tomada, entregue um prompt da imagem inicial e outro de movimento. Separe fatos, interpretação e incertezas. Não copie falas, não revele o desfecho e não invente disponibilidade em streaming. A relação com capitalismo, quando houver, deve ser justificada pelo conteúdo, não imposta a todo filme. Entregue a premissa, o gancho, a fala e as ações visuais.

**6. Regras que influenciam o formato e a renda**

| Rede | Referência para planejar |
|---|---|
| TikTok | O anúncio oficial brasileiro informa 18 anos ou mais, conta pessoal regular em mercado elegível, 10 mil seguidores e 100 mil visualizações nos últimos 30 dias; o programa contempla conteúdo original com mais de um minuto. Confirmar os requisitos e a elegibilidade no TikTok Studio. |
| YouTube | Para participação em anúncios: 1.000 inscritos e 10 milhões de visualizações públicas válidas de Shorts em 90 dias; existe a via alternativa de 4 mil horas públicas qualificadas em 12 meses. Horas do feed de Shorts não contam para essas 4 mil. Há análise do canal. |
| Instagram | Usar inicialmente para distribuição e relacionamento. Não projetar pagamento automático por visualização. Verificar os recursos disponíveis no painel da própria conta. |

Fontes: [TikTok — anúncio do programa](https://newsroom.tiktok.com/apresentando-o-programa-de-recompensas-do-criador?from_seo_redirect=1&lang=pt-BR), [YouTube — qualificação](https://support.google.com/youtube/answer/72851?hl=pt-BR), [Meta — painel de boas práticas](https://about.fb.com/news/2024/10/best-practices-education-hub-creators-instagram/amp/).

O YPP expandido tem entrada antecipada para certos recursos com 500 inscritos, três envios públicos em 90 dias e 3 milhões de visualizações qualificadas de Shorts em 90 dias, ou 3 mil horas qualificadas em 12 meses. Isso não equivale a liberar a receita de anúncios. [Programa expandido](https://support.google.com/youtube/answer/13429240?hl=pt-BR).

Conteúdo repetitivo, produzido em massa ou com pouca contribuição pode ser recusado para monetização. Manter identidade visual é diferente de repetir praticamente o mesmo vídeo. Cada episódio precisa de argumento e execução próprios. [Políticas do YouTube](https://support.google.com/youtube/answer/1311392?hl=pt-BR).

No TikTok, identificar conteúdo substancialmente gerado por IA é recomendado, e conteúdo sintético realista exige identificação. No YouTube, animação claramente irrealista não exige declaração apenas por ser animação; o áudio e outros elementos também precisam ser considerados. Informar na descrição o uso efetivo de IA é uma prática de transparência. [TikTok — IA](https://support.tiktok.com/pt_BR/using-tiktok/creating-videos/ai-generated-content), [YouTube — IA](https://support.google.com/youtube/answer/14328491?hl=pt-BR).

Recriar um filme em 3D retrô não elimina direitos autorais. A lei brasileira prevê autorização para adaptações e também limitações específicas, que não são uma permissão geral para refazer filmes. Para começar: premissa breve em palavras próprias, comentário editorial, ilustrações conceituais próprias, sem copiar cenas, diálogos ou trilha. Dar créditos não substitui licença. Essa estratégia reduz dependência de material de terceiros, mas não garante ausência de reclamações. [Lei 9.610, arts. 29 e 46](https://www.planalto.gov.br/ccivil_03/leis/l9610.htm).

**7. Rotina de quatro horas semanais**

A meta anterior de seis episódios no primeiro mês foi reduzida. Para começar, propor dois vídeos finalizados em quatro semanas: a definição do estilo, a escolha da voz e as tentativas de geração consomem tempo inicial. Depois, testar um vídeo por semana, apenas se o registro de horas mostrar que cabe.

| Semana inicial | Entrega |
|---|---|
| 1 | Teste de voz e cena de 8 segundos de A Caixa; medir esforço e qualidade |
| 2 | Finalizar e publicar A Caixa; guardar referências visuais e prompts reutilizáveis |
| 3 | Escrever e montar o segundo episódio usando a base já criada |
| 4 | Publicar o segundo episódio e revisar produção e resposta do público |

Distribuição alvo de uma semana, após a base pronta:

| Etapa | Minutos |
|---|---:|
| Seleção, pesquisa e roteiro | 40 |
| Síntese e revisão da narração | 25 |
| Imagens, geração de clipes e revisão | 100 |
| Montagem, legendas e revisão | 45 |
| Publicação nas redes escolhidas | 20 |
| Registro de métricas | 10 |
| Total | 240 |

Isso é orçamento de tempo, não tempo de execução já demonstrado. A espera pelas gerações pode ocorrer fora do trabalho ativo. Como os créditos gratuitos são diários e não acumulam, pode ser necessário distribuir as gerações em mais de um dia. Se exigir acompanhamento ou novas tentativas, registrar esse tempo. Assistir a um filme ainda desconhecido também precisa caber na semana; nesse caso, reduzir a produção ou publicar quinzenalmente.

Medir duração média assistida, conclusão quando disponível, compartilhamentos, salvamentos, seguidores atribuídos e comentários de intenção de assistir. Comparar na mesma rede, com duração e janela de observação semelhantes. O controle de métricas continua sem dados inventados.

Não medir sucesso só por visualizações. O experimento precisa mostrar que a proposta interessa, que a qualidade é sustentável e que há um caminho de receita. Dois vídeos ajudam a testar produção, mas são poucos para concluir se existe demanda consistente.

**8. Organização e possibilidades de renda**

Escolher apenas um controle:

| Alternativa | Serve melhor quando |
|---|---|
| CSV + pastas — recomendação inicial | Você quer começar com o mínimo de configuração |
| Google Sheets | Precisa editar pelo celular e compartilhar o controle |
| Quadro em Notion ou Trello | Prefere cartões visuais por etapa; conferir os limites atuais antes de depender deles |

Etapas: ideia → pesquisa → roteiro → áudio → animação → revisão → pronto → publicado → analisado. Uma pasta por episódio, contendo fontes, roteiro, áudio, imagens, projeto, exportação e licenças. Fazer cópia dos arquivos importantes.

O CSV de produção registra um episódio por linha. O CSV de métricas registra uma publicação por rede e por janela de observação. Não confundir a soma de medições de 48 horas e sete dias com visualizações adicionais.

Possíveis receitas: programas das plataformas quando aprovado; trabalhos patrocinados quando houver público adequado; links de afiliado apenas de programas verificados e produtos pertinentes; serviços de produção de animações para terceiros, usando o canal como portfólio. São hipóteses comerciais a testar, não receitas asseguradas. Mandar alguém procurar um filme não gera comissão automaticamente. Publicidade e afiliação devem ser identificadas.

No planejamento, assumir receita zero até existir receita real. Registrar despesas e horas. Lucro de caixa = receita recebida − despesas; avaliar também lucro por hora. O Plus já pago não é custo adicional do teste, mas sua parcela precisa entrar na conta se passar a ser mantido para o negócio.

**9. Quando entrar com n8n**

Só iniciar após um processo manual repetível e um gargalo identificado. Proposta de fluxo futuro:

Pauta aprovada → preparar pastas e dados → gerar rascunho → revisão humana → produzir elementos/áudio → renderizar → revisão final → fila de publicação → coletar métricas.

Automatizar primeiro nomes de arquivos, organização, renderização e relatórios. A geração por APIs pode ter custos próprios. Publicação automática depende de APIs, permissões e condições de cada rede; não assumir que tudo estará disponível para qualquer conta.

A edição Community do n8n pode ser auto-hospedada gratuitamente, mas computador ligado, manutenção e possíveis APIs continuam custando tempo ou dinheiro. [Documentação do n8n](https://docs.n8n.io/deploy/host-n8n/community-edition-features.md).

Antes de ampliar: medir custo por episódio, tempo de revisão, resultado editorial e receita real. Configurar limite de gastos, prevenção de publicações duplicadas e aprovação final. Expandir uma marca validada antes de abrir várias páginas.

**Próxima entrega prática:** gerar uma imagem-âncora de A Caixa no ChatGPT e testá-la em um clipe de oito segundos no Flow. Voz, licença, acesso da conta e esforço real ainda precisam de validação. Não houve instalação, contratação ou geração de vídeo nesta revisão.

**Pacote de direção detalhado de A Caixa**

A primeira imagem foi fornecida pelo usuário e preservada em `a-caixa/A01-referencia.png`. O planejamento agora possui dez tomadas e nove âncoras distintas, com oito novas gerações pendentes. As composições, falas, referências e movimentos foram decididos em `a-caixa/cenas-e-prompts.md` e `a-caixa/producao.json`. A instrução `diretor-automatico.md` permite repetir esse planejamento para outros roteiros. Nenhum fluxo n8n foi implementado.
