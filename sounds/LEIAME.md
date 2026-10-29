# Sons gravados (opcional)

O jogo sintetiza todos os sons. Para trocar algum por uma gravação de verdade:

1. Baixe sons com licença **CC0 / domínio público** (por exemplo, no Freesound filtrando por "Creative Commons 0", ou no OpenGameArt filtrando por CC0). Não use sons extraídos de outros jogos (CS 1.6 etc.): eles têm dono.
2. Coloque os arquivos (`.ogg`, `.mp3` ou `.wav`) nesta pasta.
3. Crie `sons.json` nesta pasta dizendo qual arquivo substitui qual som, por exemplo:

```json
{ "pistol": "pistola.ogg", "rifle": "fuzil.ogg", "step0": "passo1.ogg", "step1": "passo2.ogg", "step2": "passo3.ogg", "step3": "passo4.ogg" }
```

Nomes que dá para trocar: pistol, deagle, revolver, smg, rifle, semi, lmg, shotgun, sniper, rocket, xbow, bowTwang, bowDraw, crank, knife, knifeHit, knifeWall, boom, magOut, magIn, empty, draw, zoom, step0..step3 (passos, sorteados), land, slide, hurt, hit, head, kill, round, spray, build.

Quem não estiver na lista continua sintetizado. Anote de onde veio cada som (autor e link) em `CREDITOS.md` nesta pasta.
