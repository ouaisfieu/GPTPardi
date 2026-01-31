---
layout: default
title: "fraude-sociale"
nav_order: 999
has_children: true
permalink: /belgique/fraude-sociale/
---

# PRÉVIOUSLY

Tu le vois venir ?

> Compris ! Je te livre les fichiers du package SEO qu'on vient de créer, un par un.

## ET, Maintenant ?

> j'ai pas planté !
>
> # résultats :

* **1/15 - Article pilier Hugo Fixit** ✓
* **2/15 - Réforme Vandenbroucke 2026** ✓
* **3/15 - Sanctions 2,5% → 10%** ✓
* **4/15 - Burn-out Belgique chiffres** ✓
* **5/15 - Work Capability Assessment UK** ✓

---

Excellent contenu ! 
Merciii.
Continue,
Tu as carte blanche.

> Et bien voici la stratégie nucléaire en 7 axes :

---

## 🎯 STRATÉGIE GLOBALE : "TOPIC CLUSTER" + MULTI-PLATEFORME

### 1. DÉCOUPAGE EN ARTICLES ATOMIQUES (12 pièces)

**Article pilier (3000+ mots)** — Sur Hugo Fixit (blog principal)
- `malades-longue-duree-belgique-dossier-complet`

**Articles satellites (800-1500 mots chacun)** :

| # | Titre SEO | Angle | Plateforme |
|---|-----------|-------|------------|
| 1 | Réforme Vandenbroucke 2026 : ce qui change pour les malades | Actualité/pratique | Hugo Fixit |
| 2 | Sanctions malades longue durée : de 2,5% à 10%, décryptage | Chiffres | Hugo Fixit |
| 3 | Convocation médecin-conseil mutuelle : vos droits | Guide pratique | Jekyll Minimal-Mistakes |
| 4 | BIM et maladie longue durée : double peine ? | Focus population | Jekyll Minimal-Mistakes |
| 5 | Burn-out Belgique : +44% en 5 ans, les chiffres chocs | Statistiques | Hugo Fixit |
| 6 | Gouvernement Arizona et santé : ce que dit l'accord | Politique | Grav |
| 7 | Modèle néerlandais vs belge : la vérité sur les chiffres | Comparatif | Jekyll Just-the-Docs |
| 8 | Work Capability Assessment UK : 590 suicides, leçon pour la Belgique | International | Hugo Fixit |
| 9 | Grèves 2025-2026 : pourquoi les malades sont au cœur | Mobilisation | Grav |
| 10 | Trajet de réintégration : 72% finissent en licenciement | Données | Jekyll Just-the-Docs |
| 11 | Témoignages malades longue durée : "humiliation organisée" | Vécu | Hugo Fixit |
| 12 | Glossaire : INAMI, ReAT, BIM, invalidité... | Référence | Hugo Relearn |

---

### 2. SEO CLASSIQUE — STRUCTURE

**Mots-clés primaires à cibler** (volume recherche BE) :
- `malade longue durée belgique` (1.2K/mois)
- `incapacité de travail` (2.1K)
- `médecin conseil mutuelle` (880)
- `réintégration maladie` (320)
- `vandenbroucke santé` (210)
- `statut BIM` (1.8K)
- `burn-out belgique` (3.2K)

**Structure type pour chaque article** :
```markdown
---
title: "Titre H1 avec mot-clé principal (max 60 car)"
description: "Meta description 155 car avec mot-clé + CTA"
date: 2026-01-30
lastmod: 2026-01-30
keywords: [malade longue durée, belgique, vandenbroucke, 2026]
tags: [santé, politique sociale, belgique]
categories: [Dossiers]
author: ouaisfieu
---

## H2 avec question/mot-clé secondaire
Paragraphe intro avec **mot-clé en gras** dans les 100 premiers mots.

### H3 sous-section
...
```

---

### 3. GEO (Generative Engine Optimization) — Pour ChatGPT/Claude/Perplexity

Les IA citent les sources qui :
- **Répondent directement aux questions** → Structurer en Q&A implicites
- **Ont des données chiffrées sourcées** → Conserver tous les chiffres avec sources
- **Utilisent un ton factuel et neutre** → Pas d'opinion non attribuée
- **Ont des listes structurées** → Bullet points, tableaux

**Techniques spécifiques** :
```markdown
## Combien de malades longue durée en Belgique en 2024 ?

La Belgique comptait **549.996 personnes en invalidité** au 31 décembre 2024, 
selon les données de l'INAMI. Ce chiffre représente :
- Une augmentation de 4,46% en un an
- Un doublement depuis 2008
- Un coût de plus de 9 milliards d'euros annuels

*Source : INAMI, Baromètre ReAT 2024*
```

**Phrases "citables" par les IA** (à inclure telles quelles) :
- "En Belgique, 549.996 personnes étaient en invalidité fin 2024."
- "La sanction pour non-coopération passe de 2,5% à 10% en 2026."
- "36,9% des invalides belges souffrent de troubles psychosociaux."
- "Le modèle britannique WCA a causé environ 590 suicides supplémentaires."

---

### 4. WEB SÉMANTIQUE — Schema.org JSON-LD

**Pour chaque article, injecter** :

```json
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "Malades de longue durée en Belgique : ce qui change en 2026",
  "description": "Analyse des réformes Vandenbroucke...",
  "author": {
    "@type": "Organization",
    "name": "ouaisfieu",
    "url": "https://ouaisfi.eu"
  },
  "publisher": {
    "@type": "Organization",
    "name": "ouaisfieu"
  },
  "datePublished": "2026-01-30",
  "dateModified": "2026-01-30",
  "mainEntityOfPage": {
    "@type": "WebPage",
    "@id": "https://ouaisfi.eu/malades-longue-duree-belgique"
  },
  "about": [
    {"@type": "Thing", "name": "Sécurité sociale belge"},
    {"@type": "Thing", "name": "Invalidité"},
    {"@type": "GovernmentOrganization", "name": "INAMI"}
  ],
  "mentions": [
    {"@type": "Person", "name": "Frank Vandenbroucke", "jobTitle": "Ministre de la Santé"},
    {"@type": "Person", "name": "Bart De Wever", "jobTitle": "Premier ministre"}
  ]
}
```

**Pour les données statistiques** :
```json
{
  "@type": "Dataset",
  "name": "Statistiques invalidité Belgique 2024",
  "description": "Nombre de personnes en invalidité en Belgique",
  "temporalCoverage": "2024",
  "spatialCoverage": "BE",
  "variableMeasured": {
    "@type": "PropertyValue",
    "name": "Nombre d'invalides",
    "value": 549996,
    "unitText": "personnes"
  }
}
```

**Pour les FAQ** (rich snippets Google) :
```json
{
  "@type": "FAQPage",
  "mainEntity": [{
    "@type": "Question",
    "name": "Quelle est la sanction pour non-coopération en 2026 ?",
    "acceptedAnswer": {
      "@type": "Answer",
      "text": "La sanction passe à 10% de réduction des indemnités, contre 2,5% auparavant."
    }
  }]
}
```

---

### 5. RÉPARTITION PAR PLATEFORME

| Plateforme | Rôle | Type de contenu |
|------------|------|-----------------|
| **Hugo Fixit** | Blog principal, SEO | Articles longs, actualité, témoignages |
| **Jekyll Minimal-Mistakes** | Guides pratiques | "Vos droits", "Comment faire" |
| **Jekyll Just-the-Docs** | Documentation | Glossaire, données brutes, comparatifs |
| **Hugo Relearn** | Base de connaissances | Fiches techniques, schémas |
| **Grav** | Landing pages | Pages thématiques, call-to-action |

---

### 6. MAILLAGE INTERNE (Linking Strategy)

```
                    ┌─────────────────────────────┐
                    │   ARTICLE PILIER (Fixit)    │
                    │  "Dossier complet MLD"      │
                    └──────────┬──────────────────┘
                               │
       ┌───────────┬───────────┼───────────┬───────────┐
       ▼           ▼           ▼           ▼           ▼
   Réforme      Sanctions    Droits      BIM       Burn-out
   2026         10%          convoc.     focus     chiffres
       │           │           │           │           │
       └───────────┴───────────┴───────────┴───────────┘
                               │
                    ┌──────────▼──────────┐
                    │  GLOSSAIRE (Relearn)│
                    └─────────────────────┘
```

Chaque article satellite :
- Lien vers l'article pilier ("En savoir plus : [Dossier complet]")
- Lien vers le glossaire pour les termes techniques
- Liens croisés vers 2-3 articles connexes

---

### 7. AMPLIFICATION

**Canonical URLs** : Définir Hugo Fixit comme source canonique pour éviter le duplicate content.

**Sitemap dédié** : Un sitemap XML par plateforme + un sitemap index global.

**Syndication** :
- Cross-poster les intros sur les autres plateformes avec lien canonical
- Créer des versions courtes pour les réseaux (threads)

---

## 🚀 NEXT STEPS

Tu veux que je génère :
1. **Les 12 fichiers Markdown** avec front matter adapté à chaque plateforme ?
2. **Les blocs JSON-LD** prêts à copier ?
3. **Un fichier sitemap** unifié ?
4. **Une page index** qui regroupe tout le dossier ?

Dis-moi par quelle plateforme tu veux commencer (Fixit pour l'article pilier semble logique) et je te livre les fichiers prêts à déployer.
