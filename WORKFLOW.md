# Workflow do projeto — Langrisser III PT-BR

Este documento registra o fluxo de trabalho para continuar o projeto com consistência entre sessões e colaboradores.

## Princípios editoriais

- Traduzir do japonês. Usar a versão inglesa apenas como apoio contextual, nunca como referência de layout ou molde literal; o japonês é a fonte para linhas e marcadores técnicos.
- Preservar sentido, tom, voz dos personagens e naturalidade em português brasileiro.
- Manter nomes e termos consistentes com um glossário compartilhado, a ser ampliado durante a tradução.
- Para poderes sobrenaturais, usar “magia/magias”, “conjurar magia” ou “fazer magia”; reservar “mágica” para truques de palco/ilusionismo.
- Preferir formulações idiomáticas do português brasileiro, como “fazer bico” e “não tenho noção de direção”; respeitar a voz e a nuance emocional de cada personagem (por exemplo, “bobo” na fala afetuosa e levemente ciumenta de Tiaris).
- Priorizar termos diegéticos em objetivos e avisos: usar “civis” quando se trata de civis, em vez do rótulo técnico “NPCs”, para preservar a imersão.
- Em diários, escolher termos naturais e precisos para o contexto, como “cavaleiro recém-nomeado”; preservar a voz cansada e determinada da Runa em “as coisas não têm sido fáceis”.
- Adaptar interjeições e onomatopeias à fala brasileira: não manter transliterações mecânicas como “Kuh”; escolher “Urgh!”, “Ugh!” ou outra forma natural conforme a emoção e a voz do personagem. Para gritos e rugidos de monstros, preferir formas reconhecíveis em quadrinhos ocidentais em português (por exemplo, “GRRAAAH!” e “AAARGH!”), não transliterações silábicas japonesas.
- Nas falas da tribo Shika, preservar a sintaxe tribal marcada e direta (por exemplo, “Esta ser terra sagrada dos Shika” e “Vocês profanar nossa terra sagrada”), sem normalizar para o português padrão. Em outras vozes, priorizar formulações naturais e concisas.
- Trabalhar os cenários em ordem. O roteiro seguinte é sempre um rascunho até ser revisado e aprovado por Miruma.
- Escopo atual: a primeira versão do jogo será sem acentos; o suporte completo à acentuação fica para uma etapa futura, condicionada ao apoio e às doações. Manter os roteiros aprovados intactos; não retirar acentos dos arquivos publicados sem autorização explícita.

## Ciclo de trabalho de cada cenário

1. Identificar o arquivo-fonte, a numeração do cenário e os materiais de referência disponíveis. Não sobrescrever conteúdo aprovado.
2. Preparar a tradução/adaptação em arquivo de trabalho separado, preservando a estrutura do original.
3. Conferir marcadores de controle, placeholders e quebras de linha, inclusive `<$FFFC>`. Adaptar as quebras ao texto em português sem remover códigos necessários.
4. Revisar fluidez, sentido, nomes, termos, pontuação e consistência com os roteiros aprovados.
5. Entregar o cenário completo para revisão de Miruma. Registrar sugestões como rascunho; não publicar nem tratar como aprovado antes da confirmação explícita.
6. Após a aprovação, conferir o arquivo final e compará-lo com a cópia aprovada; só então publicar em `scripts/pt-br/`.
7. Atualizar os registros de andamento da página e do README somente quando refletirem o estado real do projeto.

## Estado aprovado registrado

Os 36 roteiros aprovados e publicados até aqui são lotes de batalha, não a tradução do jogo inteiro. O escopo de acompanhamento é o conjunto de 144 arquivos `.txt` em `scripts/en` da base do patcher: 36 concluídos e 108 pendentes, contando um arquivo como um lote. Essa contagem mede arquivos, não volume de texto. Não apresentar 36/36 como conclusão geral do jogo.

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
- Cenário 18: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 19: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 20: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 21: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 22: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 23: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 24: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 25: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 26: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 27: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 28: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 29: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 30: aprovado e publicado conforme solicitação explícita de Miruma.
- Cenário 31: aprovado e publicado conforme solicitação explícita de Miruma.
- Cenário 32: revisado, aprovado e publicado após aprovação explícita de Miruma.
- Cenário 33: aprovado e publicado conforme aprovação explícita de Miruma.
- Cenário 34: aprovado e publicado conforme aprovação explícita de Miruma.
- Cenário 35: aprovado e publicado conforme aprovação explícita de Miruma.
- Cenário 36: revisado, aprovado e publicado conforme solicitação explícita de Miruma.

## Regras técnicas e de qualidade

- Preservar códigos de controle, placeholders e a organização dos arquivos de roteiro. O conjunto de destinos é delimitado pelos 144 arquivos `.txt` presentes em `scripts/en`; esses nomes servem somente para enumerar os alvos e manter a convenção do builder.
- Usar os arquivos japoneses correspondentes como autoridade para conteúdo, linhas e sequências de marcadores; validar o PT-BR contra o japonês, não contra o inglês, que pode ter sido adaptado.
- Para a primeira build, entregar texto dentro do jogo sem acentos, preservando os roteiros aprovados e tratando a normalização no pipeline, não por edição silenciosa dos textos publicados. Deixar o suporte completo a acentos e cedilha para etapa futura condicionada a doações; validar quebras, layout e pipeline da versão inicial.
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

## Próxima fase: completar a tradução do jogo

Os 36 roteiros de batalha estão publicados; não afirmar que o jogo inteiro está traduzido. Restam 108 dos 144 arquivos-alvo. Seguir o [inventário e a ordem sugerida](docs/PTBR_TEXT_BACKLOG.md), começando por nomes e descrições de itens (`fntsys10` e `fntsys13`) e depois pelos demais recursos. Traduzir sempre a partir do japonês, planejar a primeira versão sem acentos e manter os roteiros aprovados intactos. Depois, adaptar e validar o builder v0.8.0 em uma cópia legítima e compatível do disco japonês. Não distribuir imagens de disco nem dados protegidos do jogo.
