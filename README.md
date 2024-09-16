# Idée de projet multimédia

## Idée
Étant passionné de musique j'aimerais faire une projet tournant autour de cette passion. J'aimerais pouvoir proposer au musiciens amateurs une expérience leur permettant de s'imaginer donner un concert. Pour ce faire, le projet consisterait d'un processus de traitement du son émis par l'utilisateur (par un instrument, micro ou sons préenregistré). Le son reçu serait alors traité pour retourner une expérience visuelle dinamique et intéractive.

## Scénario interactif
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
