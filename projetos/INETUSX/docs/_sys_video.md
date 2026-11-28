# Guia de Geração de Vídeo (SkyReels V3)

Este arquivo define as regras para geração de vídeos via SkyReels V3.
O campo `prompt` de cada cena usa estas diretrizes.

## Como o SkyReels funciona
O modelo ANIMA as imagens de referência (ref_imgs). O prompt apenas guia:
- Que AçãO/MOVIMENTO ocorre (personagem anda, vira, gesticula)
- Que MOVIMENTO DE CâMERA usar (pan, dolly, push in, zoom)
- O prompt NãO precisa descrever o que já está nas imagens (cenário, cores, roupas)

## Regras do prompt de vídeo
- Escreva em INGLêS — MáXIMO 2 frases curtas
- Foque em: tipo de plano + ação + movimento de câmera
- PROIBIDO: descrições longas, narrativas, contexto ou explicações
- Seja específico sobre direções (up/down/left/right)
- COERêNCIA: o prompt DEVE descrever a mesma ação/direção que o audio_text

## Bons exemplos
"Medium shot, girl stands up gesturing excitedly, camera slowly pushes in, anime style"
"Wide shot, group walks through corridor, camera dollies forward, warm lighting"
"Close-up, boy looks at screen with curiosity, soft camera pan right, anime style"

## Maus exemplos (NUNCA faça)
"Wide establishing shot of a futuristic holographic classroom in 2030. Four teenagers
sit at interactive desks as holographic projections of ancient Greek maps and the
Parthenon illuminate the room in blue and gold light." — MUITO LONGO, descritivo demais

## Referências visuais (ref_imgs)
- MáXIMO 4 imagens por cena
- Use SEMPRE a imagem do ambiente + imagem do personagem que aparece
- NUNCA duas imagens do mesmo personagem (duplica o personagem na cena)
