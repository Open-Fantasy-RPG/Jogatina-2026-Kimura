# Galen — Assinaturas gráficas

Este arquivo guarda somente a camada visual específica do personagem: quais capacidades têm fonte e como sua identidade altera a assinatura-base. Não substitui ficha, lista de magias, inventário, história nem o catálogo compartilhado. As definições gerais e as cinco fases completas residem uma única vez no catálogo-base, referenciado por `base_id`.

**Estado:** proposta visual para revisão. A disponibilidade de uma capacidade pode estar confirmada; sua paleta e encenação abaixo continuam propostas. Os IDs de assinatura-base são referências editoriais estáveis. Esta página registra os acentos próprios e as fontes públicas; não divulga documentos ou instruções de produção. Não exige acesso a um link privado para consultar estes ajustes.

**Como ler:** campos sem alteração herdam a assinatura-base. Os ajustes de fase indicados aqui não criam ações, duração, componente ou efeito. Aplicar a fonte da cena em primeiro lugar, especialmente em eventos antigos. Em qualquer cena nova, confirmar a ficha vigente.

## Identidade que não muda

Conservar [descrição completa](descricao.md), [retrato civil v0003](galen-retrato-v0003.png), [retrato com cota](galen-retrato-cota-de-malha-v0001.png) e respectivas [referências](README.md). Galen é robusto/atarracado, rosto largo, cabelo preto curto e barba cheia preta. Manter identidade distinta de Kaelen. Ocre e azul-marinho são paleta de traje do piloto; cota de malha é equipamento documentado. Não acrescentar escudo, elmo, placas, brasão, símbolo religioso, divindade ou espécie. As variantes civil/cota não estabelecem cronologia.

A assinatura pessoal tem peso, apoio e resolução: antecipação de ombro/quadril, arco compacto, contato definido e retomada do equilíbrio. A maça é tecnologia física asurana. Sua eletricidade azul-branca fica junto do mecanismo quando ativo; proteção/cura usam marfim/âmbar; trovão usa anel de pressão. Essas três leituras não devem virar um mesmo clarão.

## Fonte e abrangência

[Perfil atual](../README.md): Paladino do Juramento da Vingança, nível 4. Não há ficha numérica completa nem edição explicitada. Este guia inclui só capacidades citadas nas fontes públicas: maça, javelin, imobilização, Comando, Hunter’s Mark, Thunderous Smite, Shield of Faith, Lay on Hands, menção a Divine Smite e recurso de liderança com nome transcrito de modo incerto. Os IDs de capacidades D&D ficam em `pendente.dnd5e.*`; isso não cria uma versão híbrida 2014/2024. Não preencher o restante da lista de paladino por classe.

## Capacidades e acentos próprios

### Maça asurana

- **ID da instância:** `kimura.galen.maca-asurana`
- **Assinatura-base:** `mundano.weapon.mace`
- **Disponibilidade documentada:** Arma + mecanismo confirmados; falhas registradas.
- **Fonte de titularidade/efeito:** [Identidade/equipamento de Galen](../README.md); [Descrição visual](descricao.md); [17/09, mecanismo e falhas](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-17-audiencia-em-eldervan/sessao-2026-09-17-audiencia-em-eldervan.md#L51-L64). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Metal/brônzeo da referência; pequenos fios azul-brancos apenas quando ativada.
- **Proposta — motivo próprio:** Massa pesada, espinhos mecânicos e descargas curtas locais.
- **Ajustes às cinco fases-base:** Antecipação: base firme e peso da maça legíveis. Ativação: espinhos abrem se o mecanismo estiver ativo. Movimento: arco pesado curto; eletricidade fica junto da cabeça. Impacto: TUM físico mais filetes locais se couber. Resíduo: mecanismo conserva estado, sem brilho em falha/desativada.
- **Linhas de velocidade/escorço:** Cabeça grande em perspectiva, corpo robusto e cabo inteiro; não alongar maça como cajado.
- **SFX PT-BR:** CLAC do mecanismo; TUM e TZT curtos em ativação confirmada.
- **Continuidade e limites adicionais:** Não atribuir tipo de dano, bônus, raio à distância, corrente entre alvos ou sobrecarga sempre ligada por causa da arte. Falhas não somem por conveniência visual.

### Azagaia / javelin

- **ID da instância:** `kimura.galen.javelin`
- **Assinatura-base:** `mundano.weapon.javelin`
- **Disponibilidade documentada:** Arremessos efetivamente documentados.
- **Fonte de titularidade/efeito:** [24/09, 01:34:45–01:35:15](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-24-exploracao-do-templo-do-fluxo/sessao-2026-09-24-exploracao-do-templo-do-fluxo.md#L2205-L2215); [01/10, 00:41:13–00:42:05](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-10-01-andares-inferiores-441e1e188cc4b00b74901b904337b9cd1fd669468513102efce50859532f91ec/transcript.curated.md#L361-L373). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Madeira e metal; ocre/navy pertencem à roupa, não ao projétil.
- **Proposta — motivo próprio:** Diagonal física sóbria.
- **Ajustes às cinco fases-base:** Antecipação: ombro recua e define linha livre. Movimento: um projétil, trajetória fina. Impacto/resíduo: seguir acerto/erro e local realmente conhecidos.
- **Linhas de velocidade/escorço:** Escorço de braço, sem três azagaias para sugerir velocidade.
- **SFX PT-BR:** FUI / TUC.
- **Continuidade e limites adicionais:** A mesa explicitamente retirou Thunderous Smite do arremesso em 01/10; não eletrificar por associação com sua maça nem inventar quantidade no inventário.

### Agarrão e imobilização

- **ID da instância:** `kimura.galen.imobilizacao`
- **Assinatura-base:** `mundano.body.grapple`
- **Disponibilidade documentada:** Ação histórica citada no perfil; não estilo/feito permanente.
- **Fonte de titularidade/efeito:** [Identidade/equipamento de Galen](../README.md); [Descrição visual](descricao.md). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Tecidos e metal sob luz ambiente.
- **Proposta — motivo próprio:** Triângulo de apoio e mãos claramente visíveis.
- **Ajustes às cinco fases-base:** Antecipação: aproximação de corpo robusto. Movimento: peso controlado. Impacto: pegada legível. Resíduo: sustentação conforme cena.
- **Linhas de velocidade/escorço:** Separar os dois corpos; não esconder articulações sob speedlines.
- **SFX PT-BR:** RRF / HN, se cabível.
- **Continuidade e limites adicionais:** Não tratar toda imobilização como sufocamento, nocaute, ataque mágico ou sucesso automático.

### Comando

- **ID da instância:** `kimura.galen.command`
- **Assinatura-base:** `pendente.dnd5e.spell.command`
- **Disponibilidade documentada:** Uso registrado no perfil; palavra/resultado específico não recuperados.
- **Fonte de titularidade/efeito:** [Identidade/equipamento de Galen](../README.md); [Descrição visual](descricao.md). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Âmbar escuro com preto gráfico.
- **Proposta — motivo próprio:** Uma faixa curta e vertical de autoridade.
- **Ajustes às cinco fases-base:** Ativação: postura frontal e fala. Impacto: corte imediato para a resposta resolvida, sem inventar verbo. Resíduo: faixa desaparece.
- **Linhas de velocidade/escorço:** Balão firme e rosto preservado, sem olhos brilhantes obrigatórios.
- **SFX PT-BR:** Usar só palavra documentada; sem ela, não preencher fala.
- **Continuidade e limites adicionais:** Não presumir divindade, domínio mental, berro sobrenatural ou que qualquer ordem cotidiana é magia.

### Hunter’s Mark

- **ID da instância:** `kimura.galen.hunters-mark`
- **Assinatura-base:** `pendente.dnd5e.spell.hunters-mark`
- **Disponibilidade documentada:** Uso confirmado; edição/ficha completa pendentes.
- **Fonte de titularidade/efeito:** [24/09, 01:33:59 e 01:37:24–01:37:46](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-24-exploracao-do-templo-do-fluxo/sessao-2026-09-24-exploracao-do-templo-do-fluxo.md#L2193-L2293); [01/10, 01:39:56–01:40:30](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-10-01-andares-inferiores-441e1e188cc4b00b74901b904337b9cd1fd669468513102efce50859532f91ec/transcript.curated.md#L1135-L1139). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Cobre escuro e âmbar.
- **Proposta — motivo próprio:** Dois colchetes abertos, geométricos e só ao leitor.
- **Ajustes às cinco fases-base:** Ativação: olhar de rastreamento. Movimento: motivo fica no alvo correto. Impacto: pequeno segundo acento no acerto elegível. Resíduo: não trocar alvo sem fonte.
- **Linhas de velocidade/escorço:** Corte entre Galen e alvo; evitar radar/laser.
- **SFX PT-BR:** TIC editorial opcional.
- **Continuidade e limites adicionais:** Não confundir com eletricidade da arma, sensor asurano ou marca em todos. Em 24/09 há correção explícita: sombra marcada, não cachorro.

### Thunderous Smite

- **ID da instância:** `kimura.galen.thunderous-smite`
- **Assinatura-base:** `pendente.dnd5e.spell.thunderous-smite`
- **Disponibilidade documentada:** Uso confirmado; edição/ficha completa pendentes.
- **Fonte de titularidade/efeito:** [24/09, 00:43:58–00:46:53](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-24-exploracao-do-templo-do-fluxo/sessao-2026-09-24-exploracao-do-templo-do-fluxo.md#L972-L1054); [01/10, 00:52:57–00:54:44](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-10-01-andares-inferiores-441e1e188cc4b00b74901b904337b9cd1fd669468513102efce50859532f91ec/transcript.curated.md#L531-L543). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Branco denso/charcoal com mínimo reflexo âmbar.
- **Proposta — motivo próprio:** Anel quebrado de pressão sobre impacto da maça.
- **Ajustes às cinco fases-base:** Ativação: pressão curta junto à arma. Movimento: herdar peso da maça. Impacto: anel e estrondo abrem o quadro. Resíduo: eco se afasta; descarga elétrica do equipamento continua uma camada distinta, se ativa.
- **Linhas de velocidade/escorço:** Letras grandes localizadas junto ao impacto sem esconder arma/alvo; radiais de pressão em vez de zigue-zague elétrico.
- **SFX PT-BR:** BRUM! / TROOOM.
- **Continuidade e limites adicionais:** Não confundir trovão com raios nem torná-lo dano em área. O eco/duplicação de 24/09 foi ressonância de cena.

### Shield of Faith

- **ID da instância:** `kimura.galen.shield-of-faith`
- **Assinatura-base:** `pendente.dnd5e.spell.shield-of-faith`
- **Disponibilidade documentada:** Conjuração em si mesmo documentada.
- **Fonte de titularidade/efeito:** [01/10, 01:17:08–01:17:29](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-10-01-andares-inferiores-441e1e188cc4b00b74901b904337b9cd1fd669468513102efce50859532f91ec/transcript.curated.md#L787). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Marfim/âmbar suave, sem o azul da maça.
- **Proposta — motivo próprio:** Faixas largas e concêntricas próximas do torso.
- **Ajustes às cinco fases-base:** Ativação: envelope fecha por cima da cota sem substituí-la. Resíduo: proteção discreta persiste somente conforme fonte. Impacto ofensivo inexistente.
- **Linhas de velocidade/escorço:** Conservar malha/rosto visíveis; diferença clara para o plano de Escudo de Kaelen.
- **SFX PT-BR:** HUM opcional.
- **Continuidade e limites adicionais:** Não escudo físico, placas de armadura novas, brasão de ordem, símbolo de deus ou imunidade.

### Lay on Hands

- **ID da instância:** `kimura.galen.lay-on-hands`
- **Assinatura-base:** `pendente.dnd5e.class.lay-on-hands`
- **Disponibilidade documentada:** Cura por toque em si documentada.
- **Fonte de titularidade/efeito:** [01/10, 01:38:30–01:40:13](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-10-01-andares-inferiores-441e1e188cc4b00b74901b904337b9cd1fd669468513102efce50859532f91ec/transcript.curated.md#L1111-L1135). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Ouro suave/marfim apenas sob a palma.
- **Proposta — motivo próprio:** Halo pequeno, arredondado, aderente à mão.
- **Ajustes às cinco fases-base:** Ativação: mão toca o próprio corpo. Movimento: luz se adensa sob a palma. Impacto: gesto/rosto se recompõem conforme cura. Resíduo: apaga na mão.
- **Linhas de velocidade/escorço:** Close de mão robusta e cota; preservar ferimentos narrados e recursos gastos.
- **SFX PT-BR:** HUM opcional.
- **Continuidade e limites adicionais:** Não curar Jânia ou outra pessoa por inferência; a fala de 01:39:56 tem transcrição ambígua, então não fixa novo destinatário.

### Divine Smite

- **ID da instância:** `kimura.galen.divine-smite`
- **Assinatura-base:** `pendente.dnd5e.ability.divine-smite`
- **Disponibilidade documentada:** Mencionado pelo mestre como disponível; lançamento não confirmado.
- **Fonte de titularidade/efeito:** [24/09, 01:34:22–01:34:45](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-24-exploracao-do-templo-do-fluxo/sessao-2026-09-24-exploracao-do-templo-do-fluxo.md#L2196-L2206). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Marfim quente e ouro contido.
- **Proposta — motivo próprio:** Clarão axial compacto diferente do anel de Thunderous Smite.
- **Ajustes às cinco fases-base:** Herdar golpe físico; acento somente quando uma execução futura/histórica for confirmada pela fonte.
- **Linhas de velocidade/escorço:** Metal continua visível dentro do clarão; sem entidade sobrenatural atrás.
- **SFX PT-BR:** TAM editorial opcional.
- **Continuidade e limites adicionais:** Não incluir como usado no combate só porque o mestre o lembrou; não escolher uma versão 2014/2024, deus ou efeito adicional.

### Recurso de liderança / provável Inspiring Leader

- **ID da instância:** `kimura.galen.inspiring-leader`
- **Assinatura-base:** `pendente.dnd5e.feat.inspiring-leader`
- **Disponibilidade documentada:** PV temporários de liderança confirmados; nome fonético e edição pendentes.
- **Fonte de titularidade/efeito:** [24/09, 01:13:57–01:14:38](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-24-exploracao-do-templo-do-fluxo/sessao-2026-09-24-exploracao-do-templo-do-fluxo.md#L1680-L1711). A definição mecânica permanece nessa fonte.
- **Proposta — paleta própria:** Luz ambiente, ocre de roupa; sem emissão mágica.
- **Proposta — motivo próprio:** Horizonte comum alinhando cabeças/ombros do grupo.
- **Ajustes às cinco fases-base:** Antecipação: grupo reunido. Ativação: fala. Manifestação: aliados firmam postura. Resíduo: benefício acompanha a cena sem halo obrigatório.
- **Linhas de velocidade/escorço:** Plano de conjunto robusto e humano; sem speedlines de lançamento.
- **SFX PT-BR:** Som normal da fala.
- **Continuidade e limites adicionais:** Não é magia conforme jogador; não dá antecipação de turno por mera menção. Não normalizar silenciosamente o nome transcrito.

## Estados da maça e exceções de cena

- **Desativada ou falha:** metal/mecanismo continuam visíveis; não manter raios por hábito. A falha tecnológica em Erlingheim está registrada.
- **Ativa normal:** espinhos e pequenos arcos locais conforme fonte. A assinatura registra o aspecto do mecanismo e não arbitra as estatísticas da arma. [Fonte](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-17-audiencia-em-eldervan/sessao-2026-09-17-audiencia-em-eldervan.md#L51-L64).
- **Sobrecarga de 24/09:** espinhos/raios frenéticos eram temporários e cessaram. Usar essa aparência apenas para o momento documentado, sem convertê-la em estado visual permanente. [Fonte, 01:51:20–01:52:04](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-24-exploracao-do-templo-do-fluxo/sessao-2026-09-24-exploracao-do-templo-do-fluxo.md#L2679-L2695).
- **Arco para segunda sombra em 01/10:** efeito episódico de ressonância narrado no impacto; não relâmpago em cadeia disponível a cada golpe. Mostrar apenas as criaturas atingidas conforme resolução. [Fonte, 01:32:10–01:32:51](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-10-01-andares-inferiores-441e1e188cc4b00b74901b904337b9cd1fd669468513102efce50859532f91ec/transcript.curated.md#L1007-L1015).
- **Eco duplicado de Thunderous Smite em 24/09:** a repetição em outro lugar veio da ressonância da cena; não integra a magia-base. [Fonte, 00:46:46–00:46:53](https://github.com/Open-Fantasy-RPG/Jogatina-2026-Kimura/blob/29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce/historico-campanha/sessao-2026-09-24-exploracao-do-templo-do-fluxo/sessao-2026-09-24-exploracao-do-templo-do-fluxo.md#L1050-L1054).

## Controle de revisão

Confirmar edição, ficha completa, preparo atual, alvo e consumo antes de usar uma capacidade em cena nova. Não inventar Divine Sense, Vow of Enmity, Abjure Enemy, Bless, Cure Wounds, Aura de Proteção ou lista automática de juramento. Menção de Divine Smite não prova execução. Nome do recurso de liderança continua pendente; seu efeito documentado não é autorização para corrigir a ficha.

Leitura-base conferida em 04/10/2026, commit público `29f52c4ab4fe7dd3df28d4a32672f9bbdd72d0ce`. Esta data documenta a consulta, não aprovação das propostas.
