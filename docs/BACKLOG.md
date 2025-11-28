# Product Backlog - Classroom Planner v2.0

## 🎯 Product Goal
Application React/TS pour optimiser l'agencement des élèves en classe.

## 📊 Backlog Items (Priorisés)

### SPRINT 1 (Semaine 1-2) - MVP Core Features

#### US-001 : Saisie des élèves [5 Story Points]
**En tant qu'** enseignant  
**Je veux** saisir la liste de mes élèves avec leurs prénoms  
**Afin de** créer la base de données de ma classe

**Critères d'acceptation :**
- [ ] Formulaire avec champ "Prénom"
- [ ] Bouton "Ajouter élève"
- [ ] Liste des élèves s'affiche en temps réel
- [ ] Validation : pas de prénom vide
- [ ] Possibilité de supprimer un élève

**DoD :**
- [ ] Tests unitaires formulaire
- [ ] TypeScript strict
- [ ] Responsive mobile

---

#### US-002 : Stockage local des données [3 Story Points]
**En tant qu'** enseignant  
**Je veux** que mes données soient sauvegardées automatiquement  
**Afin de** ne pas perdre mon travail entre les sessions

**Critères d'acceptation :**
- [ ] Données persistées dans Zustand
- [ ] Sérialisation/désérialisation JSON
- [ ] Restauration automatique au chargement

**DoD :**
- [ ] Tests du store Zustand
- [ ] Gestion des erreurs

---

#### US-003 : Attribution des notes [5 Story Points]
**En tant qu'** enseignant  
**Je veux** attribuer des notes comportementales à chaque élève  
**Afin de** prendre en compte leur comportement dans le placement

**Critères d'acceptation :**
- [ ] Échelle de 1 à 5 (ou A à E)
- [ ] Interface de notation claire
- [ ] Modification possible des notes
- [ ] Validation des entrées

**DoD :**
- [ ] Tests validation notes
- [ ] Accessible (clavier navigation)

---

#### US-004 : Génération du plan de classe [8 Story Points]
**En tant qu'** enseignant  
**Je veux** générer automatiquement un plan de classe optimisé  
**Afin de** placer les élèves de manière équilibrée

**Critères d'acceptation :**
- [ ] Algorithme de placement (grille 6x5 par défaut)
- [ ] Répartition équilibrée des notes
- [ ] Affichage visuel du plan (grille)
- [ ] Possibilité de régénérer

**DoD :**
- [ ] Tests algorithme (plusieurs scénarios)
- [ ] Performance <100ms pour 30 élèves

---

### SPRINT 2 (Semaine 3-4) - Polish & Tests

#### US-005 : Drag & Drop manuel [5 Story Points]
#### US-006 : Export PDF/Print [3 Story Points]
#### US-007 : Multi-classes [8 Story Points]
#### US-008 : Thème sombre [2 Story Points]

---

### BACKLOG (Non planifié)
- US-009 : Historique des plans
- US-010 : Import depuis CSV
- US-011 : Groupes de travail


---

## 🏃 SPRINT 1 : Core Features (Semaines 1-2, 20h)

> **Concept Agile** : Un **Sprint** est une itération fixe (1-4 semaines) où on développe un incrément de produit potentiellement livrable. Chez CERN, ils font probablement des sprints de 2 semaines.

### 📅 Sprint Planning (Aujourd'hui - 30 min)

> **Cérémonie Agile** : Le **Sprint Planning** lance le sprint. L'équipe sélectionne les User Stories à développer et les découpe en tâches techniques.

**Sprint Goal** : 
```
"À la fin du Sprint 1, l'utilisateur peut saisir des élèves, 
leur attribuer des notes, et générer un plan de classe optimisé."
```

**Capacité** : 20h (10h/semaine × 2 semaines)  
**Vélocité estimée** : 21 Story Points (US-001 à US-004)

#### 🔨 Découpage en tâches techniques

**US-001 : Saisie des élèves [5 SP] → 5h**
- [ ] T1.1 : Créer type `Student` (0.5h)
- [ ] T1.2 : Créer composant `StudentForm.tsx` (1h)
- [ ] T1.3 : Hook `useStudentForm` avec react-hook-form + zod (1.5h)
- [ ] T1.4 : Composant `StudentList.tsx` (1h)
- [ ] T1.5 : Tests unitaires (1h)

**US-002 : Stockage local [3 SP] → 3h**
- [ ] T2.1 : Store Zustand `useStudentStore` (1h)
- [ ] T2.2 : Persist middleware (1h)
- [ ] T2.3 : Tests store (1h)

**US-003 : Attribution notes [5 SP] → 5h**
- [ ] T3.1 : Ajouter champ `grade` au type Student (0.5h)
- [ ] T3.2 : Composant `GradeSelector.tsx` (1.5h)
- [ ] T3.3 : Intégration dans StudentForm (1h)
- [ ] T3.4 : Validation Zod (1h)
- [ ] T3.5 : Tests (1h)

**US-004 : Génération plan [8 SP] → 7h**
- [ ] T4.1 : Algorithme de placement `generateSeatingPlan()` (2h)
- [ ] T4.2 : Type `SeatingPlan` et `Seat` (0.5h)
- [ ] T4.3 : Composant `ClassroomGrid.tsx` (2h)
- [ ] T4.4 : Store `useSeatingStore` (1h)
- [ ] T4.5 : Tests algorithme (1.5h)

**Total Sprint 1** : 20h ✅

---

## 📆 PLANNING DÉTAILLÉ - Semaine 1 (10h)

### 🗓️ Lundi 2 décembre (2h) - TypeScript Foundations

**Daily Standup** (5 min - faites-le même seul !) :
> **Concept Agile** : Chaque jour, l'équipe fait un **Daily Standup** de 15 min max pour synchroniser. 

> 3 questions : 

- Qu'ai-je fait hier ? 
- Que vais-je faire aujourd'hui ?
- Ai-je des blockers ?

```
Hier : Sprint 0 - Setup projet ✅
Aujourd'hui : TypeScript fundamentals + US-001 T1.1
Blockers : Aucun



- Préparé BDD backlog + prep sous BDD pour tasks (en cours 28/11/25 15:38)