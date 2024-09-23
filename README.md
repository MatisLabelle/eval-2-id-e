# Idée de projet multimédia

## Idée
Étant passionné de musique j'aimerais faire une projet tournant autour de cette passion.
J'aimerais pouvoir proposer au musiciens amateurs une expérience leur permettant de s'imaginer donner un concert. La différence entre un concert et une session de jam seule est l'ambiance. Pour donner l'ambiance d'un concert à un environnement sans publique il faut comprendre la synesthésie, le concept de lié nos sens entre eux.. 

Pour ce faire, le projet consisterait d'un processus de traitement du son émis par l'utilisateur (par un instrument, micro ou sons préenregistré). Le son reçu serait alors traité pour retourner une expérience visuelle dynamique et intéractive. L'expérience serait retransmit en direct sur un site de diffusion publique comme twitch, youtube, kick, tik tok... pour permettre à l'utilisateur d'avoir une audience même si elle n'est pas physique.

## Scénario
Plusieurs instruments seront mis à disposition de l'utilisateur.(Guitare, piano, percussion, micro...) L'utilisateur aura donc le chois de l'instrument qu'il veut utiliser et de ce qu'il veut jouer avec. Le son sera ensuite traité et transformé en lumière et vidéo.

Les percussions aurait un effet important sur les lumières qui clignoterait au rythme joué. Les instruments mélodiques comme les guitares, pianos, voix... serait représenté par la projection et les lumières. Châque instrument aurait une couleur spéciphique qui changerait de teinte par rapport à sa fréquence. 

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
