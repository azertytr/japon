# CLAUDE.md - Instructions de Travail

## 📌 Vue d'ensemble du projet

Ce projet gère un **itinéraire de voyage au Japon (14 jours)** centré autour de Pokémon, Nintendo et parcs à thème. L'objectif est de documenter et maintenir un planning détaillé avec budget, transports, attractions et conseils pratiques.

**Dates** : 6-20 juillet 2026  
**Budget total** : ~920€ (sur place)  
**Destination** : Tokyo → Osaka → Kyoto → Nara → Mont Fuji → Tokyo

## 🗂️ Structure du projet

```
japon/
├── japan_trip_itinerary.html   # Itinéraire complet (HTML formaté)
├── README.md                     # Vue d'ensemble du voyage (créé)
└── CLAUDE.md                     # Ce fichier - Instructions de travail
```

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
1. **Nintendo Museum Kyoto** - Réservation obligatoire immédiatement
   - URL : https://www.nintendo-museum.jp/en/
   - Jour 6 (16 juillet) 10h-12h recommandé
   - Prix : 3000¥

2. **JR Pass décision** - Avant jour 3
   - 7-day JR Pass (~29650¥) vs trajets à l'unité (~25000¥)
   - Coût-bénéfice : Tokyo→Osaka→Kyoto→Nara→Tokyo

3. **Hôtels** - Réserver ASAP (juillet = haute saison)
   - Tokyo (3 nuits)
   - Osaka (3 nuits)
   - Kyoto (4 nuits)
   - Nara (1 nuit)
   - Tokyo retour (2 nuits)

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

### Quand modifier le README
```bash
# Modifier le README pour clarté ou mise à jour
git add README.md
git commit -m "Chore: update planning details"
git push -u origin claude/japan-trip-docs-QT5YS
```

### Quand modifier l'HTML
```bash
# L'HTML est la source complète avec styling
# Modifications synchronisées dans README après
git add japan_trip_itinerary.html
git commit -m "Chore: update HTML with latest details"
git push -u origin claude/japan-trip-docs-QT5YS
```

### Quand ajouter des notes
- Créer une issue GitHub pour suggestion/améliorations
- Ajouter un commentaire dans la section Concerns
- Pull request avec changements proposés

## 🎮 Comment utiliser ce projet avec moi

### Pour clarifications
```
"Combien coûte la navette entre Haneda et Shinjuku ?"
→ Je vérifierai le détail dans japan_trip_itinerary.html
```

### Pour modifications
```
"Ajoute un jour pour Tokyo Disneyland aux jours flexibles"
→ Je mettrai à jour README.md + HTML
```

### Pour nouvelle fonctionnalité
```
"Crée une liste d'achats Pokémon basée sur les Centers visités"
→ Je créerai un fichier shopping-list.md
```

## 📊 Budget détaillé (référence)

| Catégorie | Coût | Notes |
|-----------|------|-------|
| Hébergement | 10 800¥ (~75€) | 13 nuits, 2-3★ |
| Transport | 30 720¥ (~210€) | Shinkansen + locaux |
| Parcs/Attractions | 36 700¥ (~250€) | Nintendo, USJ, temples |
| Shopping Pokémon | 20 000¥ (~135€) | 5 Centers + Akihabara |
| Repas & divers | 37 500¥ (~255€) | 2000-3000¥/jour |
| **TOTAL** | **~135 720¥** | **~920€** |

*Vols internationaux (Paris-Tokyo) non inclus (déjà payés)*

## 🔗 Ressources importantes

- **Nintendo Museum** : https://www.nintendo-museum.jp/en/
- **Réservations hôtels** : Booking.com, Agoda, jalan.net
- **Transport** : Google Maps, Hyperdia, JR East Pass app
- **Billets parcs** : USJ official, Disneyland, Puroland websites

## ⚡ Commandes rapides

Modifier ce fichier : `/claude.md`  
Voir le planning complet : Ouvrir `japan_trip_itinerary.html` dans navigateur  
Aider à organiser : `"Organise une checklist pour les réservations"`

---

**Dernière mise à jour** : 3 mai 2026  
**Prochain review** : Avant 1er juin (confirmations réservations)  
**Départ prévu** : 6 juillet 2026
