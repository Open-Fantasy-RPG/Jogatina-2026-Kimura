# Modelos públicos de sessão e cena

1. Criar `sessao-AAAA-MM-DD-slug/README.md` com título, fonte pública e lista de cenas.
2. Preservar o registro original da sessão dentro da pasta, sem substituir por resumo.
3. Criar `cenas/01-slug/`, `02-slug/` etc. segundo ordem comprovada; cenas paralelas/recapitulações devem ser marcadas.
4. Copiar os modelos de [cena](descricao-cena.md) e [local](descricao-local.md), preenchendo somente fatos e descrição aprovados para publicação.
5. Colocar imagens de um local concreto em `cenas/NN-slug/imagens/`, na cena correspondente; reutilizar por links mesmo quando o local reaparece em outras sessões. Usar `referencias/` para referências gerais da sessão e `referencias-compartilhadas/` para contexto geral da campanha, como cidades, mapa regional e NPCs.
6. Escrever a ambientação em prosa a partir da narração e da comparação visual: o que está presente, conservação, relações espaciais e sons/luz com fonte. No templo atual, aplicar ruínas e abandono, preservando a diferença entre áreas mais e menos deterioradas.
7. Registrar proveniência e manter um único arquivo binário. Se a relação não for demonstrável, usar `a-classificar/`.

Este modelo não autoriza divulgar transcrições novas, segredos, rascunhos do mestre ou produção de HQ. A aprovação de conteúdo novo continua obrigatória.

## Identidade por capítulo

Consultar `../capitulos.json` antes de criar entradas. Capítulos novos usam `historico-campanha/capitulos/NNN-slug/`; guardar `chapter_id`, `chapter_number`, `title` e `session_date` separadamente em `chapter.json`. Duas datas iguais não fundem capítulos. Cenas e artefatos não incrementam a numeração. Fontes antigas continuam nos caminhos legados registrados, com navegação pela entrada canônica.
