# Fotonovela — "Fora do Escritório" — Bíblia de Personagens e Roteiros

Recurso narrativo do curso "Agentes de Código no Terminal: CLI, tmux, MCP e
Harness". Mesmo mecanismo já usado nos cursos IA, Git e Engenharia de
Software na Era dos Agentes (ver `[[garagem-fotonovela]]`), mas com elenco
PRÓPRIO (nunca reaproveitar Duda/Rex/Bug nem Fernando/Carol/Marcelo/Rafa) e
uma direção visual deliberadamente diferente: **cenários variados, não só
escritório** — cafeteria estilo Nova York, trânsito/transporte público,
caminhada com fone — decisão do Diego em 2026-07-18, junto com a exigência
de que os personagens tenham nome e apareçam de forma reconhecível (recap
de decisões: reduzir o elenco pra 2 pessoas facilita variar cenário sem
perder consistência de quem é quem).

## 1. Título geral

**"Fora do Escritório"**

## 2. Conceito narrativo

Dois profissionais: um dev pleno sempre em movimento (trabalha remoto, vive
entre cafeteria/trânsito/caminhada) e uma mentora sênior remote-first que o
orienta por chamada de voz/vídeo — quase nunca fisicamente no mesmo lugar
que ele. Cada módulo, o mesmo padrão do curso ESA: abertura (desafio novo
do módulo, ele ainda não sabe resolver) e fecho (mesmo desafio, resolvido
com o conteúdo do módulo). Arco cumulativo: aprendizado de módulos
anteriores nunca regride.

### Regra de cenário (a diferença deste curso pros outros)

Nunca ambientar a cena inteira dentro de um escritório corporativo. Alternar
entre (pelo menos 3 dos 4 abaixo por módulo, entre abertura e fecho):
- **Cafeteria estilo Nova York** — tijolo aparente, luz quente, placa "OPEN"
  em neon ao fundo, mesa de mármore ou madeira escura.
- **Trânsito/transporte público** — metrô, ônibus, banco de trás de
  carro/app de corrida, fones de ouvido.
- **Caminhada com fone** — rua urbana, fones sem fio, celular na mão ou no
  bolso, chamada de voz.
- **Home office/escritório** — usar como base ocasional, nunca cenário
  único do módulo.

## 3. Bíblia dos 2 personagens

### Personagem 1 — Vinícius "Vini" Andrade Cardoso (protagonista)

- **Idade**: ~29 anos
- **Função**: Desenvolvedor Pleno, 100% remoto
- **Personalidade**: curioso, rápido pra experimentar, um pouco disperso —
  vive resolvendo trabalho enquanto está em trânsito ou numa cafeteria
- **Insegurança principal**: acha que só ele não entende as ferramentas
  novas de agente — os colegas parecem já saber
- **Qualidade principal**: aprende rápido quando alguém mostra o caminho
  certo; não tem vergonha de ligar pra pedir ajuda
- **Defeito/ponto cego**: tenta resolver tudo sozinho antes de perguntar,
  perde tempo com solução manual quando existe uma automática
- **Arco**: de "usuário de chat que copia e cola" a alguém que opera
  agentes de CLI, tmux e harness com confiança
- **Aparência física**: homem pardo, 1,78m, magro, cabelo preto curto e
  levemente ondulado, barba rala por fazer, sempre com mochila de notebook
  a tiracolo
- **Roupas**: moletom cinza-chumbo com capuz OU camiseta de banda/tech por
  baixo de uma jaqueta jeans leve (varia por cena, mas sempre estilo
  casual-urbano, nunca traje formal)
- **Acessórios**: fones de ouvido sem fio (no ouvido ou pendurados no
  pescoço), smartwatch preto no pulso esquerdo, notebook com adesivo
  discreto de terminal (`>_`) na tampa
- **Nunca muda**: mochila a tiracolo + fones sem fio + adesivo `>_` no
  notebook + cabelo preto curto ondulado

### Personagem 2 — Helena Marques Beltrão (mentora)

- **Idade**: ~42 anos
- **Função**: Engenheira Sênior, remote-first há anos, orienta o Vini
- **Personalidade**: calma, direta, nunca dá a resposta pronta — pergunta
  até o Vini chegar lá sozinho
- **Qualidade principal**: décadas de prática em decidir o que automatizar
  e o que não vale a pena
- **Aparência física**: mulher negra, 1,65m, cabelo black power curto
  grisalhando nas têmporas, óculos de armação fina redonda
- **Roupas**: blazer leve de linho por cima de camiseta lisa, cores
  terrosas (terracota, verde-oliva, areia) — nunca traje corporativo rígido
- **Acessórios**: headset leve pendurado no pescoço quando não está numa
  chamada, caneca térmica de viagem sempre por perto, brincos pequenos
  geométricos
- **Aparece**: na maioria das cenas por CHAMADA (tela de celular/notebook
  mostrando o vídeo dela, ou só a voz com o ícone de chamada) — encontro
  presencial é raro e reservado pros momentos de virada mais fortes
- **Nunca muda**: cabelo black power grisalhando + óculos redondos finos +
  headset no pescoço + caneca térmica

## 4. Regras de continuidade visual (OBRIGATÓRIO em todo prompt de quadro)

Persona canônica a colar em TODO prompt que contiver o personagem:

- **Vini**: `Vini (SEMPRE O MESMO HOMEM: pardo, 29 anos, magro, 1,78m, cabelo preto curto levemente ondulado, barba rala por fazer, fones de ouvido sem fio no pescoço ou nos ouvidos, mochila de notebook a tiracolo, notebook com um adesivo discreto de terminal ">_" na tampa)`
- **Helena** (presencial): `Helena (SEMPRE A MESMA MULHER: negra, 42 anos, 1,65m, cabelo black power curto grisalhando nas têmporas, óculos de armação fina redonda, blazer leve de linho em tom terroso sobre camiseta lisa, caneca térmica de viagem por perto)`
- **Helena** (em chamada, tela de celular/notebook): `uma tela de celular/notebook mostrando uma videochamada com Helena (mulher negra, 42 anos, cabelo black power grisalhando, óculos redondos finos), qualidade de câmera de webcam, fundo desfocado`

Guard de anatomia (colar em todo prompt com pessoa):
`ANATOMIA HUMANA CORRETA: exatamente dois braços, duas mãos e cinco dedos por mão, sem membros/mãos/dedos extras/duplicados/deformados. TELAS sempre viradas pra pessoa (nunca a traseira/tampa pra frente).`

Guard de texto (colar sempre):
`IMPORTANTE: NÃO desenhe nenhum balão de fala, nenhuma nuvem de pensamento, nenhuma legenda, nenhum texto real e legível de verdade, nenhuma palavra formada, nenhuma letra reconhecível em lugar nenhum da imagem — telas e cartazes devem mostrar só blocos/linhas BORRADAS e ILEGÍVEIS, nunca frases reais. É uma FOTO pura.`

Regra de balão: sempre no canto oposto ao rosto de quem fala; preferir
cantos de baixo (`bl`/`br`) como ponto de partida (lição herdada do curso
ESA — cantos de cima cobrem rosto de gente em pé/sentada perto da borda).

Regra de ambiente: empresas e sistemas 100% fictícios. Nada de marca real,
cliente real, produto real. Fotorrealista/HQ contemporânea.

## 5. Estrutura por módulo

Cada módulo do curso ganha DUAS lessons `Slides` (8 quadros cada): abertura
(logo após a 1ª lesson do módulo) e fecho (penúltima lesson, antes de
qualquer prova/lesson final). Escritas SEMPRE juntas na mesma sessão (regra
herdada do bug de continuidade do curso ESA — nunca produzir abertura e
fecho em momentos separados sem reler o outro lado).

## 6. Estado

Elenco aprovado pelo Diego em 2026-07-18 (Vini + Helena, 2 personagens,
cenários variados). Módulos do curso (10 ao todo):
1. Fundamentos: chat, CLI, agente e harness
2. Setup real dos agentes no terminal
3. tmux na prática: sessões persistentes pra agentes
4. Acesso remoto: SSH, celular e Cloudflare Tunnel
5. Usando Claude Code, Codex, Gemini CLI e OpenCode em tarefas reais
6. Contexto, RTK, arquivos de instrução e prompts de projeto
7. MCP e integrações com ferramentas externas
8. Git Worktree e múltiplos agentes em paralelo
9. Harness mínimo: organizando sessões, tarefas e comandos
10. Projeto final: fluxo real de trabalho com agentes

Produção começa pelo Módulo 1 (piloto, pra validar elenco/tom antes de
seguir pros outros 9).

## 7. ✅ PUBLICADO — Módulo 1 (piloto)

Desafio novo: Vini só sabe usar chat de IA (copia resposta, cola no
terminal, perde contexto a cada rodada). Abertura: travado numa cafeteria,
Helena liga por vídeochamada. Fecho: mesma tarefa resolvida com agente de
CLI que opera direto no terminal — cena se move da cafeteria pra rua/
caminhada até o metrô (com Helena em chamada) e volta pra cafeteria no
fechamento. Lessons: abertura `54a32f0d-37b8-4fde-8a58-12f72f579bb8`, fecho
`211ed1f3-3a9f-4940-894c-29ae2fc1b91e`. 16/16 quadros corretos na primeira
tentativa (elenco reconhecível em cafeteria E rua, adesivo `>_` do Vini e
óculos/cabelo grisalhando da Helena consistentes na tela de chamada). Único
ponto de atenção (não bloqueante): um quadro de rua tem uma placa real de
sinalização urbana ("ESTAÇÃO METRÔ") com texto legível — genérico/
wayfinding, não é marca fictícia nem spoiler de história, mas vale reforçar
o guard de texto nos próximos quadros de rua/exterior.
