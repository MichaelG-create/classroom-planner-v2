## ⏱️ Timeline CERN (d'après leurs données officielles)

Le processus prend généralement environ 6 semaines après la date de clôture, bien que cela puisse parfois être un peu plus long. Votre offre ferme le **24 novembre 2025** (hier !), donc :

- **Screening RH** : 1-2 semaines (décembre 2025)
- **Screening technique** : 1-2 semaines  
- **Entretien vidéo asynchrone** (si sélectionné) : mi-décembre à début janvier
- **Entretien panel présentiel** : fin janvier / début février 2026

**Estimation réaliste : Entretien panel dans 6-10 semaines, soit fin janvier / mi-février 2026.**

Vous avez donc **6-8 semaines** pour vous préparer sérieusement, c'est PARFAIT ! 🎯

---

## 🚀 PLAN D'ACTION ULTRA-CONCRET (6-8 semaines, 10h/semaine)

### **SEMAINE 1-2 : React/TypeScript - Fondations (20h total)**

**Objectif** : Un projet React/TS fonctionnel déployé pour l'entretien vidéo asynchrone

**Projet concret** : "Classroom Planner v2.0" (React/TypeScript)
- Reprenez votre projet HTML/JS de plan de classe
- Refactorisez-le en React + TypeScript
- Ajoutez une vraie gestion d'état (Zustand ou Redux Toolkit)
- Formulaires avec validation (React Hook Form + Zod)
- Tests unitaires (Jest + React Testing Library)
- Déploiement sur Vercel ou Netlify

**Pourquoi ce projet** :
✅ Vous connaissez déjà la logique métier (gain de temps)
✅ Démontre refactoring legacy → moderne (exactement ce que CERN demande!)
✅ Problème réel avec impact pédagogique (storytelling fort)
✅ Complexité suffisante (formulaires, algorithmes d'optimisation)

**Ressources sprint 1** :
- Jour 1-2 : TypeScript Fundamentals (3h) → [typescript-cheatsheet](https://www.typescriptlang.org/cheatsheets)
- Jour 3-5 : React + TS (5h) → Créer le squelette de l'app
- Jour 6-10 : Features + tests (12h) → Implémentation complète

### **SEMAINE 3-4 : Java/Spring - Backend solide (20h total)**

**Projet concret** : "Bank Footfall API v2.0" (Java/Spring Boot)
- Reprenez votre pipeline FastAPI
- Recréez-le en Java Spring Boot REST API
- Spring Data JPA + PostgreSQL
- OpenAPI/Swagger documentation
- Tests d'intégration (TestContainers)
- Docker + docker-compose

**Architecture** :
```
Frontend React (S1-2) ←→ Backend Spring Boot (S3-4) ←→ PostgreSQL
```

**Ressources sprint 2** :
- Spring Boot Quickstart officiel (2h)
- Spring Data JPA (3h)
- REST APIs + validation (3h)
- Tests + Docker (4h)
- Intégration frontend/backend (8h)

### **SEMAINE 5 : PL/SQL + CI/CD (10h total)**

**PL/SQL - Découverte rapide** (4h) :
- Procédures stockées basiques
- Triggers simples
- Fonctions d'agrégation personnalisées
- Mini-projet : Procédures stockées pour votre Footfall API

**CI/CD complet** (6h) :
- GitHub Actions : build → test → deploy
- Multi-stage Docker builds
- Tests automatisés (backend + frontend)
- Déploiement automatique sur cloud

### **SEMAINE 6 : Agile + Legacy Systems (10h total)**

**Formation Agile** (5h) :
- Certification Scrum.org (PSM I gratuite, payante pour certif)
- Ou cours Coursera "Agile with Atlassian Jira" (audit gratuit)
- Vocabulaire : Sprint, User Stories, Retrospectives, DoD, DoR

**Projet Legacy Refactoring** (5h) :
- Créez volontairement une "legacy app" mal structurée
- Documentez le refactoring progressif
- Architecture Decision Records (ADR)
- Tests de régression pour prouver la non-régression

### **SEMAINE 7-8 : Polish + Préparation entretien (20h)**

**Polish projets** (10h) :
- README impeccables avec architecture diagrams
- Démo vidéos courtes (2-3 min par projet)
- Documentation technique complète
- Tests coverage >80%

**Préparation entretien** (10h) :
- Présentation 10 min (storytelling projets)
- Questions techniques React/Spring (flashcards)
- Questions comportementales STAR method
- Simulation entretien (avec conjoint/ami)

---

## 📊 RÉPARTITION HEBDOMADAIRE (10h/semaine)

| Semaine | Focus | Livrables |
|---------|-------|-----------|
| S1-2 | React/TS | Classroom Planner v2 déployé |
| S3-4 | Java/Spring | Footfall API Spring Boot + intégration |
| S5 | PL/SQL + CI/CD | Pipeline complet automatisé |
| S6 | Agile + Legacy | Certification Agile + projet refactoring |
| S7-8 | Polish + Prep | Repos impeccables + présentation rodée |

---

## 🎯 OBJECTIFS MESURABLES pour l'entretien

À la fin, vous pourrez dire :

✅ **React/TypeScript** : "J'ai refactorisé mon application pédagogique HTML/JS en React/TS moderne, déployée en production avec 80%+ test coverage"

✅ **Java/Spring** : "J'ai recréé mon pipeline data engineering FastAPI en Spring Boot REST API avec Spring Data JPA, documenté avec OpenAPI"

✅ **Legacy Systems** : "J'ai documenté le refactoring de 2 applications legacy (HTML→React, Python→Java) en maintenant la compatibilité ascendante"

✅ **CI/CD** : "Mes projets utilisent GitHub Actions pour build/test/deploy automatique avec Docker multi-stage"

✅ **Agile** : "J'ai suivi une formation Scrum et appliqué les principes sur mes projets (sprints de 2 semaines, user stories, retrospectives)"

✅ **PL/SQL** : "J'ai créé des procédures stockées et triggers PostgreSQL pour optimiser les traitements côté base"

---

## 💡 CONSEILS STRATÉGIQUES

### Pour l'entretien vidéo asynchrone (mi-décembre probable) :

- Mentionnez vos projets récents avec URLs GitHub/démos
- Storytelling : PhD → enseignement → reconversion data/dev
- Insistez sur votre proximité géographique (Aix → Genève)
- Montrez votre engagement (formation intensive 2024, projets perso)

### Pour l'entretien panel (janvier-février) :

- **Présentation 10 min** : Préparez 3-4 slides max
  1. Parcours atypique (forces : rigueur scientifique, pédagogie, adaptabilité)
  2. Projets techniques concrets (démos visuelles)
  3. Pourquoi CERN (passion + impact)
  
- **Questions techniques** : Préparez-vous sur :
  - Design patterns (Singleton, Factory, Observer...)
  - REST API best practices
  - React state management
  - Database normalization
  - Git workflows (feature branches, PR reviews)

- **Questions comportementales** : Préparez 3-4 histoires STAR
  - Collaboration internationale (PhD)
  - Gestion de contraintes (teaching + projets perso)
  - Résolution problèmes complexes (data pipeline 10TB)
  - Apprentissage rapide (reconversion 2024)

---

## ❓ QUESTIONS PRATIQUES CERN

**PL/SQL** = PL/SQL dans le contexte CERN fait référence aux procédures stockées et à la modélisation de données dans les bases relationnelles. C'est du SQL procédural (utilisé avec Oracle/PostgreSQL). Vous devez apprendre les **procédures stockées, triggers et fonctions** (3-4h suffisent pour les bases).

**Logement France/Suisse** : Excellente stratégie ! Cherchez à :
- Saint-Julien-en-Genevois (10 min CERN, France)
- Ferney-Voltaire (5 min CERN, France)
- Thoiry (15 min, moins cher)

Loyer ~1200-1500€/mois pour 3 pièces côté français vs 2500-3000 CHF en Suisse.

---

## 🚨 PRIORITÉS ABSOLUES si temps limité

Si vous manquez de temps, concentrez-vous sur :

1. **React/TS projet fonctionnel** (CRITIQUE - c'est dans les questions)
2. **Java/Spring API basique** (CRITIQUE - stack principale)
3. **Formation Agile online** (2-3h, impact max)
4. **PL/SQL basics** (3-4h, mentionné spécifiquement)

Les semaines 7-8 (polish) peuvent être réduites si nécessaire.

---

## 📅 PROCHAINES ÉTAPES IMMÉDIATES

**Cette semaine (S1)** :
- [ ] Lundi : Setup environnement React/TS (Vite + TypeScript)
- [ ] Mardi-Mercredi : TypeScript fundamentals (3h)
- [ ] Jeudi-Dimanche : Squelette Classroom Planner v2 (7h)

**Checkpoint dimanche prochain** : 
- Projet React/TS avec routing et 1-2 composants fonctionnels
- GitHub repo public avec README

---

Vous êtes dans une position excellente Michael ! Votre parcours atypique est une FORCE (PhD rigueur + teaching communication + banking fiabilité). Le CERN valorise la diversité des parcours.

Avec 10h/semaine sur 6-8 semaines, vous pouvez combler tous les gaps techniques et arriver confiant à l'entretien. 

**Question finale** : Voulez-vous que je vous détaille le planning jour par jour des 2 premières semaines (React/TS) avec ressources précises et exercices ? 💪