# Inventário de texto PT-BR — patcher v0.8.0

## Escopo e regra de contagem

O escopo fechado deste plano é o conjunto de arquivos `.txt` existente em `scripts/en` na base do patcher v0.8.0: **144 arquivos-alvo**. A lista inglesa serve somente para enumerar os arquivos e manter a convenção de nomes esperada pelo builder. A tradução, as linhas e os marcadores técnicos devem vir dos arquivos japoneses correspondentes; o inglês não é molde nem fonte de tradução.

Para este acompanhamento, **um arquivo-alvo equivale a um lote**. O percentual é por quantidade de arquivos, não por palavras, caracteres ou esforço: **36/144 concluídos (25%); 108/144 pendentes**. Os arquivos PT-BR continuam usando o sufixo `E` porque essa é a convenção técnica esperada pelo patcher.

## Resumo por família

| Família | Arquivos-alvo | Fonte japonesa | Total | Aprovados | Pendentes |
|---|---|---|---:|---:|---:|
| Roteiros `scen` | `scen001E.txt`–`scen125E.txt` | `scen001J.txt`–`scen125J.txt` | 125 | 36 (`001`–`036`) | 89 (`037`–`125`) |
| Recursos de sistema/UI `fntsys` | `fntsys1E.txt`–`fntsys15E.txt` | `fntsys1J.txt`–`fntsys15J.txt` | 15 | 0 | 15 |
| Texto de progressão | `plotE.txt` | `plotJ.txt` | 1 | 0 | 1 |
| Tabela de magias | `prog3_magicE.txt` | `prog3_magic_JP.txt` | 1 | 0 | 1 |
| Tabela de habilidades | `prog3_skillE.txt` | `prog3_skill_JP.txt` | 1 | 0 | 1 |
| Janelas do sistema/batalha | `syswinE.txt` | `syswinJ.txt` | 1 | 0 | 1 |
| **Total** | **144 arquivos** |  | **144** | **36** | **108** |

Os 36 arquivos já aprovados são os roteiros de batalha `scen001E.txt`–`scen036E.txt`. Os 89 arquivos `scen037E.txt`–`scen125E.txt` ainda precisam ser traduzidos; sua classificação narrativa será confirmada pelo japonês durante o trabalho.

## Próximos lotes: menus e itens

1. **Nomes de itens:** `scripts/jp/fntsys10J.txt` → `scripts/pt-br/fntsys10E.txt`.
2. **Descrições de itens e equipamentos:** `scripts/jp/fntsys13J.txt` → `scripts/pt-br/fntsys13E.txt`. O formato conhecido contém 175 descrições em uma grade fixa de registros; há ainda um registro reservado em branco. Preservar exatamente a quantidade e a ordem de registros do original japonês.
3. **Demais recursos de sistema/UI:** `fntsys1`–`fntsys9`, `fntsys11`–`fntsys12` e `fntsys14`–`fntsys15`, sempre do arquivo japonês de mesmo número para o destino PT-BR correspondente.
4. **Janela de sistema/batalha:** `syswinJ.txt` → `syswinE.txt`.
5. **Tabelas de jogo:** `prog3_magic_JP.txt` → `prog3_magicE.txt` e `prog3_skill_JP.txt` → `prog3_skillE.txt`.
6. **Progressão:** `plotJ.txt` → `plotE.txt`.
7. **Roteiros restantes:** `scen037J.txt`–`scen125J.txt` → `scen037E.txt`–`scen125E.txt`.

O total desta fila é 108 arquivos pendentes: 15 `fntsys`, 4 recursos individuais e 89 roteiros `scen`. A ordem é uma proposta de organização, não autorização para publicar rascunhos; cada arquivo novo continua sujeito à revisão e aprovação de Miruma.

## Arquivos fora deste inventário

A lista não inclui arquivos que existam somente em `scripts/jp`, auxiliares de extração, arquivos `_scan_`, nem imagens de disco ou binários. Isso segue a regra do projeto: somente os `.txt` da base inglesa definem os destinos deste backlog, enquanto o japonês permanece a autoridade para o conteúdo traduzido e para os marcadores. Nenhum texto protegido do jogo é reproduzido neste inventário.
