# ⚔️ Super Smash Profs Ultimate

Un jeu de combat 2D inspiré de Super Smash Bros, avec des professeurs comme personnages.  
1 à 4 joueurs, 3 maps, objets, boule smash et attaques spéciales.

**Jouer** : ouvrir `game.html` dans un navigateur. Aucune installation requise.

---

## 🎮 Contrôles

| | Mouvement | Saut | Normal | Magie 1 | Magie 2 | Ultime |
|---|---|---|---|---|---|---|
| **P1** | Z Q S D | A | F | G | H | J |
| **P2** | Flèches | Entrée | Ù | * | ) | = |
| **P3** | U I O P | L | B | N | M | V |
| **P4** | IA auto | — | — | — | — | — |

- **R** : rejouer après une partie
- **Clic / touche** : passer l'intro
- Choix DST de M. Oladeji : touches Normal/Magie1 = option A, Magie2/Ultime = option B

---

## 👥 Personnages

### Isaure Fernandes — Maths · Rapide · 3 sauts
*Spécialité : poison et contrôle de zone*

| Attaque | Nom | Effet | Cooldown |
|---|---|---|---|
| Normal | Éval rapide | Lance une feuille d'éval → confus 0.5s | 8s |
| Magie 1 | Chuchotement | Attire les ennemis vers elle | 15s |
| Magie 2 | Cours ennuyant | Empoisonne en continu (-2 PV/s, permanent) | 11s |
| Ultime | Rassemblement Incendie | Rassemble tous les ennemis proches, les met en feu 4s + confus 2s, devient invisible | 100% barre |
| 🔮 Spéciale | Brevet Blanc | Assomme l'ennemi le plus proche : -50% de ses PV + endormi 3s | Boule smash |

**Faiblesse** : Instagram — 3% de chance lors d'une attaque de perdre 50 PV, réinitialiser tous les cooldowns et vider la barre d'ultime.

---

### Sunday Oladeji — Techno · Lent · 1 saut
*Spécialité : bouclier, onde de choc, malus aléatoires*

| Attaque | Nom | Effet | Cooldown |
|---|---|---|---|
| Normal | Chaîne d'énergie | Bouclier hexagonal (-50% dégâts reçus) 4s | 15s |
| Magie 1 | Changement de ton | Attire puis expulse les ennemis proches, 10 dégâts + malus aléatoire | 16s |
| Magie 2 | Poteau-type | 3 passages : 15 dégâts + malus aléatoire à chaque fois | 15s |
| Ultime | Tu es GÊNANT!! | 40 dégâts + 2 malus aléatoires + confus 2s sur tous les proches, +15 PV pour lui | 100% barre |
| 🔮 Spéciale | Pieuvre des fonctions | Fige tous les ennemis 5s | Boule smash |

**Faiblesse** : Correction de DST toutes les 25s — choix entre faire corriger par les élèves (3 malus aléatoires) ou corriger soi-même (cooldowns max + confus 3s).  
**Passif** : retomber sur un ennemi inflige 5 dégâts.

*Malus aléatoires possibles* : empoisonné, aveugle, ralenti, -30% ultime, cooldowns augmentés, +10 dégâts bonus.

---

### Giovanni Zacari — Musique · Moyen · 3 sauts
*Spécialité : contre-attaque, hypnose, musique*

| Attaque | Nom | Effet | Cooldown |
|---|---|---|---|
| Normal | Autographe | Coup de stylo : 5 dégâts aux 2 ennemis les plus proches | 3s |
| Magie 1 | Cou d'écou | Timbale : le prochain ennemi qui attaque dans la seconde est zombifié 3s | 20s |
| Magie 2 | Impro | Le prochain ennemi qui bouge dans la seconde est confus 2s (+5 PV pour Giovanni) | 20s |
| Ultime | Mambo italiano | Hypnotise la moitié des ennemis 7s (ils marchent vers lui), immunité 7s. Si les hypnotisés n'infligent pas assez de dégâts : -60 PV + 2 malus | 100% barre |
| 🔮 Spéciale | Famille royale du Bénin | Invoque un clone IA de Giovanni (50 PV, 15s) avec les mêmes attaques | Boule smash |

**Faiblesse** : Clic-clic toutes les 45s — perd 35 PV + malus aléatoire.

---

### Djamila Chung — Anglais · Moyen · 2 sauts
*Spécialité : dégâts de zone, confusion, consignes piège*

| Attaque | Nom | Effet | Cooldown |
|---|---|---|---|
| Normal | Verbes irréguliers | Coup de règle : 7 dégâts à l'ennemi le plus proche | 2s |
| Magie 1 | Wordreference | Lettres projectiles : 18 dégâts à tous les ennemis proches | 8s |
| Magie 2 | Anglaisfacile.com | Écran qui explose : confus 2s sur tous les ennemis | 9s |
| Ultime | Djamila mila eh eh | Onde sonore : tous les ennemis sans attaque 5s | 100% barre |
| 🔮 Spéciale | Retraite | Disparaît 10s (invisible + immunisée), se régénère +4 PV/s | Boule smash |

**Faiblesse** : Consignes au sol — si un ennemi reste dessus 0.3s, Djamila est confuse 3s (consignes réapparaissent après 30s).

---

### Jean-Baptiste Langlois — SVT · Rapide · 4 sauts
*Spécialité : mobilité, contrôle, dégâts en rafale*

| Attaque | Nom | Effet | Cooldown |
|---|---|---|---|
| Normal | Éval surprise | Mauvaise note (-50% dégâts) 3s sur les ennemis proches | 6s |
| Magie 1 | Sortez vos cahiers | 10 dégâts si ennemis proches, sinon endort les ennemis lointains 5s | 9s |
| Magie 2 | Kahoot | Rayon multicolore : 30 dégâts + contrôle perdu 5s sur le plus proche | 18s |
| Ultime | Je vais le dire à José | ×2 dégâts pendant 8s. 10% de chance de rater : les ennemis font ×2 dégâts sur lui 10s | 100% barre |
| 🔮 Spéciale | JBL | Tous les ennemis perdent 4 PV/s pendant 10s (musique forcée) | Boule smash |

**Faiblesse** : Vidéoprojecteur — 40% de chance lors d'une éval surprise de se mettre mauvaise note à soi-même.

---

### Milan Mandic — Maths · Lent · 3 sauts
*Spécialité : mobilité aérienne, livre projectile, dégâts exponentiels*

| Attaque | Nom | Effet | Cooldown |
|---|---|---|---|
| Normal | DST 2h→1h | Contrôles inversés + vitesse ×2 + attaque lente 6s sur les ennemis proches | 6s |
| Magie 1 | Niveau CP | Lance un livre vers l'ennemi le plus proche. Touché : empoisonné 5s (-2 à -4 PV/s). Esquivé : ennemi ralenti 2s, +10 PV et +50% ultime pour Milan | 13s |
| Magie 2 | 🚀 Fusées (toggle) | Active/désactive les fusées : vol libre dans toutes les directions à grande vitesse, mais -8 PV/s | Aucun |
| Ultime | x² | Tire un nombre n entre 1 et 8 (8 très rare) → n² dégâts. Si n < 5 : +n PV pour Milan + malus pour l'ennemi | 15s |
| 🔮 Spéciale | Dérivée | Pendant 8s, tous les ennemis s'infligent leurs propres attaques à eux-mêmes | Boule smash |

---

## 🗺️ Maps

| Map | Description |
|---|---|
| 🏫 Salle de classe | Grande plateforme centrale + 3 plateformes flottantes. Fond : tableau noir étoilé |
| 🏀 Gymnase | Sol parquet + 5 plateformes. Panneaux de basket, cercle central |
| 🌙 Toit de l'école | Plateforme centrale étroite + 3 petites. Ciel nocturne animé, lune, nuages, lumières de ville |

---

## 📦 Objets (spawn toutes les 12–20s)

| Objet | Effet |
|---|---|
| ❤️ Soin | +25 PV |
| ⚡ Ultime | +50% barre d'ultime |
| 🛡 Bouclier | Bouclier 6s (-50% dégâts reçus) |
| 💣 Bombe | -20 PV à tous les joueurs dans un rayon au ramassage |
| 👟 Vitesse | Vitesse ×2 pendant 6s |
| ⭐ Invincible | Immunisé 4s |
| 🔮 Boule Smash | Charge l'attaque spéciale unique du personnage (1 chance sur 8) |

---

## ⚡ Statuts

| Icône | Statut         | Effet                                           |
| -------| ----------------| -------------------------------------------------|
| ?　　 | Confus         | Ne peut pas attaquer                            |
| Zzz　 | Endormi        | Immobile et ne peut pas attaquer                |
| ☠　　 | Empoisonné     | Perd des PV en continu                          |
| 🔥　　| Feu            | Perd des PV en continu (plus rapide que poison) |
| 👁　　| Aveugle        | 50% de chance de rater une attaque              |
| 🐢　　| Ralenti        | Vitesse divisée par 2                           |
| ~　　 | Hypnotisé      | Marche vers Giovanni                            |
| 🧟　　| Zombie         | Marche en s'éloignant de la source              |
| ⚡　　 | Contrôle perdu | Mouvements aléatoires                           |
| ↓　　 | Mauvaise note  | Dégâts divisés par 2                            |
| ×3　　| Dégâts triple  | Dégâts multipliés par 2 (ultime JB)             |
| 🔇　　| Sans attaque   | Ne peut pas attaquer                            |
| 🛡　　 | Bouclier       | Dégâts reçus divisés par 2                      |
| ★　　 | Immunisé       | Aucun dégât reçu                                |
| 👻　　| Invisible      | Quasi-invisible (alpha 0.2)                     |

---

## 🗂️ Structure des fichiers

```
game.html       — tout le jeu (HTML + CSS + JS inline)
sspu_logo.png   — logo affiché dans l'intro
```

## Legal notice

"Super Smash Profs. Ultimate" is an independent project inspired by the platform fighter genre.

This game does not use any official Nintendo assets, characters, or copyrighted material, and has no affiliation with or endorsement from Nintendo.

All trademarks and brand names mentioned are the property of their respective owners. No infringement is intended.
