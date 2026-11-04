# De onde vieram os sons

Todos **CC0 (domínio público)**: pode usar, mudar e vender sem pedir nem dar crédito. Os arquivos foram cortados
(um disparo só, com o fim do eco), passados para mono e com o volume igualado.

| Arquivo | Gravação original | Fonte |
|---|---|---|
| pistol.ogg | Walther PPQ 9 mm (X_38, gravação atrás do atirador) | The Free Firearm Sound Library, https://opengameart.org/content/the-free-firearm-sound-library |
| deagle.ogg | Colt 1911 .45 (A_35, atrás do atirador), mais grave | idem |
| revolver.ogg | Smith & Wesson 642 .38 (V_24), tom abaixado | idem |
| smg.ogg | Carl Gustav M45 9 mm (G_26) | idem |
| rifle.ogg | AR-15 5.56 (D_27) | idem |
| semi.ogg | Savage Model 10 .300 (T_24) | idem |
| lmg.ogg | AK-47 7.62x39 (C_39), tom abaixado | idem |
| shotgun.ogg | Benelli Nova calibre 12 (O_18) | idem |
| sniper.ogg | Tikka T3 .30-06 (W_26), tom abaixado | idem |
| musket.ogg | Mosin Nagant 7.62x54 (M_21P) | idem |
| blunder.ogg | Winchester Model 12 calibre 12 (K_22P) | idem |
| minigun.ogg | PPSh 7.62x25 (P_30P) | idem |
| st_stone0..5.ogg, st_sand0..5.ogg | Fantozzi's Footsteps (pedra e areia) | https://opengameart.org/content/fantozzis-footsteps-grasssand-stone |
| st_grass0..4.ogg, st_wood0..4.ogg | Kenney, Impact Sounds (footstep_grass, footstep_wood) | https://kenney.nl/assets/impact-sounds |
| st_metal0..4.ogg | Kenney, Impact Sounds (footstep_concrete misturado com impact_metal_light) | idem |
| rl_magout, rl_magin2, rl_rack | LFA, Equipment Clicks III | https://opengameart.org/content/equipment-clicks-iii |
| rl_magin, rl_shell | Brian MacIntosh (BMacZero), Gun Reload Sound Effects (clipload2, singlebullet1) | https://opengameart.org/content/gun-reload-sound-effects |
| rl_pout, rl_pin, rl_prack | zer0_sol, Handgun Reload Sound Effect | https://opengameart.org/content/handgun-reload-sound-effect |
| rl_rack2 | SpringySpringo, Gun Reload Sounds | https://opengameart.org/content/gun-reload-sounds |

Baixados dos espelhos em https://github.com/petroulacl/fps-asset-kit, https://github.com/Boyquotes/kenney-impact-sounds-for-godot, https://github.com/VtCasagrande/warcats-web e https://github.com/DeathByDenim/openspades-free-pak (só os arquivos marcados CC0 lá).

**Tiros com peso (2026-11-03):** os tiros de arma de fogo foram refeitos a partir das faixas brutas da mesma biblioteca (CC0, em https://github.com/buddingmonkey/FreeFirearmsSFXLibrary): corte do primeiro disparo gravado atrás do atirador, tom ajustado por arma, camada grave sintetizada por baixo (o soco), estalo do gatilho/martelo logo antes do tiro e uma saturação leve. A camada grave e o estalo são gerados por código, sem amostra de terceiros.

Atualização (v87): os tiros foram refeitos com camada de estrondo grave (80–350 Hz), reverberação curta, compressão forte e saturação, para ficarem bem mais altos e pesados. Mesmas gravações-base CC0 da FreeFirearmsSFXLibrary.

v90: tiros sem camadas sintéticas. Cada tiro é a gravação real (FreeFirearmsSFXLibrary, CC0) com a cauda natural, mais o grave de outra gravação real da mesma biblioteca (AR-15, Tikka, Walther) por baixo, compressão e limite suave. Nenhum som de jogo comercial é usado.

## v101 (2026-11-04)
- Tiros refeitos com timbre próprio por arma (altura, equalização e cauda de ambiente diferentes), sniper e escopeta mais fortes. Origem: FreeFirearmsSFXLibrary (CC0), processado por script.
- `kill.ogg` e `head.ogg` (som de abate e de headshot, no lugar do sino): sintetizados por script, sem amostras de terceiros.
