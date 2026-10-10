# Organização e divulgação da campanha

## Destino obrigatório do conteúdo

- Todo conteúdo referente a personagem deve ficar em `personagens/`, dentro da pasta do personagem correspondente. Isso inclui ficha, evolução de nível, atributos, habilidades, magias, equipamentos, inventário, antecedentes, história pessoal, interpretação e decisões de progressão.
- Todo novo commit que crie ou altere evolução de personagem deve gravar os arquivos exclusivamente em `personagens/`. Não registrar evolução individual em `historico-campanha/`, no README da raiz ou em outra pasta.
- Todo conteúdo referente aos acontecimentos compartilhados da campanha deve ficar em `historico-campanha/`. Isso inclui relatos de sessão, cronologia, viagens, combates, descobertas e consequências coletivas já aprovadas para os jogadores.
- Menções a personagens dentro de um relato de sessão continuam em `historico-campanha/`; mudanças persistentes na ficha, nas capacidades ou na progressão do personagem devem ser registradas também no arquivo próprio em `personagens/`.
- Quando um commit contiver histórico da campanha e evolução de personagem, separar cada parte no destino correto. Não criar arquivo misto fora dessas duas pastas.
- Antes de concluir qualquer alteração, conferir os caminhos dos arquivos modificados e mover conteúdo colocado no destino errado.

- Guardar todo conteúdo do mestre exclusivamente em `C:/Users/qi_xx/OneDrive/Documentos/GitHub/Mestre - Jogatina/` (fora deste projeto): lore secreta, preparação, NPCs com motivações ocultas, análises, transcrições, versões integrais e rascunhos para revisão.
- `Jogatina/` é a pasta dos jogadores. Não criar nem atualizar conteúdo nela sem aprovação expressa do usuário para o conteúdo exato apresentado.
- O usuário também autorizou a presença de `historico-campanha/` e `personagens/` na raiz de `Jogatina-2026-Kimura`. Essas cópias são destinadas aos jogadores e seguem a mesma revisão e aprovação de conteúdo; versões integrais e notas reservadas permanecem na pasta externa do mestre.
- Antes de divulgar, preparar a versão completa em `C:/Users/qi_xx/OneDrive/Documentos/GitHub/Mestre - Jogatina/aprovacoes/`, mostrar ou vincular essa prévia ao usuário e solicitar aprovação. Uma autorização de organização não autoriza divulgação.
- Após aprovação, copiar apenas a versão aprovada para `Jogatina/` e registrar em `C:/Users/qi_xx/OneDrive/Documentos/GitHub/Mestre - Jogatina/aprovacoes/` o escopo aprovado. Alterações posteriores que acrescentem informações exigem nova aprovação.
- Não criar links, imagens ou anexos na área dos jogadores que exponham material da pasta externa do mestre. Não presumir que um fato jogado está automaticamente autorizado para publicação.
- Manter o README da raiz administrativo, sem segredos ou acontecimentos da campanha.
- Os nomes canônicos são Aeloria, Kaelen (Digo) e Galen (Tata). Preservar transcrições originais como material reservado.

## Pastas canônicas e acervo visual dos personagens

- Usar uma única pasta por personagem: `personagens/Aeloria/`, `personagens/Kaelen Vane/` e `personagens/Galen/`. Aeloria não deve ser duplicada por diferença entre maiúsculas e minúsculas. Kaelen e Kaelen Vane são o mesmo personagem; o nome canônico da pasta é `Kaelen Vane/`. Usar nomes de personagens com inicial maiúscula e o nome completo de Kaelen na pasta.
- Guardar retratos, referências de frente e perfil, poses de ação, tokens e descritivos visuais em `img-visual/`, dentro da pasta correspondente. O texto visual fica em `img-visual/descricao.md`; manter `img-visual/README.md` como índice dos arquivos existentes e das referências completas.
- Antes de criar ilustrações ou HQs, consultar o índice visual, o descritivo e os documentos completos de aparência, interpretação e equipamento ali vinculados. Não tratar sugestões ou detalhes pendentes como decisões confirmadas.
- Preservar os documentos completos de história, background, vida, mecânica e progressão em suas subestruturas próprias, fora de `img-visual/`. A descrição completa de aparência, personalidade e interpretação de Aeloria fica em `personagens/Aeloria/img-visual/descricao.md`, integralmente preservada em um único documento canônico. Não manter uma cópia paralela de interpretação nem substituir os textos completos por resumos visuais.
- Fichas visuais históricas que já acompanham níveis anteriores podem permanecer nesse histórico, com link no índice visual; não duplicar arquivos grandes para reorganizá-los.
- Na unificação ou movimentação, preservar arquivos distintos, revisar referências relativas e índices e conferir colisões de nomes em sistemas sem diferenciação de maiúsculas e minúsculas. O antigo índice de Kaelen Vane fica preservado em `personagens/Kaelen Vane/dossie-de-origem.md`.
- Prompts de produção, planejamento de HQ e material reservado do mestre permanecem na área privada autorizada. Só publicar novos textos ou imagens após a aprovação exigida nas regras acima.

## Capítulos, cenas e referências de locais

- A organização canônica do histórico é por capítulo: `historico-campanha/capitulos/NNN-slug/`, com `README.md` e `chapter.json`. Ler primeiro `historico-campanha/capitulos.json`: `chapter_id` é estável; `chapter_number` define a ordem; `title` nomeia o capítulo; `session_date` é somente atributo. Não numerar por cenas, arquivos, datas, resumos ou versões de HQ.
- A numeração confirmada tem nove capítulos; os dois registros de 08/08 são capítulos distintos. Capítulos 001–002 não possuem transcrição conforme o responsável. Capítulos 003–004 têm relatos resumidos neste Git e transcrições recém-localizadas no acervo privado: não afirmar que os originais estão publicados aqui nem inventar falas do resumo. O capítulo 004 preserva explicitamente a divergência entre data local da gravação (02/09) e registro histórico (03/09).
- Fontes, cenas, referências e imagens dos antigos caminhos `historico-campanha/sessao-.../` foram consolidadas em `historico-campanha/capitulos/NNN-slug/`. Usar somente o capítulo como armazenamento ativo; não recriar pastas de sessão. Preservar IDs de cena, identidade do capítulo, registros e hashes. Consultar os aliases históricos em `mapa-de-caminhos.json` e o registro da migração antes de resolver referências antigas. Novas gravações e novos capítulos seguem a estrutura numerada e a aprovação exata de divulgação definida acima.
- Cada cena contém `descricao-cena.md` e `descricao-local.md`: fonte pública e trecho/tempo, fatos já registrados, observação visual separada, incertezas e campos editáveis do mestre. Os campos do mestre neste repositório são exclusivamente para informação liberada aos jogadores. Não colocar segredos, preparação reservada nem prompts de produção nesses modelos.
- Imagens de um local concreto associado a uma cena ficam em `cenas/NN-slug/imagens/`, mesmo quando reutilizadas por cenas ou sessões posteriores: nesses casos, usar links para o original na cena. Referências gerais de uma sessão podem ficar em `referencias/`. Reservar `historico-campanha/referencias-compartilhadas/` para referências gerais da campanha, como Eldervan, Asura’s Jewel, mapa regional e NPCs. O simples reuso não obriga a mover uma imagem de cena para a área compartilhada.
- A regra de personagens continua valendo para fichas, histórias, progressão e o acervo dos protagonistas. Os retratos públicos de NPCs usados como referência comum das cenas podem ficar no acervo compartilhado de NPCs; isso não cria um segundo histórico/ficha do personagem.
- Usar um único arquivo binário por imagem: mover mantendo bytes e blob SHA, sem recomprimir, redesenhar ou duplicar para cada sessão. Manter nomes históricos em `mapa-de-caminhos.json` e registrar fonte, tamanho e hash no inventário. Atualizar links relativos e índices ao mover um registro.
- Antes de classificar, abrir a imagem e cruzar seu conteúdo com os registros públicos reais. Nome de arquivo sozinho não prova sessão, espécie, ocupante, andar ou data. Se faltar evidência, usar `historico-campanha/a-classificar/` com proveniência e pendência explícita.
- Antes de criar uma HQ, consultar nesta ordem: registro e índice do capítulo, `descricao-cena.md`, `descricao-local.md`, imagens originais e referências completas em `personagens/.../img-visual/`. Utilizar `mapa-de-caminhos.json` para migrar referências antigas, nunca procurar automaticamente uma cópia em `imgs 1/`.
- Distinguir a imagem de um local em seu auge do estado jogado: em 24/09 o saguão e o teatro são descritos como degradados; as imagens são referências históricas. Não transformar decoração, pessoas ou criaturas desenhadas em acontecimentos confirmados.
- Manter documentos originais íntegros. Os descritivos são complementos editoriais e não substituem fontes. Novos fatos públicos, novas transcrições ou imagens e publicação de HQ continuam sujeitos à aprovação definida acima; organização de arquivos já públicos não é autorização para importar material privado.

## Ambientação coerente a partir da narração e das imagens

- Escrever um descritivo utilizável em prosa em cada cena e local, além da lista de fatos. Incluir o que há no espaço, estado de conservação, relações espaciais conhecidas e sons/luz quando houver fonte. Não deixar a ambientação reduzida a um aviso genérico ou a campos vazios.
- A narração do mestre e suas correções definem o estado atual, os presentes e os acontecimentos. Usar os pixels como referência de arquitetura, forma, materiais e composição onde forem coerentes com essa narração. Atribuir explicitamente à imagem qualquer detalhe apenas visual que ainda não esteja confirmado na mesa.
- Para o Templo do Fluxo nas sessões de 22/09 e 24/09, o estado atual é de ruínas e abandono. Imagens que pareçam íntegras orientam a forma da antiga construção; o texto atual deve incorporar o desgaste narrado. Isso não significa que todos os níveis estejam igualmente destruídos: a fonte descreve maior deterioração no nível superior e melhor preservação relativa abaixo.
- Preservar estados sucessivos: autômato inativo antes do desmonte, elevador sabotado antes do reparo, jaulas suspensas antes de formar a barreira. Não levar o estado final da cena para o seu início.
- Não criar acontecimentos, habitantes, criaturas, segredos, funções de objetos ou clima por convenção de gênero. Não atribuir conteúdo oculto aos frascos da arte, vida às figuras de uma ilustração, nem alcance cartográfico a um recorte parcial.
- Manter fontes e marcadores suficientes para revisar o descritivo. As imagens existentes permanecem intactas; criar ou substituir imagens é uma etapa separada e depende da autorização correspondente.

- O mapa da prisão tem destino canônico em `historico-campanha/capitulos/002-cidade-alta-e-prisao/cenas/03-william-e-prisao/imagens/prisao.jpeg`, na cena **William ordena a prisão** da sessão de 08/08/2026. Outras cenas de cárcere, julgamento e fuga devem apontar para esse arquivo; não recriar uma cópia na pasta compartilhada.

## Estrutura interna de cada capítulo

- Guardar a transcrição e o resumo já aprovados em `historico-campanha/capitulos/NNN-slug/transcricao/`: `transcript.md` (ou `transcript.curated.md`, quando curada), `summary.md` e um README de disponibilidade. Não manter fontes paralelas na raiz do capítulo ou em pastas de sessão.
- Guardar cada cena em `cenas/NN-slug/`, com `descricao-cena.md`, `descricao-local.md` e `imagens/README.md`; imagens específicas ficam em `imagens/`. O índice pode apontar para originais compartilhados, sem duplicar binários.
- Guardar o índice de referências e mapas do capítulo em `referencias/`. Manter referências comuns da campanha no acervo compartilhado e vinculá-las às cenas pertinentes.
- Uma pasta ou índice não comprova a existência de conteúdo. Marcar explicitamente transcrições, resumos ou descritivos ausentes; nunca fabricá-los nem importar fontes privadas sob autorização de organização. As regras de aprovação de divulgação continuam integralmente válidas.
