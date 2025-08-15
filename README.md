Puis sélectionner `Generate_leads.json`.

3. **Configurer les credentials** :
- **SerpAPI** → Créer une clé API sur [https://serpapi.com/](https://serpapi.com/) et l’ajouter dans n8n.
- **Google Sheets** → Connecter votre compte Google.

4. **Adapter les paramètres** :
- `query` : type de business recherché.
- `city` / `country` : localisation.
- `max_leads` : nombre maximum de résultats.

5. **Exécuter le workflow** pour tester.

## 📌 Prérequis
- Un compte [n8n](https://n8n.io/) (local ou hébergé).
- Une clé API **SerpAPI** valide.
- Un compte Google avec accès à Google Sheets.

## ⚠️ Sécurité
Ne partagez jamais vos **clés API** ou **identifiants** dans un commit. Utilisez les variables d’environnement n8n pour stocker ces données sensibles.

## 📜 Licence
Ce projet est sous licence MIT. Vous êtes libre de le réutiliser et le modifier.
