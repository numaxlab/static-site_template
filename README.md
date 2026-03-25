# Plantilla para sitios estáticos

Esta plantilla serve para crear e publicar sitios estáticos usando GitHub Pages.

## Instalación e configuración

1. **Crea un repositorio a partir desta plantilla**
2. **Habilita GitHub Pages**:
    * En GitHub, vai ao repositorio creado a partir desta plantilla → "Settings" → "Pages".
    * No apartado "Build and deployment" → "Source", escolle "Deploy from a branch". Selecciona o branch "main", e folder "/ (root)".
    * Garda e despois duns minutos nesta mesma sección verás unha mensaxe de "Your site is live at XXXX".

## Configuración dun dominio

1. No dominio que se quere empregar, na configuración DNS, engadir un rexistro tipo **CNAME** ```www``` apuntando a ```numaxlab.github.io``` e outro tipo **ANAME** ```@``` apuntando a ```numaxlab.github.io```
2. En GitHub, vai ao repositorio → "Settings" → "Pages" → "Custom domain", escribe o dominio (con www) e dálle a gardar.
3. Agarda uns minutos para que GitHub poida comprobar a configuración DNS e despois aparecerá nesta sección de configuración de GitHub Pages "Your site is live at https://dominio.gal"
