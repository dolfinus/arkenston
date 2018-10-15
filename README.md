# Arkenston
## Description
A Ruby on Rails and Nuxt.js+Vue.js based site with information about crystal structures, compounds, solubilities, theory and so on.

## Installation
Repos `dolfinus/arkenston-backend` and `dolfinus/arkenston-frontend` are used as submodules of project.

Fistly, you should install npm dependencies:
```bash
npm install -g
```

and then fetch submodules:
```bash
meta git update
```

After that you should use `meta` for managing project and installing dependencies:
```bash
meta npm install
meta npm link --all
npm link
```
