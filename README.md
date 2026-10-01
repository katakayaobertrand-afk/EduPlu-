# EduPlus — version A à Z

Structure à conserver :
- index.html
- package.json
- vercel.json
- .env.example
- api/ai.mjs

Déploiement :
1. Créer un dépôt GitHub `eduplus`.
2. Importer ces fichiers sans modifier les noms.
3. Dans Vercel, importer le dépôt.
4. Framework : aucun / Other.
5. Root Directory : `./`.
6. Pas de commande de build.
7. Deploy.

IA :
Dans Vercel > Settings > Environment Variables, ajouter `OPENAI_API_KEY`.
Ne jamais publier la vraie clé dans GitHub.

La version inclut une interface EduPlus, recherche, cours, exercices, corrigés, compte de démonstration, WhatsApp et endpoint IA.
Les vrais comptes sécurisés, base de données, espace admin et stockage de PDF seront ajoutés ensuite.
