## Type de modification
_Coche au moins une case_

- [X] Ajout de pattern
- [ ] Correction de pattern existant
- [ ] Amélioration / clarification
- [ ] Autre (à préciser)


## Description

player_warp
player_back
chunk_access
chunk_unaccess
faction_chat
faction_invite
faction_uninvite
faction_promote
faction_demote
faction_perms
war_reason_add
war_surrend
player_death

## Exemple de log réel

> Obligatoire pour tout ajout ou modification de pattern

```player_warp
2026-01-28 12:41:02 [INFO] [NationsGUI] Thathan007 vient de payer 20 pour se téléporter au warp america_north
```
```player_back
2026-01-28 12:45:01 [INFO] [NationsUtils] Back du joueur Xork vers world, 3493.253315973999, 10.0, -291.93180085144377
```
```chunk_access
2026-01-28 13:11:03 [INFO] [Factions] Player 0rca set access to player KarkJad in chunk 336, -172 to true
```
```chunk_unaccess
2026-01-28 15:13:05 [INFO] [Factions] Player nono1445 remove access to player adri22055 in chunk 95, -18 to false
```
```faction_chat
2026-01-28 15:44:25 [INFO] [FactionChat] FACTION|CEDROX: mrc
```
```faction_invite
2026-01-28 15:56:45 [INFO] [Factions] Player clemdefrance2020 invited 8_tangokou to join country Qatar
```
```faction_uninvite
2026-01-28 18:42:16 [INFO] [Factions] Player N_3h cancelled invitation SamTimbis to join country Algerie
```
```faction_promote
2026-01-28 18:39:54 [INFO] [NationsGUI] Player cuitcuit promoted to officer _MPM_ in country Magadan
```
```faction_demote
2026-01-28 18:28:29 [INFO] [NationsGUI] Player saucebrazil demoted to member brighterzeus799 in country Finlande
```
```faction_perms
2026-01-28 18:28:23 [INFO] [FACTION] saucebrazil changed faction permission warzone to [OFFICER, MEMBER, LEADER]
```
```faction_war_reason_add
2026-01-28 16:23:19 [INFO] [NationsUtils] Add war event kill_wilderness between Ontario and Tadjikistan
```
```faction_war_surrend
2026-01-27 16:54:36 [INFO] [NationsGUI] Kamtchatka SURREND WAR AGAINST Tadjikistan APPLY REWARDS : dollars#465918,peace#9
```
```faction_player_death
2026-01-27 16:56:31 [INFO] [NationsUtils] Le joueur faris785 est mort aux coordonnées : X-81, Y38, Z38
```
---

## Impact potentiel

* [X] Aucun impact sur les patterns existants
* [ ] Impact rétro-compatible
* [ ] Risque de rupture de compatibilité (à justifier)

Justification (si nécessaire) :


## Checklist

* [X] Le fichier YAML est valide
* [X] Aucune clé dupliquée
* [X] Le pattern est dans la bonne catégorie
* [X] Le nom du pattern est explicite et en `snake_case`
* [X] Les variables utilisées sont cohérentes et explicites
* [X] La modification est justifiée (si pattern existant)

## Informations complémentaires

Toute information utile à la revue : RAS
plugin concerné, version serveur, contexte particulier, captures, etc.
