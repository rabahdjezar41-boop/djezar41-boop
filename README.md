gh repo create rabahdjezar41-boop/my-idea --public --description "Projet expérimental" --license MIT --confirm --source=. --remote=origin --push
Importer un dépôt existant (deux approches simples)
Fork (si vous souhaitez contribuer au projet original et conserver le lien GitHub) :
Sur la page du dépôt source, cliquez sur Fork.
Ou avec gh : gh repo fork owner/repo --clone=true --remote=true
Importation complète dans un nouveau dépôt de votre compte (historique conservé, dépôt séparé) :
Utilisez GitHub Importer : https://github.com/new/import — collez l’URL du dépôt source et le nom/propriétaire du dépôt cible.
Ou manuellement :
git clone --mirror
