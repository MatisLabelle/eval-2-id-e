# Idée de projet multimédia

## Idée
Étant passionné de musique j'aimerais faire une projet tournant autour de cette passion. J'aimerais pouvoir proposer au musiciens amateurs une expérience leur permettant de s'imaginer donner un concert. Pour ce faire, le projet consisterait d'un processus de traitement du son émis par l'utilisateur (par un instrument, micro ou sons préenregistré). Le son reçu serait alors traité pour retourner une expérience visuelle dinamique et intéractive.

## Scénario
Plusieurs instruments seront mis à disposition de l'utilisateur.(Guitare, piano, percussion, micro...) L'utilisateur aura donc le chois de l'instrument qu'il veut utiliser et de ce qu'il veut jouer avec. Le son sera ensuite traité et transformé en lumière et vidéo.

````mermaid
graph TD;

    A[Veille] --> B{Son de l'utilisateur};
    B --> C;
    C[Son traité dans le logiciel];
    C -->|Vidéo| E[Projection lancée];
    C -->|Lumière| F[Effets lumineux];
    C -->|Multimédia| G[Combinaison de médias];

    E --> H{Interaction terminée ?};
    F --> H;
    G --> H;

    H -->|Oui| I[Retour à veille];
    H -->|Non| C;
````
## Ambiance

Inspiration pour l'ambiance de l'idéé:
[![ILLUMINATOR live performance demo (SOMA labs)](https://www.youtube.com/watch?v=go22inMuRgQ.jpg)](https://www.youtube.com/watch?v=go22inMuRgQ)

Inspiration pour la projection vidéo:
<img href="https://miro.medium.com/v2/resize:fit:1358/0*X8V9OosecAyGjb97"></img>
[![An old rock in the desert](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)
