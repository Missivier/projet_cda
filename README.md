### -- Projet SIVILIER Alexandre - UIMM Bruz - Master 5 ENI - Projet CDA --

#### /Commandes Utiles/

##### Environnement virtuel

- `python -m venv {nom de l'environement}` : **_créer_** l'environnment virtuel
- `./venv_win/Scripts` : chemin pour **_activer/désactiver_** environnement virtuel sur **WINDOWS**
  - `./activate` : **_activer_** environnement virtuel
  - `./deactivate` : **_desactiver_** environnement virtuel
- `./venv_linux/bin` : chemin pour **_activer/désactiver_** environnement virtuel sur **LINUX**
  - `source activate` : **_activer_** environnement virtuel
  - `source deactivate` : **_desactiver_** environnement virtuel

##### Installation des packages

- `pip install -r requirements.txt` : **_installer_** les packages dans l'environnement virtuel
- `pip freeze > requirements.txt` : **_mettre à jour_** le fichier **requirements.txt**

##### Installation du framework "TailwindCSS"

- `npm install -D tailwindcss` : **_installer_** tailwindcss
- `npx tailwindcss init` : **_créer_** fichier **_tailwind.config.js_**

Dans le fichier **_tailwind.config.js_**
