# PUBLICACIÓN RÁPIDA EN GITHUB

## 1. Crea un repositorio vacío
En GitHub crea un repositorio público, por ejemplo:
`portfolio-analisis-datos`

No agregues README, .gitignore ni licencia desde GitHub porque ya están incluidos aquí.

## 2. Abre una terminal dentro de esta carpeta y ejecuta

```bash
git init -b master
git add .
git commit -m "Publicar portafolio de proyectos"
git remote add origin https://github.com/TU_USUARIO/portfolio-analisis-datos.git
git push -u origin master
```

Si GitHub te pide iniciar sesión, completa el acceso en la ventana que aparezca.

## 3. Activa GitHub Pages

En el repositorio:
Settings → Pages → Build and deployment → Deploy from a branch

Selecciona:
- Branch: `master`
- Folder: `/(root)`

Pulsa **Save**.

Tu sitio normalmente quedará en:
`https://TU_USUARIO.github.io/portfolio-analisis-datos/`

## 4. Qué entregar

Entrega los dos enlaces:
- Repositorio: `https://github.com/TU_USUARIO/portfolio-analisis-datos`
- GitHub Pages: `https://TU_USUARIO.github.io/portfolio-analisis-datos/`
