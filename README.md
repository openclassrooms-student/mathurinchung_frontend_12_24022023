# Développez un tableau de bord d'analytics avec React

Vous travaillez en tant que développeur chez SportSee, une startup dédiée au coaching sportif. En pleine croissance, l’entreprise va aujourd’hui lancer une nouvelle version de la page profil de l’utilisateur. Cette page va notamment permettre à l’utilisateur de suivre le nombre de sessions réalisées ainsi que le nombre de calories brûlées.

![Logo de SportSee](docs/sportseelogo.png)
> *Logo de SportSee*

Vous recevez ce matin un Slack de Charles, le Product Owner :

> 
> :speech_balloon:
>
> Hello ! Bon, c’est le grand jour aujourd’hui, on va s’attaquer à la nouvelle page profil utilisateur du site :). Tiens, Léo (le designer) vient de me faire parvenir [le lien Figma de la maquette](https://www.figma.com/file/BMomGVZqLZb811mDMShpLu/UI-design-Sportify-FR?node-id=0%3A1). Et voici[ le kanban avec les User Stories](https://www.notion.so/openclassrooms/Copy-of-Dev4U-projet-Learn-Home-6686aa4b5f44417881a4884c9af5669e) à intégrer pour ce projet. Pour ce sprint, il faut que tu intègres les US de la partie TODO (le reste sera au sprint suivant).
>

Plus tard durant la journée, vous recevez un mail de votre Lead Developer, Antoine, vous donnant plus de détails techniques sur le projet.

>
> :envelope:
>
> **From**: Antoine
> **To**: Moi
> **Subject**: Précisions techniques sur la page profil
>
> Re,
>
> Charles m’a dit qu’il t’avait briefé sur les User Stories et les maquettes, voici donc plus d’infos côté technique.
> 
> L’objectif est de refaire la page profil avec React. Tu seras en charge de développer la page.
> 
> Comme tu as pu le constater, le projet intègre des graphiques sur l’activité sportive de l’utilisateur. Je t’invite à utiliser soit D3, soit Recharts. Cela dit, fais attention à D3, c’est assez puissant comme librairie mais parfois difficile à prendre en main.
>
> Concernant l’intégration CSS du projet, notre Product Owner préfère qu’on se concentre sur la partie desktop pour l’instant. Tu n’as donc pas besoin de travailler sur la version mobile et tablette du projet. Nous ferons ça dans un second temps. Cela dit, fais bien attention à ce que ton projet puisse être lisible sur les écrans d’au moins 1024 par 780 pixels.
>
> Concernant les données, je t’ai créé un [backend utilisant NodeJS que tu peux trouver ici](https://github.com/OpenClassrooms-Student-Center/P9-front-end-dashboard). Il va te permettre de réaliser tes calls HTTP et de récupérer des données d’exemple. Tout y est décrit : les étapes d’installation ainsi que les calls HTTP que j’ai mis en place.
>
> Pour la gestion des calls en eux-mêmes, je t’invite à utiliser soit [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API), soit [Axios](https://github.com/axios/axios). Par contre, il est important que tu réalises les calls en dehors des composants React. Il faudra que tu crées un service à part qui se chargera de faire les calls pour toi.
>
> D’ailleurs, il faudra que tu commences le projet en réalisant un mock des données de l'API. Dès que ton projet sera fonctionnel, tu pourras t’attaquer à l’intégration de l’API. Il faudra également que tu crées une classe de modélisation des données pour t'assurer de toujours formater correctement les données de l'API avant de les utiliser.
>
> Pour finir, il est important que tu documentes ton projet pour que tout le monde puisse travailler dessus :slight_smile:. Garde donc en tête :
>
> * L’ensemble de ta documentation doit être réalisée en anglais.
> * Le fichier README ne doit comporter que les étapes d’installation ainsi que les prérequis du projet. Dans ce fichier, tu devras dire comment installer et lancer le projet.
> * Ton projet va utiliser React et tu vas forcément créer des components. Il est donc important que tu intègres des Proptypes pour chacun de tes components. 
> * Dernier point, la JsDoc. En dehors des méthodes de cycle de vie (componentDidMount par exemple), il est important que ton projet ait des fonctions et méthodes documentées. 
>
> Allez, je te souhaite un bon développement !
>
> Antoine
>

Ça y est, vous avez toutes les informations nécessaires et vous pouvez démarrer le développement de la page.
