nigaz@nigaz-82JQ:~/IonicWorks$ git clone git@github.com:sassani134/writPinsESGI.git
Clonage dans 'writPinsESGI'...
warning: Vous semblez avoir cloné un dépôt vide.
nigaz@nigaz-82JQ:~/IonicWorks$ ionic start
? Use the app creation wizard? No

Pick a framework! 😁

Please select the JavaScript framework to use for your new app. To bypass this prompt next time, supply a value for the
--type option.

? Framework: React

Every great app needs a name! 😍

Please enter the full name of your app. You can change this at any time. To bypass this prompt next time, supply name,
the first argument to ionic start.

? Project name: writPinsESGI

Let's pick the perfect starter template! 💪

Starter templates are ready-to-go Ionic apps that come packed with everything you need to build your app. To bypass this
prompt next time, supply template, the second argument to ionic start.

? Starter template: list
? ./writPinsESGI exists. Overwrite? Yes
✔ Preparing directory ./writPinsESGI in 2.92ms
✔ Downloading and extracting list starter in 140.43ms
> ionic integrations enable capacitor --quiet -- writPinsESGI io.ionic.starter
> npm i --save -E @capacitor/core@latest

added 681 packages, and audited 682 packages in 28s

147 packages are looking for funding
  run `npm fund` for details

2 moderate severity vulnerabilities

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
> npm i -D -E @capacitor/cli@latest

added 63 packages, and audited 745 packages in 3s

153 packages are looking for funding
  run `npm fund` for details

2 moderate severity vulnerabilities

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
> npm i --save -E @capacitor/haptics @capacitor/app @capacitor/keyboard @capacitor/status-bar

added 4 packages, and audited 749 packages in 2s

153 packages are looking for funding
  run `npm fund` for details

2 moderate severity vulnerabilities

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
> capacitor init writPinsESGI io.ionic.starter --web-dir dist
✔ Creating capacitor.config.ts in /mnt/e644da04-91ef-4746-8f4c-8890d86663ff/IonicWorks/writPinsESGI in 2.07ms
[success] capacitor.config.ts created!

Next steps:
https://capacitorjs.com/docs/getting-started#where-to-go-next
[OK] Integration capacitor added!

Installing dependencies may take several minutes.

  ──────────────────────────────────────────────────────────────────────────────

         Ionic Advisory, tailored solutions and expert services by Ionic

                             Go to market faster 🏆
                    Real-time troubleshooting and guidance 💁
        Custom training, best practices, code and architecture reviews 🔎
      Customized strategies for every phase of the development lifecycle 🔮

                        👉  https://ion.link/advisory  👈

  ──────────────────────────────────────────────────────────────────────────────


> npm i

up to date, audited 749 packages in 913ms

153 packages are looking for funding
  run `npm fund` for details

2 moderate severity vulnerabilities

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
> git init
astuce: Utilisation de 'master' comme nom de la branche initiale. Le nom de la branche
astuce: par défaut peut changer. Pour configurer le nom de la branche initiale
astuce: pour tous les nouveaux dépôts, et supprimer cet avertissement, lancez :
astuce:
astuce: 	git config --global init.defaultBranch <nom>
astuce:
astuce: Les noms les plus utilisés à la place de 'master' sont 'main', 'trunk' et
astuce: 'development'. La branche nouvellement créée peut être rénommée avec :
astuce:
astuce: 	git branch -m <nom>
Dépôt Git vide initialisé dans /mnt/e644da04-91ef-4746-8f4c-8890d86663ff/IonicWorks/writPinsESGI/.git/

Join the Ionic Community! 💙

Connect with millions of developers on the Ionic Forum and get access to live events, news updates, and more.

? Create free Ionic account? No
> git add -A
> git commit -m "Initial commit" --no-gpg-sign
[master (commit racine) 9d3b684] Initial commit
 32 files changed, 10658 insertions(+)
 create mode 100644 .browserslistrc
 create mode 100644 .eslintrc.js
 create mode 100644 .gitignore
 create mode 100644 .vscode/extensions.json
 create mode 100644 capacitor.config.ts
 create mode 100644 cypress.config.ts
 create mode 100644 cypress/e2e/test.cy.ts
 create mode 100644 cypress/fixtures/example.json
 create mode 100644 cypress/support/commands.ts
 create mode 100644 cypress/support/e2e.ts
 create mode 100644 index.html
 create mode 100644 ionic.config.json
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 public/favicon.png
 create mode 100644 public/manifest.json
 create mode 100644 src/App.test.tsx
 create mode 100644 src/App.tsx
 create mode 100644 src/components/MessageListItem.css
 create mode 100644 src/components/MessageListItem.tsx
 create mode 100644 src/data/messages.ts
 create mode 100644 src/main.tsx
 create mode 100644 src/pages/Home.css
 create mode 100644 src/pages/Home.tsx
 create mode 100644 src/pages/ViewMessage.css
 create mode 100644 src/pages/ViewMessage.tsx
 create mode 100644 src/setupTests.ts
 create mode 100644 src/theme/variables.css
 create mode 100644 src/vite-env.d.ts
 create mode 100644 tsconfig.json
 create mode 100644 tsconfig.node.json
 create mode 100644 vite.config.ts

Your Ionic app is ready! Follow these next steps:

- Go to your new project: cd ./writPinsESGI
- Run ionic serve within the app directory to see your app in the browser
- Run ionic capacitor add to add a native iOS or Android project using Capacitor
- Generate your app icon and splash screens using cordova-res --skip-config --copy
- Explore the Ionic docs for components, tutorials, and more: https://ion.link/docs
- Building an enterprise app? Ionic has Enterprise Support and Features: https://ion.link/enterprise-edition
nigaz@nigaz-82JQ:~/IonicWorks$ cd writPinsESGI/
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ touch README.md LICENCE Source.md Starter.md apprentissages.md choix-implementation.txt
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ rm -rf .git
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ git remote add origin git@github.com:sassani134/writPinsESGI.git
fatal: ni ceci ni aucun de ses répertoires parents (jusqu'au point de montage /mnt) n'est un dépôt git
Arrêt à la limite du système de fichiers (GIT_DISCOVERY_ACROSS_FILESYSTEM n'est pas défini).
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ git init
astuce: Utilisation de 'master' comme nom de la branche initiale. Le nom de la branche
astuce: par défaut peut changer. Pour configurer le nom de la branche initiale
astuce: pour tous les nouveaux dépôts, et supprimer cet avertissement, lancez :
astuce:
astuce: 	git config --global init.defaultBranch <nom>
astuce:
astuce: Les noms les plus utilisés à la place de 'master' sont 'main', 'trunk' et
astuce: 'development'. La branche nouvellement créée peut être rénommée avec :
astuce:
astuce: 	git branch -m <nom>
Dépôt Git vide initialisé dans /mnt/e644da04-91ef-4746-8f4c-8890d86663ff/IonicWorks/writPinsESGI/.git/
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ git remote add origin git@github.com:sassani134/writPinsESGI.git
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ git branch -M main
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ git add .
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ git commit -m "first commit"
[main (commit racine) 66c05e1] first commit
 38 files changed, 10658 insertions(+)
 create mode 100644 .browserslistrc
 create mode 100644 .eslintrc.js
 create mode 100644 .gitignore
 create mode 100644 .vscode/extensions.json
 create mode 100644 LICENCE
 create mode 100644 README.md
 create mode 100644 Source.md
 create mode 100644 Starter.md
 create mode 100644 apprentissages.md
 create mode 100644 capacitor.config.ts
 create mode 100644 choix-implementation.txt
 create mode 100644 cypress.config.ts
 create mode 100644 cypress/e2e/test.cy.ts
 create mode 100644 cypress/fixtures/example.json
 create mode 100644 cypress/support/commands.ts
 create mode 100644 cypress/support/e2e.ts
 create mode 100644 index.html
 create mode 100644 ionic.config.json
 create mode 100644 package-lock.json
 create mode 100644 package.json
 create mode 100644 public/favicon.png
 create mode 100644 public/manifest.json
 create mode 100644 src/App.test.tsx
 create mode 100644 src/App.tsx
 create mode 100644 src/components/MessageListItem.css
 create mode 100644 src/components/MessageListItem.tsx
 create mode 100644 src/data/messages.ts
 create mode 100644 src/main.tsx
 create mode 100644 src/pages/Home.css
 create mode 100644 src/pages/Home.tsx
 create mode 100644 src/pages/ViewMessage.css
 create mode 100644 src/pages/ViewMessage.tsx
 create mode 100644 src/setupTests.ts
 create mode 100644 src/theme/variables.css
 create mode 100644 src/vite-env.d.ts
 create mode 100644 tsconfig.json
 create mode 100644 tsconfig.node.json
 create mode 100644 vite.config.ts
nigaz@nigaz-82JQ:~/IonicWorks/writPinsESGI$ git push -u origin main
Énumération des objets: 45, fait.
Décompte des objets: 100% (45/45), fait.
Compression par delta en utilisant jusqu'à 16 fils d'exécution
Compression des objets: 100% (38/38), fait.
Écriture des objets: 100% (45/45), 95.43 Kio | 939.00 Kio/s, fait.
Total 45 (delta 2), réutilisés 0 (delta 0), réutilisés du pack 0
remote: Resolving deltas: 100% (2/2), done.
To github.com:sassani134/writPinsESGI.git
 * [new branch]      main -> main
la branche 'main' est paramétrée pour suivre 'origin/main'.
