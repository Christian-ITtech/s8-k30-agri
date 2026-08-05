## Presentation du groupe et Attribution des taches

### Groupe : Light-Tech
Light-Tech est un groupe de jeunes innovateurs passionnes, reunis par la Cohorte 2 d'Akieni Academy.  
Animes par la creativite et l'esprit d'equipe, ils s'engagent a transformer des idees en solutions concretes, au service de l'innovation et du progres.

---

### Repartition detaillee des roles et realisations

#### Marketing et Business Analysis
* **MASSANGA Gelcy Ildard**  *Lead du groupe & Lead Marketing & Communication*  
  * Email : precieuxgi@gmail.com
* **KILEBE Andelsonne**  *Lead Business Analyst* (Analyse du cahier des charges COMAKI, definition des besoins metier)  
  * Email : tosanderson16@gmail.com

---

#### Equipe Data Science (`backend/logic.py`)
Responsables de l'implementation de la logique metier Python et de la reussite des 39 tests unitaires `pytest`.

* **KIESSI Lucia**  *Lead Data*  
  * Email : kiessilucia009@gmail.com | GitHub : `@LK-BH`
  * **Zone A (Tableau de bord & Statistiques)  6 fonctions :**
    * `calculer_volume_total()`
    * `calculer_total_membres_actifs()`
    * `calculer_montant_total_paye()`
    * `calculer_chiffre_affaires_total()`
    * `generer_statistiques_globales()`
    * `generer_classement_producteurs()`

* **NGONO-NGONO Mignon**  
  * Email : ngonomignon2@gmail.com | GitHub : `@Mignon-NGONO`
  * **Zone B (Membres & Livraisons) 7 fonctions :**
    * `filtrer_membres_par_statut()`
    * `rechercher_membres()`
    * `valider_nouveau_membre()`
    * `detecter_doublon_membre()`
    * `valider_livraison()`
    * `calculer_total_livraisons_membre()`
    * `filtrer_livraisons_par_periode()`

* **MONGO Max Espoir**  
  * Email : maxespoirmongo@gmail.com
  * **Zone C & D (Ventes, Stock, Paiements & Authentification)  7 fonctions :**
    * `valider_paiement()`
    * `calculer_solde_membre()`
    * `valider_vente()`
    * `calculer_stock_disponible()`
    * `verifier_authentification()`
    * `verifier_droits_acces()`
    * `generer_rapport_bailleur()`

---

#### Equipe Full Stack (`frontend/`)
Responsables du developpement des pages HTML/CSS (responsive, semantique, design) et des fonctions pures dans `frontend/functions.js` validees par `functions.test.html`.

| Membre | Email | Pseudo GitHub | Role / Focus | Pages HTML / CSS creees & stylisees | Fonctions JavaScript implementees |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Matondo Jonathan** | johnniumatos@gmail.com | `@matondojonathan` | *Lead Fullstack* | `login/login.html`<br>`dashboard/dashboard.html` | `validerFormulaireLogin`<br>`compterJoursActifs` |
| **NDOUKOU MAMBOU Don Reel** | reelndoukou@gmail.com | `@reelndoukou` | *Dev FS2* | `membres/membres.html`<br>`comptes/comptes.html` | `filtrerMembresParStatut`<br>`rechercherMembreParNom`<br>`validerFormulaireNouveauMembre` |
| **NDONGALA Dreche** | drechemaestro1@gmail.com | `@m-ris` | *Dev FS3* | `livraisons/livraisons.html` | `validerFormulaireLivraison`<br>`trierLivraisonsParDate` |
| **Louamba Ceti Delaure** | slowceti@gmail.com | `@Cetislow` | *Dev FS4* | `paiements/paiements.html` | `validerFormulairePaiement`<br>`calculerTotalPaiements` |
| **Moutou Moukolo Christian Dorgela** | christiandorgela2@gmail.com | `@Christian-ITtech` | *Repo Admin / Dev FS5* | `ventes/ventes.html` | `getBadgeStock`<br>`formaterMontant` |
| **LELO MAKAYA Sunelson Isaac** | lelomakayasunelsonisaac@gmail.com | — | *Product Owner / Dev FS6* | `statistiques/statistiques.html` | `trierClassementParVolume`<br>`formaterDate` |
