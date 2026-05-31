# Ibrahima BALDE 
**Agricultural Data Scientist & Agroécologiste**  
*M.Sc. Agroécologie et Systèmes Alimentaires Durables (USSEIN) | Spécialiste R, Python & Télédétection Drone*

Je combine une solide expertise agronomique de terrain au Sahel (diagnostics d'exploitations, encadrement, cartographie) avec la puissance de l'analyse de données avancée, des biostatistiques et de la télédétection par drone pour optimiser les itinéraires techniques et accélérer la sélection variétale moderne.

---

### 🚀 Projet Phare : R&D, Simulation Variétale & Phénotypage Drone (Auto-formation & Valorisation)

#### 🔬 [peaboost-yield-analytics](https://github.com/ibalde006-boop/peaboost-yield-analytics)
*   **Contexte et Résilience :** Projet d'ingénierie statistique développé en autonomie (Master 2 ASAD, USSEIN)[cite: 2]. Suite à la restructuration du stage PeaBoost 2026[cite: 2], j'ai conçu ce pipeline complet basé sur la **génération et la simulation de données agronomiques complexes** (8 génotypes de pois x 4 environnements x 2 campagnes 2025-2026) afin de maîtriser concrètement les outils de pointe de la sélection végétale[cite: 2].
*   **Architecture & Pipelines R implémentés :**
    *   **Modèles Mixtes (`lme4`, `lmerTest`, `emmeans`) :** Évaluation des effets fixes (Génotype, Environnement, Campagne, Interaction G×E) et aléatoires (Répétition dans l'Environnement) sur le rendement grain[cite: 2]. Calcul des moyennes marginales estimées et classification par test de comparaison multiple de Tukey[cite: 2].
    *   **Interaction G×E & Stabilité (`metan`) :** Modélisation AMMI (Additive Main effects Multiplicative Interaction), calcul de l'indice de stabilité WAASB et génération de graphiques *GGE Biplot* ("Which-Won-Where") pour l'aide à la décision en sélection[cite: 2].
    *   **Analyse Multivariée & Typologies (`FactoMineR`, `factoextra`) :** Exploration des corrélations des composantes du rendement (Rendement, Nb_gousses_m², Nb_graines_gousse, PMG, LAI_max, Teneur en Protéines) via une Analyse en Composantes Principales (ACP) couplée à une Classification Ascendante Hiérarchique (CAH / HCPC) pour identifier 3 clusters de profils agronomiques[cite: 2].
    *   **Phénotypage Drone & Télédétection (`terra`, `RStoolbox`) :** Simulation d'images matricielles multibandes (Caméra Micasense RedEdge : Bleu, Vert, Rouge, RedEdge, PIR)[cite: 2]. Calcul programmatique d'indices spectraux avancés (**NDVI, GNDVI, GRVI, NDRE, SAVI**) et modélisation de la relation NDVI-Rendement par régression linéaire[cite: 2].

---

### 💼 Portfolio : Projets Techniques & Expériences Terrain

#### 🛰️ [qgis-anacarde-bio-cartography](https://github.com/ibalde006-boop/qgis-anacarde-bio-cartography)
*   **Ancrage Réel :** Chargé de Cartographie chez NOURSERVI (Zone Sokone et Toubacouta)[cite: 1].
*   **Détails Techniques :** Structuration de bases de données géospatiales sous QGIS pour la certification biologique de **150 producteurs d’anacarde** (délimitation de parcelles et analyse cartographique)[cite: 1].

#### 🌾 [sorgho-agroecology-analytics](https://github.com/ibalde006-boop/sorgho-agroecology-analytics)
*   **Ancrage Réel :** Responsable de production Sorgho (Campagne hivernale 2025) – Projet PEA-PETTAL (Ferme Intégrée USSEIN, Mbadakhoune)[cite: 1].
*   **Détails Techniques :** Suivi rigoureux des itinéraires techniques, diagnostics phytosanitaires de terrain et gestion de pépinières agroécologiques[cite: 1].

#### 📊[agri-survey-data-pipeline](https://github.com/ibalde006-boop/agri-survey-data-pipeline)
*   **Ancrage Réel :** Enquêtes et recensements d'envergure (ANSD - RGPH-5, PULA Advisor au bassin de l'Anambé)[cite: 1].
*   **Détails Techniques :** Collecte via KoboToolbox, nettoyage, structuration et traitement statistique de données d'enquêtes socio-économiques et rizicoles complexes[cite: 1].

---

### 🧰 Ma Stack Technique Référencée

*   **Data Science, Biostatistiques & Modélisation (R) :** `tidyverse` (manipulation), `ggplot2` & `corrplot` (dataviz), `lme4` (modèles mixtes), `metan` (GxE), `FactoMineR` (ACP/CAH)[cite: 2].
*   **SIG, Télédétection & Phénotypage :** `terra` (manipulation de rasters), `RStoolbox` (indices spectraux), QGIS, KoboToolbox / KoboCollect[cite: 1, 2].
*   **Biostatistiques Mathématiques (Fondements IMT Business School) :** Gestion des variables aléatoires, fonctions de répartition, calcul d'espérance et variance appliquée à l'expérimentation[cite: 1].
*   **Programmation Python (Fondements Université Côte d'Azur) :** Maîtrise des structures de données (listes, séquences, chaînes complexes, encodage Unicode)[cite: 1].
*   **Web & Design Éco-responsable (FORCE-N) :** HTML5, CSS3, JavaScript, WordPress, Suite Adobe (Photoshop, Illustrator), Canva[cite: 1].

---

### 🎓 Parcours Académique

*   **Master 2 (Bac+5) en Agroécologie et Systèmes Alimentaires Durables (ASAD)** – USSEIN (2024 - 2026)[cite: 1]
    *   *UFR :* Sciences Sociales et Environnementales[cite: 2].
    *   *Spécialisation :* Modélisation, biostatistiques avancées et application de la télédétection drone à l'amélioration végétale (via l'étude de cas pratique *PeaBoost*)[cite: 1, 2].
    *   *Terrain :* Immersion intensive de 3 jours à **Bignona (ECO FROM AFRICA)**[cite: 1].
*   **Licence (Bac+3) en Agriculture Biologique & Écologique** – USSEIN (2019 - 2022)[cite: 1]
    *   *Expertise :* Diagnostics complets d'exploitations, immersion à l'**ISRA de Bambey**, étude d'une ferme intégrée de +90 ha à Thiès (bâtiments avicoles de 500 m²) et de la coopérative Capcoo à Latmingué[cite: 1].

---

### 📜 Certifications Officielles 

*   **Statistique pour l'ingénieur, Mathematical Statistics and Probability** — *Institut Mines-Télécom Business School*[cite: 1]
*   **Python : des fondamentaux aux concepts avancés du langage** — *Université Côte d'Azur*[cite: 1]
*   **Suivi-évaluation de projets de développement** — *Agence Française de Développement (AFD)*[cite: 1]
*   **Conception de projets respectueux de l'environnement** — *AFD*[cite: 1]
*   **Finance carbone et gaz à effet de serre** — *AFD*[cite: 1]
*   **Adaptation au changement climatique & Éducation climatique** — *École Virtuelle du Climat (EVC)*[cite: 1]

---

### 👥 Leadership & Engagements
*   **Président de la Commission Sociale du Master ASAD :** Gestion des allocations, du logement et de la santé des étudiants de la promotion[cite: 1].

**Explorons de nouvelles synergies :** [Mon Profil LinkedIn](https://www.linkedin.com/in/ibrahima-bald%C3%A9-42210322b/) | 📧 ibalde006@gmail.com
