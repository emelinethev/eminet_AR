# eminet_AR

toujours en https (github.io en https)

# AR Markers detection

Bonnes pratiques ([ref](https://medium.com/chialab-open-source/10-tips-to-enhance-your-ar-js-app-8b44c6faffca))
- utiliser des markers asymétriques
- utilisé en landscape (optimisé) (bugs en passant de l'un à l'autre
- changement d'échelle sur les 3 axes en même temps
- taille du marker (règle empirique : doit être reconnaissable pour l'oeil humain). Marker de 3cm2 fonctionne à 40-50 cm
- imprimer le marker (plus de difficultés sur écrans : effets de brillances, …)
- laisser un bord clair autour du cadre
favoriser le contraste (noir-blanc mieux que couleurs)
au moins être de la moitié de la largeur du cadre.
- logique d'événement :
quand le marker est trouvé ou perdu
evénements souris (clic, mouse avec le curseur)
- utiliser Safari sur iOS (poublème accès webcam avec chrome _ bug google)
- resolution par défaut de la webcam (640x480px)
ex : pour changer en FullHD camera

`<a-scene embedded arjs=’sourceType: webcam; sourceWidth:1280; sourceHeight:960; displayWidth: 1280; displayHeight: 960;’>`

# AR Image Tracking (Natural Feature Tracking or NFT)
[example](https://github.com/AR-js-org/AR.js/tree/master/aframe/examples/image-tracking/)
[NFT marker creator](https://carnaux.github.io/NFT-Marker-Creator/)
[markers quality](https://github.com/Carnaux/NFT-Marker-Creator/wiki/Creating-good-markers)


# AR geolocalisation (GPS)

Localisation GPS
- https://www.coordonnees-gps.fr/ma-position
- https://www.latlong.net/
- https://esri.github.io/html5-geolocation-tool-js/
- https://www.torop.net/coordonnees-gps.php
- https://www.mapsdirections.info/fr/coordonnees-sur-google-map.html
- https://jsfiddle.net/fbqa8fuh/7/



# outils
- aframe inspector : ctrl+alt+i
- console : ctrl+maj+i (pas installé par défaut sur safari)



# liens

AR (Augmented Reality)
[Accueil AR.js](https://github.com/AR-js-org)

0. AR.js documentation :
[github](https://github.com/AR-js-org/AR.js-Docs) ou
[online](https://ar-js-org.github.io/AR.js-Docs/)

1. [librairie AR.js](https://github.com/AR-js-org/AR.js)
2. [AR.js with HTML balises](https://github.com/AR-js-org/aframe)

Image Tracking
3. [Image Creation](https://github.com/AR-js-org/NFT-Marker-Creator)

Square Markers - Patterns
1. [Markers Generator](https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html)
2. [Arttoolkit Barcode _ collection](https://github.com/AR-js-org/artoolkit-barcode-markers-collection)
3. [Markers in QR codes](https://medium.com/chialab-open-source/how-to-deliver-ar-on-the-web-only-with-a-qr-code-e24b7b61f8cb)




* AR markers (détection Markers)


* AR_geo (détection GPS)
[tuto : location based app](https://medium.com/chialab-open-source/build-your-location-based-augmented-reality-web-app-c2442e716564)
[tuto : peakfinder app](https://medium.com/chialab-open-source/build-your-location-based-augmented-reality-web-app-c2442e716564)


* a-frame
[cours a-frame](https://aframe-course.glitch.me/index.html)
[doc:primitives](https://github.com/aframevr/aframe/tree/master/docs/primitives)
[doc:components](https://github.com/aframevr/aframe/tree/master/docs/components)
[site](https://aframe.io/)
[getting start](https://aframe.io/docs/1.0.0/introduction/)
[blog examples](https://aframe.io/blog/)
[components:superframe](https://github.com/supermedium/superframe)
[components:](https://www.npmjs.com/search?q=keywords:aframe&page=1&ranking=optimal)
