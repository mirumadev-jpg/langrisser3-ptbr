# Langrisser III — tradução PT-BR

Projeto de fã para traduzir *Langrisser III* (Sega Saturn, Japão) para português brasileiro. A tradução parte do japonês, com a versão inglesa como apoio de contexto e de layout, e busca preservar o sentido e o tom de cada cena em uma fala que soe natural no Brasil.

**Estado:** os cenários 1 a 6 foram revisados e aprovados. O cenário 7 é o próximo da tradução; os roteiros aprovados ficam em `scripts/pt-br/`.

**[Abrir a página do projeto](https://mirumadev-jpg.github.io/langrisser3-ptbr/)** · **[Ver os créditos](CREDITS.md)** · **[Ver os roteiros](scripts/pt-br/)**

## Sobre Mim

Sou Miruma: dev solo, artista, compositor e escritor. Estou trabalhando em jogos comerciais e gratuitos. Resolvi traduzir *Langrisser III* porque amo a franquia e quero aproximar essa obra do público brasileiro.

Há milhões de anos (risos), a arte de Satoshi Urushihara me inspirou a desenhar. É uma honra trazer uma obra cuja identidade visual me marcou para mais perto de quem fala português. Também sou entusiasta de jogos com romances possíveis; esse tipo de relação entre personagens me encanta e certamente vai aparecer nos meus próprios jogos.

## Andamento

- Cenário 1 — tradução revisada e aprovada.
- Cenário 2 — tradução revisada e aprovada.
- Cenário 3 — tradução revisada e aprovada.
- Cenário 4 — tradução revisada e aprovada.
- Cenário 5 — tradução revisada e aprovada.
- Cenário 6 — tradução revisada e aprovada.
- Cenário 7 — próximo da fila.

Os arquivos publicados ficam em [`scripts/pt-br/`](scripts/pt-br/). Eles preservam códigos de controle e placeholders necessários ao roteiro.

## Nota de terminologia

Em PT-BR, usamos **magia/magias**, **conjurar magia** ou **fazer magia** para poderes sobrenaturais. **Mágica** fica para truques de palco e ilusionismo, a menos que o contexto peça outra coisa.

Também priorizamos expressões que soem naturais no Brasil e preservem a voz de cada personagem: por exemplo, “fazer bico” em vez de “fazer beiço” e “não tenho noção de direção” em vez de uma construção literal. Em objetivos com peso narrativo, preferimos “civis” a rótulos técnicos como “NPCs”, para não quebrar a imersão. No cenário 5, a fala afetuosa e levemente ciumenta de Tiaris usa “bobo”; nos diários, usamos “recém-nomeado” para o cavaleiro e “as coisas não têm sido fáceis” para o relato da Runa.

## Notas técnicas

A base técnica é o release [v0.8.0 do Langrisser III English Patch](https://github.com/hexerkat/langrisser3-english/releases/tag/v0.8.0). O repositório original descreve o pipeline como reutilizável para outras línguas. Este repositório ainda é um projeto de tradução textual, não um patch PT-BR pronto para aplicar.

Antes de uma build serão necessários, no mínimo:

- ampliar o mapa de glifos da fonte para incluir acentos, cedilha, maiúsculas e minúsculas do português; avaliar pares de letras comprimidos;
- completar os roteiros e revisar nomes e termos num glossário;
- executar QA de layout em português, ajustar as quebras `<$FFFC>` e testar no jogo;
- validar o pipeline de build para PT-BR.

O patcher pronto do release é voltado à versão inglesa. Nenhum arquivo de jogo, ROM, ISO, binário, música, vídeo ou arte extraída é distribuído neste repositório. Para jogar, é necessário possuir uma cópia legítima do disco japonês.

## Créditos

Agradecimentos ao projeto [Langrisser III English Patch](https://github.com/hexerkat/langrisser3-english), a `hexerkat` pela manutenção e autoria da versão inglesa atual, e a `ralfguth`, autor original do patch-base e de partes fundamentais da ferramenta. Os créditos herdados completos estão em [CREDITS.md](CREDITS.md).

A arte de Satoshi Urushihara, designer de personagens de *Langrisser III*, inspirou Miruma a desenhar e é uma das razões afetivas deste projeto.

## Licença e aviso

Este repositório mantém a licença GPL-3.0 já presente. A licença cobre apenas o material a que seus autores podem conceder direitos; não licencia *Langrisser III* nem seus elementos protegidos. Este é um projeto de fã, não oficial e sem afiliação, patrocínio ou endosso de Masaya, NCS ou dos titulares dos direitos.
