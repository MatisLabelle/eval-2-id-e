# Idée de projet multimédia

## Idée
Étant passionné par la musique, j'aimerais réaliser un projet tournant autour de cette passion. Je souhaiterais proposer aux musiciens amateurs une expérience leur permettant de s'imaginer en train de donner un concert. La différence entre un concert et une simple session de jam réside dans l'ambiance. Pour recréer l'ambiance d'un concert dans un environnement sans public, il est essentiel de comprendre la synesthésie, ce concept qui lie nos sens entre eux.

Pour ce faire, le projet consisterait en un processus de traitement du son émis par l'utilisateur (via un instrument, un micro ou des sons préenregistrés). Le son reçu serait alors traité pour générer une expérience visuelle dynamique et interactive. L'expérience serait diffusée en direct sur une plateforme publique telle que Twitch, YouTube, Kick, TikTok... afin de permettre à l'utilisateur d'avoir une audience, même si celle-ci n'est pas physique.

## Scénario
Plusieurs instruments seront mis à disposition de l'utilisateur (guitare, piano, percussions, micro...). L'utilisateur aura donc le choix de l'instrument qu'il souhaite utiliser et de ce qu'il veut jouer. Le son sera ensuite traité et transformé en lumière et en vidéo.

Les percussions auraient un effet important sur les lumières, qui clignoteraient au rythme joué. Les instruments mélodiques, comme les guitares, pianos, voix... seraient représentés par des projections et des jeux de lumières. Chaque instrument aurait une couleur spécifique, qui changerait de teinte en fonction de sa fréquence et d'intensité selon son volume.

Le tout disposé devant une caméra pour la diffusion du jam.

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

[![ILLUMINATOR live performance demo (SOMA labs)](https://i.ytimg.com/vi/go22inMuRgQ/hqdefault.jpg?sqp=-oaymwEpCNACELwBSFryq4qpAxsIARUAAIhCGAHYAQHiAQwIGhACGAYgATgBQAE=&rs=AOn4CLA6CwuT2K_F_SQpNhJi4ErkhUZwhQ)](https://www.youtube.com/watch?v=go22inMuRgQ)

Inspiration pour la projection vidéo:
<img src="https://miro.medium.com/v2/resize:fit:1358/0*X8V9OosecAyGjb97"></img>

Palette de couleur : 
<img src="assets/Capture.PNG"></img>

## Technologies

Pour ce projet les technologies nécésaires seront: 
- Projecteur
- Lumière LED
- Ordinateur
- Instruments de musique
- Micro
- Cable XLR
- Caméra
- Carte d'aquisition vidéo

Et les logiciels nécéssaires seront: 
- Touch Designer
- QLC +
- Plugdata
- MidiLoop
- OBSstudio
- Site de diffuion (twitch, yt, tiktok, kick...)
