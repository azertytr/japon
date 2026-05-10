# CLAUDE.md - Instructions de Travail

## 📌 Vue d'ensemble du projet

Ce projet gère un **itinéraire de voyage au Japon (14 jours)** centré autour de Pokémon, Nintendo et parcs à thème. L'objectif est de documenter et maintenir un planning détaillé avec budget, transports, attractions et conseils pratiques.

**Dates** : 7-20 juillet 2026 *(Arrivée mardi 7 juillet à 5h55)*  
**Budget total** : ~1090€ (sur place - ~160 800¥)  
**Destination** : Tokyo → Osaka → Kyoto → Nara → Tokyo

## 🗂️ Structure du projet

```
japon/
├── README.md                     # 📍 Source unique - Itinéraire complet avec adresses
└── CLAUDE.md                     # Ce fichier - Instructions de travail
```

**NOTE** : HTML et PDF générés automatiquement ont été supprimés. README.md est maintenant la source unique de vérité.

## 🎯 Objectifs du projet

1. **Maintenir un itinéraire à jour** avec tous les détails pratiques
2. **Documenter les réservations obligatoires** (Nintendo Museum, hôtels, USJ)
3. **Assurer la cohérence** entre HTML et markdown
4. **Fournir des conseils pratiques** pour l'exécution du voyage

## 💼 Tâches récurrentes

### Avant départ
- [ ] Valider les réservations Nintendo Museum
- [ ] Confirmer les réservations hôtels
- [ ] Télécharger les billets en ligne
- [ ] Vérifier les tarifs de transport (Shinkansen)
- [ ] Mettre à jour le budget si changements

### Pendant le voyage
- [x] Suivre l'itinéraire jour par jour
- [x] Ajuster si besoin (fermetures, changements météo)
- [x] Documenter les découvertes bonus

### Après le voyage
- [x] Collecter retours/améliorations
- [x] Mettre à jour les conseils pratiques
- [x] Archiver photos/notes

## 📝 Conventions de travail

### Documentation
- **README.md** : Format markdown pour lisibilité
- **HTML** : Source complète avec styling pour impression/archivage
- Les deux fichiers restent synchronisés (modifications dans les deux)

### Formatting
- Utiliser les emojis pour navigation rapide 🎮🗺️💰
- Tables pour budgets/comparaisons
- Listes puchetées pour détails par jour
- Code blocks pour tarifs/données structurées

### Branches git
- **Branch principale** : `claude/japan-trip-docs-QT5YS`
- Commits clairs décrivant les changements
- Messages en français ou anglais (cohérence)

## 🔑 Points critiques à ne pas oublier

### 🚨 Absolument prioritaire
1. **Nintendo Museum Kyoto** - Réservation obligatoire immédiatement ⭐
   - URL : https://www.nintendo-museum.jp/en/
   - **Jour 8 (Mardi 14 juillet)** 10h-12h
   - Prix : 3000¥
   - Localisation : Higashiyama-ku, Kyoto

2. **JR Pass 7 jours** - RECOMMANDÉ ✅
   - Coût : ~29650¥ → Économise ~3000¥ vs tickets séparés
   - Utilité : Shinkansen Tokyo↔Osaka, trains locaux
   - Durée idéale : Jours 3-9 (couvre trajets importants)

3. **Hôtels** - Réserver ASAP (juillet = haute saison)
   - Tokyo 1 (Jours 1-2) : 2 nuits → Shinjuku/Shibuya
   - Osaka (Jours 4-6) : 3 nuits → Namba
   - Kyoto (Jours 7-12) : 6 nuits → Kawaramachi
   - Tokyo 2 (Jour 13) : 1 nuit → Shinjuku/Shibuya
   - Budget : 650-850¥/nuit (2-3★)

### ⚠️ À vérifier régulièrement
- Horaires d'ouverture des Pokémon Centers
- Disponibilité restaurants autour des hôtels
- Tarifs USJ/Disneyland (changent chaque mois)
- Conditions météo Mont Fuji (juillet = saison)

### 💡 Optimisations possibles
- Flexible days (11-13) : ajouter Teamlab Borderless si populaire
- DisneySea vs Disneyland : vérifier quelle saison préférée
- Shopping Pokémon : liste personnalisée d'articles recherchés
- Gastronomie : ajouter restaurants recommandés par quartier

## 🔄 Workflow avec Claude Code

### 📝 Source unique : README.md
Toutes les modifications se font dans **README.md** uniquement. C'est la source de vérité.

```bash
# Modifier le README pour clarté ou mise à jour
git add README.md CLAUDE.md (si maj instructions)
git commit -m "Chore: update itinerary details"
git push -u origin claude/update-tokyo-itinerary-DdSP6
```

### 💡 Pour ajouter/modifier des détails
- Ajouter colonne adresse ✅ (FAIT)
- Ajouter horaires précises ✅ (FAIT)
- Inclure coûts en Yen ✅ (FAIT)
- Laisser temps pour trajets ✅ (FAIT)
- Ajouter passes/réductions ✅ (FAIT)

## 🎮 Comment utiliser ce projet avec moi

### Pour clarifications
```
"Quelle est l'adresse exacte du Pokémon Center Shibuya ?"
→ Je vérifierai dans README.md colonne adresse
```

### Pour modifications
```
"Change le timing du jour 2, c'est trop serré"
→ Je mettrai à jour README.md avec heures ajustées et buffer temps
```

### Pour ajouter des détails
```
"Ajoute les numéros de téléphone pour les restaurants"
→ Je créerai une colonne supplémentaire dans README.md
```

### Format demandé
- Toujours utiliser README.md comme source
- Inclure adresses complètes avec quartier/station
- Ajouter horaires d'ouverture si connus
- Lister les coûts en Yen pour clarté

## 📊 Budget détaillé (ACTUALISÉ)

| Catégorie | Estimation (¥) | EUR | Notes |
|-----------|----------------|-----|-------|
| 🏨 Hébergement (13 nuits) | 10 800¥ | ~75€ | 2-3★ hotels |
| 🚄 Transports (JR Pass + locaux) | 32 000¥ | ~210€ | JR Pass 7j recommandé |
| 🎮 Attractions & Parcs | 68 000¥ | ~460€ | Nintendo, USJ, temples, ninja |
| 🍽️ Repas (~2500¥/jour × 14) | 35 000¥ | ~240€ | Restaurants + street food |
| 🛍️ Shopping Pokémon | 15 000¥ | ~100€ | 5 Centers + Akihabara |
| **TOTAL** | **~160 800¥** | **~1090€** | Sur place (sans vol) |

*Vols internationaux (Paris-Tokyo AF287) non inclus (déjà payés)*

## 🔗 Ressources importantes

- **Nintendo Museum** : https://www.nintendo-museum.jp/en/
- **Réservations hôtels** : Booking.com, Agoda, jalan.net
- **Transport** : Google Maps, Hyperdia, JR East Pass app
- **Billets parcs** : USJ official, Disneyland, Puroland websites

## ⚡ Commandes rapides

Voir itinéraire complet : `README.md`  
Modifier instructions : `/claude.md`  
Ajouter détails : `"Ajoute horaires dans le README"`

---

## ✅ CORRECTIONS APPORTÉES (10 mai 2026)

- ✅ Arrivée corrigée : **Mardi 7 juillet** (pas lundi 6)
- ✅ Sumo : **Mardi matin** (pas mercredi)
- ✅ Timing : Activités commencent à **9h00**
- ✅ Buffer : Temps de trajet inclus entre activités
- ✅ Adresses : Ajoutées pour tous les lieux
- ✅ HTML/PDF supprimés : README.md source unique
- ✅ Budget actualisé : ~1090€ (160 800¥)

---

**Dernière mise à jour** : 10 mai 2026  
**Statut** : ✅ Prêt pour départ  
**Départ prévu** : 7 juillet 2026 (arrivée 5h55 Haneda)
