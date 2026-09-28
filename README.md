# 🎓 Guide de Survie Étudiant & International

Projet web open-source centralisant les ressources, démarches administratives et bons plans indispensables pour réussir son installation et sa vie étudiante en France.

---

## 🎯 Ambitions du projet

Ce projet est né du constat que l'accès aux informations pratiques pour les étudiants (et plus particulièrement les étudiants internationaux) est souvent éparpillé entre plusieurs plateformes institutionnelles.

**Les objectifs principaux :**
- **Centraliser l'information :** Regrouper en un seul endroit les démarches clés (ANEF/VLS-TS, Visale, CPAM/Ameli, CAF).
- **Favoriser l'égalité des chances :** Rendre les bons plans (alimentation à bas coût, transports, réductions culturelles) faciles à trouver pour réduire la précarité étudiante.
- **Offrir une interface simple et accessible :** Proposer une navigation fluide et claire, lisible sur smartphone comme sur ordinateur.
- **Accompagner l'intégration :** Proposer des repères clairs pour faciliter la transition administrative et culturelle des nouveaux arrivants.

---

## 🚀 Première version du code (v1.0)

Cette première version propose un site statique léger et responsive, structuré en cartes thématiques.

### 📄 `index.html`
```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guide de Survie Étudiant & International</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>🎓 Guide de Survie Étudiant</h1>
        <p>Bons plans, démarches et astuces pour réussir son installation en France.</p>
    </header>

    <nav>
        <a href="#demarches">🏛️ Démarches</a>
        <a href="#bons-plans">💶 Bons Plans</a>
        <a href="#sante">🏥 Santé & Aides</a>
    </nav>

    <main>
        <section id="demarches">
            <h2>🏛️ Démarches Essentielles</h2>
            <div class="grid">
                <article class="card">
                    <span class="tag international">Étrangers</span>
                    <h3>Validation VLS-TS (Titre de séjour)</h3>
                    <p>Validation obligatoire dans les 3 mois suivant l'arrivée en France sur la plateforme ANEF.</p>
                    <a href="[https://administration-etrangers-en-france.interieur.gouv.fr](https://administration-etrangers-en-france.interieur.gouv.fr)" target="_blank" class="btn">Site ANEF</a>
                </article>

                <article class="card">
                    <span class="tag tous">Tous étudiants</span>
                    <h3>Garantie Visale</h3>
                    <p>Obtenir un garant gratuitement pour la location d'un logement.</p>
                    <a href="[https://www.visale.fr](https://www.visale.fr)" target="_blank" class="btn">Demander Visale</a>
                </article>
            </div>
        </section>

        <section id="bons-plans">
            <h2>💶 Vie Chère & Bons Plans</h2>
            <div class="grid">
                <article class="card">
                    <span class="tag tous">Tous étudiants</span>
                    <h3>Repas CROUS</h3>
                    <p>Accès aux Restos U pour manger équilibré à petit prix (1 € ou 3,30 €).</p>
                    <a href="[https://www.crous.fr](https://www.crous.fr)" target="_blank" class="btn">Trouver un Resto U</a>
                </article>
            </div>
        </section>
    </main>

    <footer>
        <p>Projet Open Source hébergé sur GitHub Pages — Fait pour la communauté étudiante.</p>
    </footer>

</body>
</html># guide-survie--tudiant
Guide pratique et bons plans pour les étudiants en France et internationaux.
