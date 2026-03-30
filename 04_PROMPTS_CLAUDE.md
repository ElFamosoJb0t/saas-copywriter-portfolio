# Prompts Claude — Prêts à l'emploi pour chaque type de contenu

---

## PROMPT 1 — Article de Blog SEO SaaS

```
Tu es un copywriter SaaS B2B expert en SEO. Rédige un article de blog optimisé pour le mot-clé "[MOT-CLÉ]".

Contexte :
- Entreprise : [NOM] — [description courte du produit SaaS]
- Audience : [personas — ex: product managers, CTOs, marketers]
- Objectif de l'article : [générer du trafic organique / éduquer / convertir en trial]
- Ton : professionnel mais accessible, pas corporate. Comme un collègue expert qui explique.

Structure demandée :
1. Titre H1 accrocheur avec le mot-clé (max 60 caractères)
2. Introduction hook (2-3 paragraphes, captiver en 5 secondes, inclure le mot-clé dans les 100 premiers mots)
3. 4-6 sections H2 avec contenu substantiel
4. Données chiffrées, exemples concrets, tableaux comparatifs si pertinent
5. Conclusion avec CTA naturel vers le produit
6. Meta title (max 60 car.) + meta description (max 155 car.)

Contraintes :
- Longueur : [1200 / 2000 / 3000] mots
- Intègre les mots-clés secondaires : [mot1, mot2, mot3]
- Pas de fluff, chaque paragraphe doit apporter de la valeur
- Utilise des listes à puces et tableaux pour la lisibilité
- Écris comme si le lecteur avait 30 secondes d'attention

Références concurrentes à surpasser : [URL 1, URL 2]
```

---

## PROMPT 2 — Séquence Email SaaS

```
Tu es un email copywriter spécialisé SaaS B2B. Crée une séquence de [5/7] emails pour [OBJECTIF].

Contexte :
- Produit : [NOM] — [ce que fait le produit]
- Type de séquence : [onboarding / nurture / réactivation / launch / upsell]
- Audience : [qui reçoit ces emails — nouveaux users, trial expiré, etc.]
- Milestones d'activation : [les 3-5 actions clés que l'utilisateur doit faire]
- Ton : [conversationnel et direct / professionnel mais humain]

Pour chaque email, fournis :
1. Trigger (comportemental ou temporel)
2. 2 objets A/B (max 50 caractères, pas de spam words)
3. Corps de l'email (150-250 mots max — court et actionnable)
4. 1 CTA principal clair
5. P.S. optionnel si pertinent

Contraintes :
- Chaque email a UN seul objectif et UN seul CTA
- Utilise le prénom du destinataire
- Pas de langage corporate ("we are pleased to inform you...")
- Écris comme un humain, pas comme un robot marketing
- Inclus du social proof ou des données quand possible
- Le dernier email peut inclure une offre/urgence

À la fin, ajoute un tableau récapitulatif : Email # | Trigger | Objectif | CTA | KPI cible
```

---

## PROMPT 3 — Landing Page SaaS

```
Tu es un conversion copywriter expert en landing pages SaaS B2B. Rédige le copy complet pour une landing page.

Contexte :
- Produit : [NOM] — [description]
- Objectif de la page : [free trial signup / demo booking / lead magnet download]
- Audience : [qui arrive sur cette page et d'où — SEO, ads, referral]
- Proposition de valeur principale : [le bénéfice #1]
- Concurrents principaux : [3 concurrents que le visiteur compare]
- Objections courantes : [prix, complexité, déjà un outil, etc.]

Structure de la page :
1. HERO : Headline (max 10 mots) + subheadline (1-2 phrases) + CTA + preuve sociale rapide
2. PROBLÈME : 3-4 pain points de l'audience (avec empathie, pas condescendant)
3. SOLUTION : présentation du produit comme la réponse au problème
4. FEATURES : 3-4 features clés avec bénéfices (pas juste des descriptions techniques)
5. SOCIAL PROOF : format pour 2-3 témoignages + logos clients
6. COMPARAISON : tableau vs concurrents (honnête mais avantageux)
7. FAQ : 4-5 questions qui lèvent les objections
8. CTA FINAL : dernière accroche + bouton

Framework : utilise [AIDA / PAS / Before-After-Bridge] comme structure de persuasion.

Contraintes :
- Chaque section doit pouvoir convaincre seule (les gens scannent, ne lisent pas)
- Headlines > body copy (les titres font 80% du travail)
- CTA visible minimum 3 fois sur la page
- Spécifique > générique ("save 5 hours/week" > "save time")
```

---

## PROMPT 4 — Recherche & Analyse Concurrentielle (Pré-rédaction)

```
Aide-moi à préparer la recherche pour un article de blog SaaS.

Sujet : [SUJET]
Mot-clé cible : [MOT-CLÉ]
Niche : [CRM / Analytics / DevTools / Cybersécurité / etc.]

Fais cette recherche :
1. Quel est l'intent de recherche derrière ce mot-clé ? (informationnel, transactionnel, comparatif)
2. Quels sous-sujets / questions les utilisateurs se posent sur ce thème ?
3. Quelle structure d'article serait optimale pour ranker sur ce mot-clé ?
4. Quels types de données/stats/exemples rendraient cet article plus crédible ?
5. Quels angles les concurrents ne couvrent probablement PAS ? (trouver le gap)
6. Suggest 5 titres H1 optimisés SEO pour ce mot-clé
7. Suggest 5 meta descriptions

Format ta réponse en sections claires avec des bullet points.
```

---

## PROMPT 5 — Réécriture / Amélioration de contenu existant

```
Voici un texte écrit pour un client SaaS. Améliore-le selon ces critères :

Texte original :
"""
[COLLER LE TEXTE]
"""

Critères d'amélioration :
1. Rends les phrases plus concises (supprime le fluff)
2. Renforce les hooks et transitions
3. Ajoute des données chiffrées ou exemples concrets là où c'est vague
4. Améliore les CTA pour qu'ils soient plus spécifiques et actionnables
5. Vérifie la cohérence du ton (doit être : [professionnel mais accessible])
6. Optimise pour le mot-clé : [MOT-CLÉ] si applicable

Fournis :
- La version améliorée complète
- Une liste des changements majeurs effectués et pourquoi
```

---

## PROMPT 6 — Proposal Upwork / Cold Email personnalisé

```
Rédige une proposal Upwork (ou cold email) pour ce job/prospect :

Description du job/prospect :
"""
[COLLER LA DESCRIPTION DU JOB UPWORK OU LE CONTEXTE DU PROSPECT]
"""

Mon profil :
- Copywriter SaaS B2B spécialisé en [blog SEO / emails / landing pages]
- Background technique (développement, data science, ML)
- Je livre en 3-5 jours, avec une révision incluse

Contraintes pour la proposal :
- Max 150 mots (les clients Upwork ne lisent pas les pavés)
- Commence par une phrase qui montre que tu as LU le job post (pas générique)
- Mentionne 1 résultat concret ou échantillon pertinent
- Termine par une question ouverte pour engager la conversation
- Ton : confiant mais pas arrogant, professionnel mais humain
- PAS de "Dear Sir/Madam" ou "I am a highly experienced..."
```
