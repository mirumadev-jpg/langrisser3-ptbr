<p align="center">
  <img src="langrisser3-ptbr-banner.png" alt="Banner ilustrado de Langrisser III: a protagonista de cabelos prateados diante de uma lua e um castelo, com o título Langrisser III e Tradução PT-BR." width="960">
</p>

# Langrisser III — tradução PT-BR

Projeto de fã para traduzir *Langrisser III* (Sega Saturn, Japão) para português brasileiro. A tradução parte do japonês, que também é a referência para linhas e marcadores técnicos; a versão inglesa serve apenas de apoio contextual. A meta é preservar o sentido e o tom de cada cena em uma fala que soe natural no Brasil.

**Estado:** os 36 cenários foram traduzidos, revisados e aprovados. Os roteiros aprovados ficam em `scripts/pt-br/`; a próxima fase é desenvolver e testar a ferramenta de patch PT-BR.

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
- Cenário 7 — tradução revisada e aprovada.
- Cenário 8 — tradução revisada e aprovada.
- Cenário 9 — tradução revisada e aprovada.
- Cenário 10 — tradução revisada e aprovada.
- Cenário 11 — tradução revisada e aprovada.
- Cenário 12 — tradução revisada e aprovada.
- Cenário 13 — tradução revisada e aprovada.
- Cenário 14 — tradução revisada e aprovada.
- Cenário 15 — tradução revisada e aprovada.
- Cenário 16 — tradução revisada e aprovada.
- Cenário 17 — tradução revisada e aprovada.
- Cenário 18 — tradução revisada e aprovada.
- Cenário 19 — tradução revisada e aprovada.
- Cenário 20 — tradução revisada e aprovada.
- Cenário 21 — tradução revisada e aprovada.
- Cenário 22 — tradução revisada e aprovada.
- Cenário 23 — tradução revisada e aprovada.
- Cenário 24 — tradução revisada e aprovada.
- Cenário 25 — tradução revisada e aprovada.
- Cenário 26 — tradução revisada e aprovada.
- Cenário 27 — tradução revisada e aprovada.
- Cenário 28 — tradução revisada e aprovada.
- Cenário 29 — tradução revisada e aprovada.
- Cenário 30 — tradução aprovada e publicada.
- Cenário 31 — tradução aprovada e publicada.
- Cenário 32 — tradução aprovada e publicada.
- Cenário 33 — tradução aprovada e publicada.
- Cenário 34 — tradução aprovada e publicada.
- Cenário 35 — tradução aprovada e publicada.
- Cenário 36 — tradução revisada, aprovada e publicada.

Os arquivos publicados ficam em [`scripts/pt-br/`](scripts/pt-br/). Eles preservam a sequência de códigos de controle e placeholders do roteiro japonês; a versão inglesa é usada apenas como apoio de contexto.

## Nota de terminologia

Em PT-BR, usamos **magia/magias**, **conjurar magia** ou **fazer magia** para poderes sobrenaturais. **Mágica** fica para truques de palco e ilusionismo, a menos que o contexto peça outra coisa.

Também priorizamos expressões que soem naturais no Brasil e preservem a voz de cada personagem: por exemplo, “fazer bico” em vez de “fazer beiço” e “não tenho noção de direção” em vez de uma construção literal. Em objetivos com peso narrativo, preferimos “civis” a rótulos técnicos como “NPCs”, para não quebrar a imersão. No cenário 5, a fala afetuosa e levemente ciumenta de Tiaris usa “bobo”; nos diários, usamos “recém-nomeado” para o cavaleiro e “as coisas não têm sido fáceis” para o relato da Runa.

Interjeições e onomatopeias também devem soar brasileiras: adaptar sons como “Kuh” para “Urgh!”, “Ugh!” ou outra forma natural conforme a fala, em vez de transliterá-los mecanicamente.

## Notas técnicas

A base técnica é o release [v0.8.0 do Langrisser III English Patch](https://github.com/hexerkat/langrisser3-english/releases/tag/v0.8.0), usado como referência para adaptar o builder. O roteiro japonês é a autoridade para a estrutura e os marcadores de controle; a versão inglesa serve apenas de apoio contextual. Os 36 roteiros PT-BR estão completos, mas este repositório ainda não contém um patch aplicável.

Antes de uma build PT-BR serão necessários, no mínimo:

- adaptar o builder para localizar os roteiros PT-BR e validar sua estrutura e seus marcadores contra os arquivos japoneses;
- ampliar o mapa de glifos da fonte para incluir acentos, cedilha, maiúsculas e minúsculas do português; avaliar pares de letras comprimidos;
- traduzir os recursos de texto que ficam fora dos cenários, como menus, nomes e mensagens do sistema;
- executar QA de layout em português e testar o resultado no jogo;
- validar o pipeline de build para PT-BR.

O patcher pronto do release é voltado à versão inglesa. Nenhum arquivo de jogo, ROM, ISO, binário, música, vídeo ou arte extraída é distribuído neste repositório. Para jogar, é necessário possuir uma cópia legítima do disco japonês.

## Próxima fase: ferramenta de patch

O trabalho seguinte é adaptar o builder v0.8.0 para os recursos PT-BR e testar a geração da imagem localmente com uma cópia legítima e compatível do disco japonês. A ferramenta e o patch só serão considerados prontos após validação do texto, da fonte, dos menus e do funcionamento no jogo.

## Créditos

Agradecimentos ao projeto [Langrisser III English Patch](https://github.com/hexerkat/langrisser3-english), a `hexerkat` pela manutenção e autoria da versão inglesa atual, e a `ralfguth`, autor original do patch-base e de partes fundamentais da ferramenta. Os créditos herdados completos estão em [CREDITS.md](CREDITS.md).

A arte de Satoshi Urushihara, designer de personagens de *Langrisser III*, inspirou Miruma a desenhar e é uma das razões afetivas deste projeto.

## Licença e aviso

Este repositório mantém a licença GPL-3.0 já presente. A licença cobre apenas o material a que seus autores podem conceder direitos; não licencia *Langrisser III* nem seus elementos protegidos. Este é um projeto de fã, não oficial e sem afiliação, patrocínio ou endosso de Masaya, NCS ou dos titulares dos direitos.
