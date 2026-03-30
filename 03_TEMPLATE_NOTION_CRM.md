# Structure Notion — CRM & Gestion de Projet
# Crée ces pages dans un workspace Notion gratuit

---

## PAGE 1 : Dashboard Principal

### Tableau de bord — Vue d'ensemble
- Revenu du mois : [à mettre à jour]
- Nombre de clients actifs : [X]
- Projets en cours : [X]
- Proposals envoyées cette semaine : [X]
- Objectif mensuel : 3000$ → 100$/jour

---

## PAGE 2 : Base de données "Clients & Prospects"

### Propriétés de la base de données :
| Colonne | Type | Options |
|---------|------|---------|
| Nom entreprise | Title | — |
| Contact | Text | Nom + email |
| Niche | Select | SaaS, Fintech, DevTools, Analytics, CRM, Autre |
| Statut | Select | 🔵 Prospect, 🟡 Contacté, 🟠 En discussion, 🟢 Client, 🔴 Perdu |
| Source | Select | Upwork, Fiverr, Cold Email, LinkedIn, Referral |
| Date premier contact | Date | — |
| Valeur estimée | Number ($) | — |
| Notes | Text | — |
| Lien proposal | URL | — |

### Vues recommandées :
1. **Pipeline** (vue Kanban par Statut)
2. **Tous les contacts** (vue Table)
3. **Clients actifs** (filtre: Statut = Client)
4. **À relancer** (filtre: Statut = Contacté, Date > 3 jours)

---

## PAGE 3 : Base de données "Projets"

### Propriétés :
| Colonne | Type | Options |
|---------|------|---------|
| Nom du projet | Title | — |
| Client | Relation → Clients | — |
| Type | Select | Blog Post, Email Sequence, Landing Page, Retainer |
| Statut | Select | 📋 Brief, ✍️ En rédaction, 👀 En révision, ✅ Livré, 💰 Payé |
| Prix | Number ($) | — |
| Deadline | Date | — |
| Lien livrable | URL | Google Doc |
| Brief | Text | Résumé du brief client |

### Vues :
1. **En cours** (Kanban par Statut)
2. **Calendrier** (vue Calendar par Deadline)
3. **Revenus** (vue Table, trié par Prix)

---

## PAGE 4 : Template de Brief Client

# Brief — [Nom Client] — [Nom Projet]

## Informations Client
- **Entreprise** :
- **Produit/Service** :
- **Audience cible** :
- **URL du site** :
- **Concurrents principaux** :

## Détails du Projet
- **Type de contenu** : Blog / Email / Landing Page
- **Sujet/Thème** :
- **Mot-clé principal** :
- **Mots-clés secondaires** :
- **Ton souhaité** : Professionnel / Casual / Technique / Conversationnel
- **Longueur** : _____ mots
- **CTA souhaité** :
- **Références / articles similaires aimés** :

## Livraison
- **Deadline** :
- **Format** : Google Doc
- **Révisions incluses** : 1

---

## PAGE 5 : Tracker Prospection Quotidien

### Tableau hebdomadaire :
| Jour | Cold Emails | Proposals Upwork | Fiverr Replies | LinkedIn | Réponses reçues |
|------|------------|------------------|----------------|----------|----------------|
| Lundi | 5 | 5 | 2 | 3 | — |
| Mardi | 5 | 5 | 2 | 3 | — |
| ... | ... | ... | ... | ... | ... |

### Objectifs hebdomadaires :
- Cold emails envoyés : 25+
- Proposals Upwork : 25+
- Interactions LinkedIn : 15+
- Réponses obtenues : 5+
- Appels discovery : 2+

---

## PAGE 6 : Swipe File & Ressources

### Prompts Claude (liens vers fichier prompts)
### Exemples de bons articles SaaS (bookmarks)
### Frameworks de copywriting
- **AIDA** : Attention → Interest → Desire → Action
- **PAS** : Problem → Agitate → Solution
- **BAB** : Before → After → Bridge
- **4 Ps** : Promise → Picture → Proof → Push

### Outils
- Grammarly : https://grammarly.com
- LanguageTool : https://languagetool.org
- Hemingway : https://hemingwayapp.com
- Hunter.io : https://hunter.io
- Ubersuggest : https://neilpatel.com/ubersuggest/
