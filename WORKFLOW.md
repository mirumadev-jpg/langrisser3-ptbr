# Workflow do projeto — Langrisser III PT-BR

Este documento registra o fluxo de trabalho para continuar o projeto com consistência entre sessões e colaboradores.

## Princípios editoriais

- Traduzir do japonês. Usar a tradução inglesa como apoio de contexto e referência de layout, nunca como molde literal.
- Preservar sentido, tom, voz dos personagens e naturalidade em português brasileiro.
- Manter nomes e termos consistentes com um glossário compartilhado, a ser ampliado durante a tradução.
- Para poderes sobrenaturais, usar “magia/magias”, “conjurar magia” ou “fazer magia”; reservar “mágica” para truques de palco/ilusionismo.
- Preferir formulações idiomáticas do português brasileiro, como “fazer bico” e “não tenho noção de direção”; respeitar a voz e a nuance emocional de cada personagem (por exemplo, “bobo” na fala afetuosa e levemente ciumenta de Tiaris).
- Priorizar termos diegéticos em objetivos e avisos: usar “civis” quando se trata de civis, em vez do rótulo técnico “NPCs”, para preservar a imersão.
- Em diários, escolher termos naturais e precisos para o contexto, como “cavaleiro recém-nomeado”; preservar a voz cansada e determinada da Runa em “as coisas não têm sido fáceis”.
- Adaptar interjeições e onomatopeias à fala brasileira: não manter transliterações mecânicas como “Kuh”; escolher “Urgh!”, “Ugh!” ou outra forma natural conforme a emoção e a voz do personagem. Para gritos e rugidos de monstros, preferir formas reconhecíveis em quadrinhos ocidentais em português (por exemplo, “GRRAAAH!” e “AAARGH!”), não transliterações silábicas japonesas.
- Nas falas da tribo Shika, preservar a sintaxe tribal marcada e direta (por exemplo, “Esta ser terra sagrada dos Shika” e “Vocês profanar nossa terra sagrada”), sem normalizar para o português padrão. Em outras vozes, priorizar formulações naturais e concisas.
- Trabalhar os cenários em ordem. O roteiro seguinte é sempre um rascunho até ser revisado e aprovado por Miruma.

## Ciclo de trabalho de cada cenário

1. Identificar o arquivo-fonte, a numeração do cenário e os materiais de referência disponíveis. Não sobrescrever conteúdo aprovado.
2. Preparar a tradução/adaptação em arquivo de trabalho separado, preservando a estrutura do original.
3. Conferir marcadores de controle, placeholders e quebras de linha, inclusive `<$FFFC>`. Adaptar as quebras ao texto em português sem remover códigos necessários.
4. Revisar fluidez, sentido, nomes, termos, pontuação e consistência com os roteiros aprovados.
5. Entregar o cenário completo para revisão de Miruma. Registrar sugestões como rascunho; não publicar nem tratar como aprovado antes da confirmação explícita.
6. Após a aprovação, conferir o arquivo final e compará-lo com a cópia aprovada; só então publicar em `scripts/pt-br/`.
7. Atualizar os registros de andamento da página e do README somente quando refletirem o estado real do projeto.

## Estado aprovado registrado

- Cenário 1: revisado, aprovado e publicado.
- Cenário 2: revisado, aprovado e publicado.
- Cenário 3: revisado, aprovado e publicado.
- Cenário 4: revisado, aprovado e publicado.
- Cenário 5: revisado, aprovado e publicado; texto atualizado conforme nova revisão de Miruma.
- Cenário 6: revisado, aprovado e publicado.
- Cenário 7: revisado, aprovado e publicado.
- Cenário 8: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 9: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 10: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 11: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 12: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 13: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 14: revisado, aprovado e publicado após aprovação explícita de Miruma; “velhote” mantido nas falas ajustadas.
- Cenário 15: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 16: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 17: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 18: próximo da fila; manter como rascunho até revisão e aprovação explícita de Miruma.

## Regras técnicas e de qualidade

- Preservar códigos de controle, placeholders e a organização dos arquivos de roteiro.
- Antes de uma build PT-BR, ampliar e testar o mapa de glifos para acentos, cedilha e letras maiúsculas/minúsculas; avaliar pares comprimidos; revisar quebras e layout no jogo; validar o pipeline de build em português.
- O patcher do release inglês não é um patch PT-BR pronto. Não afirmar que existe uma build aplicável até que o pipeline seja adaptado e testado.
- Não substituir nem alterar a licença preexistente sem pedido e revisão específicos.

## Ilustrações e materiais visuais

- Ilustrações originais desenhadas por Miruma podem ser incluídas na página quando ele as fornecer e indicar que estão prontas para uso.
- Registrar autoria e créditos adequadamente. Preferir arte autoral; não incluir imagens extraídas do jogo nem arte de terceiros sem autorização apropriada.
- O uso de ilustrações próprias não altera o caráter não oficial do projeto nem cria afiliação com os titulares de Langrisser III.

## Publicação do site

- O site está em `index.html` na raiz e é publicado pelo GitHub Pages a partir de `main` e `/(root)`.
- Após mudanças de conteúdo aprovadas, verificar o workflow `pages-build-deployment` e testar `https://mirumadev-jpg.github.io/langrisser3-ptbr/`.
- Não criar commits duplicados nem alterar conteúdo fora do escopo aprovado.

## Créditos, direitos e distribuição

- Preservar e atualizar `CREDITS.md` quando houver novos colaboradores ou fontes.
- Manter a indicação de que este é um projeto de fã não oficial e sem afiliação aos titulares de Langrisser III.
- Não distribuir ROM, ISO, binários do jogo, música, vídeo ou arte extraída. A licença GPL-3.0 existente cobre somente materiais cujos autores possam conceder esses direitos; não concede direitos sobre o jogo ou materiais de terceiros.

## Próximo passo de tradução

Retomar o cenário 18 na ordem, preparar um rascunho para revisão de Miruma e aguardar aprovação antes de publicar qualquer arquivo ou atualizar seu status como aprovado.
