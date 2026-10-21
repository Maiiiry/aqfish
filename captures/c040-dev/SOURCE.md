# Captures c040 (Dev)
- Branche : cycle/c040-couches-effets-pluie, graine 42, time=30
- Commit 1 (refactor EffectLayer) : 35 captures déterministes identiques à l'octet à captures/latest (c039) ; front-panneau non reproductible par construction
- Commit 2 (pluie) : seules bassin-three-quarter-pluie et bassin-top-pluie changent
- bassin-top-pluie : identique à l'octet à c039 avec le fondu neutralisé (ronds inchangés) ; avec fondu, 81 pixels de gouttes diffèrent
- bassin-three-quarter-pluie : 207 pixels non-fond au-dessus du terrain (y < 195) avant, 0 après
- zoom-ronds-* : surface agrandie x3, avant / après ; essai épaissi écarté (ellipses remplies)
