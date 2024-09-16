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

Inspiration pour la projection vidéo: ![waveform visualizer]([https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_%28novel%29](https://miro.medium.com/v2/resize:fit:1358/0*X8V9OosecAyGjb97))
