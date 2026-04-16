1. Idea del joc
RPG de combat per torns centrat en l'estratègia i la deducció de debilitats en un entorn tancat de 5 habitacions.

Objectiu
Derrotar el cap final de la cinquena habitació superant els combats previs mitjançant la gestió d'equips.

Rol del jugador
Un líder d'equip que ha d'investigar l'entorn/diàlegs per configurar el grup d'aliats òptim abans de cada batalla.

Regles i condicions
Sistema Press Turn: Encertar debilitats o crítics dona "mitja acció" extra. Fallar o ser bloquejat penalitza perdent accions o el torn sencer.

Condició de Victòria: Reduir els HP de l'enemic a 0.

Condició de Derrota: Que tots els membres de l'equip actiu caiguin derrotats.

Bucle de joc
Entrada a l'habitació: Diàleg amb l'enemic + Pistes.

Preparació: Gestió de l'equip (triar 3 aliats de 5 disponibles).

Combat: Execució del sistema Press Turn.

Resolució: Pas a la següent habitació o Game Over.

Estats del joc
Stats base: HP, SP, ATK, DEF, EN, LUK, AGI, DEX.

Estats alterats: Refredat, Cremat, Congelat, Ira (amb modificadors percentuals).

Repte i dificultat
El repte no és el "grind" (nivells), sinó el coneixement. El jugador ha d'entendre les debilitats elementals per no perdre torns.

Limitacions (Scope)
NO hi ha inventari, ni experiència, ni animacions complexes.

Màxim 5 aliats totals i 5 enemics únics.

Gràfics: Sprites estàtics (IA) i interfície de text/llistes.

2. Riscos tècnics
Lògica de torns (Press Turn): Complexitat en la gestió de mitges accions. Solució: Sistema de punts (Acció = 2 pts).

Càlcul de mal i buffs: Bugs en acumulació de modificadors. Solució: Script únic de combat.

Gestió de menús: Temps de programació de UI. Solució: Menús de llista simple en GameMaker.

3. Exploració amb IA
Visual: Generació de 5 sprites de caps elementals (Pixel Art).

Dades: Estructura JSON/Arrays per a les estadístiques dels 5 aliats i 5 enemics.

4. Proposta final i viabilitat
Viable (9-10 hores). El projecte està ben acotat. La clau és no desviar-se cap a la cosmètica visual i centrar-se en el codi de la màquina d'estats de combat.

5. Pla de treball
Hores 1-4: Motor de combat (Lògica Press Turn, Mal, Estats).

Hora 5: Menús de selecció d'aliats i interfície bàsica.

Hores 6-9: Disseny de les 5 habitacions, diàlegs i balanceig de stats.

Hora 10: Poliment de bugs i proves de flux.

6. Eines i tecnologies
Motor: GameMaker.

Gràfics: IA Generativa (Sprites) + Editor intern (UI).

Llenguatge: GML (GameMaker Language).