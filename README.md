# Campus que se deixa ler

Mapa acessível do campus UnB Gama (FCTE). É a parte digital de um mapa tátil com QR Code e etiqueta NFC, feito para que pessoas cegas, com baixa visão ou com mobilidade reduzida encontrem prédios e caminhos sem depender de terceiros.

Site: <https://welder60.github.io/acessibilidade_fcte/>

## O que o site faz

- Mapa esquemático do campus, com o norte para cima, edifícios e trilhas do calçadão.
- Escolha de origem ("você está aqui") e de destino, com a descrição do caminho em texto e em áudio.
- Ponto de partida automático pelo endereço aberto no QR Code ou na etiqueta NFC (`#id-do-ponto`).
- Placas em grade, prontas para imprimir, com o QR Code de cada ponto.
- Leitor de tela, bom contraste e linguagem simples. Não coleta dados nem usa cookies.

## Três camadas

1. **Tato:** mapa em relevo, com título e legenda em braille.
2. **Aproximação e imagem:** QR Code e NFC em molduras em relevo.
3. **Digital:** esta página, que pode ser atualizada sem trocar a placa.

## Estrutura

Tudo está em um único arquivo, `index.html`, com HTML, CSS e JavaScript, sem dependências nem etapa de build.

Para ver localmente, abra o `index.html` no navegador.

## Publicação (GitHub Pages)

Em **Settings → Pages**, escolha **Deploy from a branch**, a branch principal e a pasta `/ (root)`.

## Estado atual

Primeira versão, da entrega parcial. O levantamento em campo de rampas, elevadores, piso tátil e banheiros acessíveis está em andamento. As rotas descrevem direção e distância aproximada, não as condições de cada trecho. Entrega final: 25 de novembro de 2026.

## Quem faz

Grupo 9 da disciplina Humanidades e Cidadania (FGA0164), turma 02, 2026.2, UnB Gama (FCTE), com a professora Sandra Maria Faleiros Lima.

- Giovanna Ramos Ribeiro Bilhão
- João Pedro Câmara Leão
- Maria Lívia Aparecida
- Maria Luiza Teixeira Duarte
- Welder Rodrigues de Medeiros
- Yago Silva Marinho

## Base legal e técnica

- Lei nº 13.146/2015 (Lei Brasileira de Inclusão)
- ABNT NBR 9050:2020
- Diretrizes de Acessibilidade para Conteúdo Web (WCAG)
