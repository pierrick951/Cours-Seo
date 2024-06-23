# Cours sur la SEO

## A quoi ça sert ?
SEO (Search Engine Optimization) est l'optimisation pour les moteurs de recherche. Les moteurs de recherche explorent le web et indexent le contenu en fonction de divers critères pour le classer dans les résultats de recherche.

[En savoir plus sur MDN](https://developer.mozilla.org/fr/docs/Glossary/SEO)

## Le SEO en trois grandes classes

### Technique
Marquez le contenu en utilisant la sémantique HTML. Lors de l'exploration du site Web, les robots d'exploration doivent trouver uniquement le contenu que vous souhaitez indexer.

### Rédaction
Écrivez du contenu en utilisant le vocabulaire de vos visiteurs. Utilisez du texte ainsi que des images pour que les robots puissent comprendre le sujet.

### Popularité
Vous obtenez plus de trafic lorsque d'autres sites établis pointent vers votre site.

## Conseils pour le contenu

- **Qualité et pertinence :** Le contenu doit être de haute qualité, pertinent et mis à jour régulièrement.
- **Mots-clés :** Intégrer naturellement des mots-clés pertinents sans surcharger.
- **Titres et sous-titres :** Utiliser des titres et sous-titres descriptifs pour organiser le contenu.

## Conseils pour les images

- **Balises alt :** Ajouter des descriptions dans les balises alt pour toutes les images.
- **Noms de fichiers :** Utiliser des noms de fichiers descriptifs pour les images.
- **Formats optimisés :** Utiliser des formats d'image optimisés pour le web (ex. JPEG, PNG) et compresser les images pour améliorer le temps de chargement.

## Conseils pour les performances

- **Optimisation et minification du CSS et JS :** Réduire la taille des fichiers pour améliorer la vitesse de chargement.
- **Mobile First :** Assurez-vous que le site est entièrement responsive et fonctionne bien sur les appareils mobiles.

## Sitemap XML
Un sitemap XML est un fichier qui liste toutes les pages importantes de votre site web, fournissant des informations supplémentaires comme la date de dernière modification, la fréquence de mise à jour, et l'importance relative de chaque page. Cela aide les moteurs de recherche à mieux comprendre la structure de votre site et à indexer toutes les pages importantes.

### Exemple de sitemap.xml
```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://www.example.com/</loc>
    <lastmod>2024-06-01</lastmod>
    <changefreq>daily</changefreq>
    <priority>1.0</priority>
  </url>
  <url>
    <loc>https://www.example.com/about</loc>
    <lastmod>2024-05-28</lastmod>
    <changefreq>monthly</changefreq>
    <priority>0.8</priority>
  </url>
  <!-- Ajouter d'autres URLs ici -->
</urlset>



Ce cours couvre maintenant un large éventail de sujets pertinents en SEO, offrant une ressource complète pour l'apprentissage et la mise en œuvre de bonnes pratiques en SEO.
