# ⚙️ Documentation Technique — Architecture & Choix de Conception

Le projet repose sur une architecture ultra-légère et performante, garantissant une maintenance aisée sur GitHub Pages.

---

## 🏛️ Architecture Monolithique

Pour éviter la complexité de gestion de multiples fichiers, l'ensemble du site est regroupé dans un fichier unique **`index1.html`** contenant la structure HTML, les styles CSS modernes et la logique JavaScript.

```mermaid
flowchart LR
    subgraph Client [Navigateur Web / ChromeOS]
        HTML[index1.html] --> CSS[Styles CSS + Variables Thème]
        HTML --> JS[Logique JS / Gestion Profil & Budget]
        JS --> Storage[(localStorage)]
    end
    subgraph Hosting [Hébergement]
        GitHub[GitHub Pages] -->|Diffusion statique| Client
    end
    subgraph External [Services Tiers]
        JS -->|Formulaires| Formspree[Formspree API]
        HTML -->|Polices| GoogleFonts[Google Fonts - Inter]
    end
