🎯 SPRINT 0 : Initialisation (Aujourd'hui - 1h)

Concept Agile : Avant de commencer les sprints de développement, on fait un "Sprint 0" pour préparer l'environnement, définir la vision produit et créer le backlog initial.

📋 Cérémonie : Product Vision & Setup
Vision Produit (votre "Product Goal") :
"Classroom Planner v2.0 : Application React/TypeScript permettant 
d'optimiser l'agencement des élèves en classe selon leurs résultats 
et comportements, avec interface moderne et tests automatisés."
Definition of Done (DoD) - Nos critères de qualité :

 Code TypeScript sans erreurs (npm run type-check)
 Tests unitaires >70% coverage
 Composants documentés (JSDoc)
 Responsive (mobile + desktop)
 Accessible (WCAG niveau A minimum)
 Déployé sur Vercel/Netlify

🛠️ Tâches Sprint 0 (À faire MAINTENANT - 1h)
bash# 1. Créer le projet (5 min)
npm create vite@latest classroom-planner-v2 -- --template react-ts
cd classroom-planner-v2
npm install

# 2. Installer les dépendances essentielles (10 min)
npm install zustand react-hook-form zod
npm install -D @testing-library/react @testing-library/jest-dom vitest jsdom
npm install -D @types/node

# 3. Structure de dossiers Agile (5 min)
mkdir -p src/{components,hooks,store,utils,types,__tests__}
mkdir -p docs/{sprints,adrs}

# 4. Configuration Git (5 min)
git init
git add .
git commit -m "chore: Sprint 0 - Project initialization"

# 5. Créer le fichier BACKLOG.md (15 min)
touch docs/BACKLOG.md

# 6. GitHub repo (10 min)
# Créez le repo sur GitHub
git remote add origin https://github.com/michaelg-create/classroom-planner-v2.git
git push -u origin main

# 7. Vérification (5 min)
npm run dev  # Doit afficher l'app sur localhost:5173
📝 Créer votre Product Backlog

Concept Agile : Le Product Backlog est la liste priorisée de toutes les fonctionnalités (User Stories) à développer. On ne détaille que les prochaines, les autres restent high-level.

Créez docs/BACKLOG.md :