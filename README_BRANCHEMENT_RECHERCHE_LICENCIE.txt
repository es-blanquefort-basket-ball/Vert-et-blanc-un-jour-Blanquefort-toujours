BRANCHEMENT — RECHERCHE LICENCIÉ DEPUIS LICENCIES_APP

Objectif :
permettre au parent de retrouver son enfant depuis LICENCIES_APP avant enregistrement.

À remplacer / ajouter dans Apps Script :
1. Remplacer Code.gs complet par le fichier :
   Code.gs

2. Ajouter un nouveau fichier Apps Script :
   module_recherche_licencies_app_v1.gs

3. Ne pas supprimer :
   - module_app_fin_saison_v1.gs
   - module_essais_2026_2027.gs
   - autres fichiers setup/audit

4. Enregistrer.

5. Redéployer :
   Déployer → Gérer les déploiements → Modifier → Nouvelle version → Déployer.

À remplacer dans GitHub :
- portail-licencie/index.html

Test :
1. Vérifier que l’onglet LICENCIES_APP existe et contient au moins Nom / Prénom / Date naissance / Licence / Catégorie.
2. Ouvrir portail licencié.
3. Onglet Parent.
4. Rechercher avec nom + prénom + date de naissance.
5. Choisir le résultat.
6. Enregistrer.
7. Vérifier APP_IDENTIFICATIONS.

URL Apps Script utilisée :
https://script.google.com/macros/s/AKfycbx2isdaOnCpljcE8I1RaBSp8Jflp8-LJjgUgHp8N0l57cV7wpkQvXV4GX01anp-6wJ6CA/exec
