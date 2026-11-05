# Podcaster

Podcaster is a small website to browse the episodes of **Black Mango**, a Spanish podcast about history, crime and adventure.

Project made by **Daniel Chaves Domínguez** (2nd year DAW) for the Web Interface Design course, using only **HTML5 and CSS3**, without JavaScript, frameworks or preprocessors.

**Live site:** https://daniel-chaves-dominguez.github.io/Podcaster/

## Views

- **Home (`index.html`):** 20 cards, one for each topic of the podcast. The search field is only visual, because the project has no JavaScript.
- **Podcast (`podcast.html`):** the details of the podcast and a table with its 135 episodes, grouped by topic. Each card on the home page takes you to its topic in the table.
- **Episode (`episode.html`):** the description of an episode, with links to YouTube, and an HTML5 audio player.

All the animations and effects are made with CSS.

## Folder structure

```
Podcaster/
├── index.html      Home page with the topics
├── podcast.html    Podcast details and table of episodes
├── episode.html    Episode details and audio player
├── css/
│   └── styles.css  All the styles
└── README.md
```

The images and the audio are hosted on Cloudinary and linked by their URL.

## How to view it

Nothing needs to be installed. You can open `index.html` in Chrome or use the **Live Server** extension for VS Code (right click on `index.html` > *Open with Live Server*).

The fade between pages does not work if you open the files directly, so use Live Server or the live site to see it.

## Screenshots

### Home

![Home page](https://res.cloudinary.com/duzljw2pp/image/upload/f_auto,q_auto,w_1200/v1793884971/captura-index_ndjbna.png)

### Podcast

![Podcast page](https://res.cloudinary.com/duzljw2pp/image/upload/f_auto,q_auto,w_1200/v1793884971/captura-podcast_ewrb6d.png)

### Episode

![Episode page](https://res.cloudinary.com/duzljw2pp/image/upload/f_auto,q_auto,w_1200/v1793884971/captura-episode_keaqnn.png)

## Credits

This is a class project with no official connection to Black Mango. The name, logo, images, audio and episode information belong to its creators. You can watch all the episodes on their [YouTube channel](https://www.youtube.com/@blackmangopodcast).
