---
permalink: /EtiquetasdeDatosEstructurados/
title: "Etiquetas de Datos Estructurados según <a href="http://schema.org">schema.org"</a>"
author_profile: true
header:
    overlay_color: "#000"
    overlay_filter: "0.5"
    overlay_image: assets/images/wallpaper-3.jpg
excerpt: ""
---

Según <a href="http://schema.org">schema.org</a>, un archivo mantenido por una organización, como lo puede ser un archivo de partidos disputados por el <a href="http://peñarol.org">Club Atlético Peñarol </a>durante el año y mantenido por una PEÑA puede ser implementado con las siguientes propiedades:
 - <a href="https://schema.org/Thing" style="color: red;font-weight: 900;">Objeto</a> > <a href="https://schema.org/Property" style="color: red;font-weight: 900;">Propiedad</a> > <a href="https://schema.org/conditionsOfAccess">Formas de Acceso</a>
 
    ```jsonld
 <!-- ArchiveComponent with restricted access -->
<script type="application/ld+json">
{
  "@context": "http://schema.org/",
  "@type": ["CreativeWork","ArchiveComponent"]
  "url": "https://abuseombudsman.github.io/ID-Penarolense/",
  "name": "Partidos Oficiales del Club Atlético Peñarol en el 2019",
  "conditionsOfAccess": "Acceso libre a través de la página de búsqueda del sitio oficial de la PEÑA ID-Penarolense",
  "holdingArchive": {
    "@type": "ArchiveOrganization",
    "name": "Repositorio Digital de la PEÑA ID-Penarolense",
    "url": "https://abuseombudsman.github.io/ID-Penarolense/"
  }
}</script>
   ```
