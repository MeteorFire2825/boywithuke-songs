# Boywithuke Songs
## A list of Boywithuke Songs.
###### This list may not be updated as i am working on other projects.
#### [meteorfire2825.github.io/boywithuke-songs](http://meteorfire2825.github.io/boywithuke-songs "meteorfire2825.github.io/boywithuke-songs")

---

### Instructions:
---
#### To change the title of the song you need to change the "song:" section.
```javascript
song:
```
---
#### To change the description of the song you need to change the "detail:" section.
```javascript
detail:
```
#### To change the url of the song you need to change the "url:" section.
```javascript
url:
```
## code for index.js
```javascript
const songData = [
  {
    song: "Bad Things",
    detail: "A song reflecting on the consequences of poor decisions and their impact.",
    url: "https://www.youtube.com/watch?v=giisqo8JZQ8"
  },
  {
    song: "Before I Die",
    detail: "A contemplative song about aspirations and life's fleeting nature.",
    url: "https://www.youtube.com/watch?v=uuCQmGFF_kA"
  },
  {
    song: "Broken (Home)",
    detail: "A song about feeling shattered and broken after a painful experience.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Can You Feel It?",
    detail: "A song capturing the emotion of being present in the moment.",
    url: "https://www.youtube.com/watch?v=XOJgO82MDuY"
  },
  {
    song: "Coffee",
    detail: "A song that delves into the comfort and warmth found in simple moments.",
    url: "https://www.youtube.com/watch?v=TSQrjglaGmk"
  },
  {
    song: "Cold Heart (Home)",
    detail: "A song reflecting on emotional detachment and being unable to feel.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Darkness (Home)",
    detail: "A haunting song about struggling with personal demons and internal darkness.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Echo (Home)",
    detail: "A song about hearing the echoes of the past and the lingering feelings of regret.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Euphoria (Home)",
    detail: "A song about experiencing moments of joy and bliss, despite life's struggles.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Faded (Home)",
    detail: "A song about the fading feelings in a relationship.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Fading (Home)",
    detail: "A song about the feeling of slipping away from reality and losing touch with the world.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Gaslight",
    detail: "A song exploring manipulation and its emotional toll.",
    url: "https://www.youtube.com/watch?v=5OYjN5ANnn4"
  },
  {
    song: "Heart of Ice",
    detail: "A song exploring the theme of emotional numbness and the struggle to open up.",
    url: "https://www.youtube.com/watch?v=K-jwbV9FRFo"
  },
  {
    song: "IDGAF",
    detail: "A song expressing a carefree attitude, featuring Blackbear.",
    url: "https://www.youtube.com/watch?v=GAMzgXWC7FY"
  },
  {
    song: "Light It Up (Home)",
    detail: "A motivational song about overcoming challenges and finding hope.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Love Lost",
    detail: "A song about the pain and longing experienced after a breakup.",
    url: "https://www.youtube.com/watch?v=64_6iDhnKIs"
  },
  {
    song: "Lost in Love (Home)",
    detail: "A song about being swept up in a whirlwind romance and feeling lost in the process.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Migraine",
    detail: "A song about the overwhelming pain of overthinking and stress.",
    url: "https://www.youtube.com/watch?v=tIxLU8WUK1Y"
  },
  {
    song: "Mirage (Home)",
    detail: "A song exploring the illusion of happiness and the disillusionment that follows.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "Out of Reach",
    detail: "A song about longing and unattainable love.",
    url: "https://www.youtube.com/watch?v=KdHcLKj4v9A"
  },
  {
    song: "Problematic",
    detail: "A song addressing flaws and challenges in relationships.",
    url: "https://www.youtube.com/watch?v=EkcGRTPnF3o"
  },
  {
    song: "Rockstar",
    detail: "A song reflecting the highs and lows of pursuing fame.",
    url: "https://www.youtube.com/watch?v=HxhFDeGKQHg"
  },
  {
    song: "Sick of U",
    detail: "A song about feeling fed up and overwhelmed with toxic relationships.",
    url: "https://www.youtube.com/watch?v=NNGd3uANaes"
  },
  {
    song: "Toxic",
    detail: "A song about the harmful effects of a toxic relationship, and the realization that it's time to let go.",
    url: "https://www.youtube.com/watch?v=Mvaosumc4hU"
  },
  {
    song: "Trauma",
    detail: "A song delving into personal struggles and emotional scars.",
    url: "https://www.youtube.com/watch?v=ASVFp5fdFnk"
  },
  {
    song: "Two Moons",
    detail: "A reflective song on finding solace and beauty in difficult times.",
    url: "https://www.youtube.com/watch?v=HHezQOZ_2xk"
  },
  {
    song: "Understand",
    detail: "A song about confusion and vulnerability in relationships, reflecting the complexity of emotions and miscommunication.",
    url: "https://www.youtube.com/watch?v=QYVz-brSsPM"
  },
  {
    song: "Unholy (Home)",
    detail: "A song about struggling with inner demons and destructive behavior.",
    url: "https://meteorfire2825.github.io"
  },
  {
    song: "You (Home)",
    detail: "A song that captures the intense emotions and vulnerability of being in love.",
    url: "https://meteorfire2825.github.io"
  }
];
```
## Code for index.html
```javascript
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BoyWithUke Songs & Interpretations</title>
    <link rel="icon" href="favicon.png">
    <style>
      body {
        background-image: url('background.png');
        background-size: cover;
        background-position: center;
        background-attachment: fixed;
        color: white;
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        overflow-x: hidden; /* Prevent horizontal scrolling */
      }
      header {
        background-color: rgba(31, 31, 31, 0.8);
        padding: 20px;
        text-align: center;
        position: relative;
      }
      header a {
        position: absolute;
        top: 10px;
        left: 10px;
      }
      header img {
        width: 200px;
        height: auto;
      }
      h1 {
        font-size: 36px;
        margin: 0;
      }
      .content {
        padding: 20px;
      }
      .title-box {
        background-color: rgba(42, 42, 42, 0.8);
        padding: 15px;
        border-radius: 8px;
        margin: 10px 0;
        width: 80%;
        margin-left: auto;
        margin-right: auto;
        text-align: center;
      }
      .song-box {
        background-color: rgba(42, 42, 42, 0.8);
        padding: 15px;
        border-radius: 8px;
        margin: 10px 0;
        width: 80%;
        margin-left: auto;
        margin-right: auto;
        cursor: pointer;
      }
      .song-title {
        font-size: 24px;
        font-weight: bold;
      }
      .interpretation {
        font-size: 16px;
        margin-top: 5px;
      }
      footer {
        background-color: rgba(31, 31, 31, 0.8);
        color: #bbb;
        text-align: center;
        padding: 10px;
        width: 100%;
        position: relative;
      }
      a {
        text-decoration: none;
        color: inherit;
      }
    </style>
  </head>
  <body>
    <header>
      <a href="https://meteorfire2825.github.io" target="_blank"><img src="logo.png" alt="Logo"></a>
      <h1>BoyWithUke Songs & Interpretations</h1>
    </header>
    <div class="content">
      <div class="title-box">
        <h2>Complete List of Songs</h2>
      </div>
      <div id="song-list"></div>
    </div>
    <footer>
      <p>&copy; 2025 BoyWithUke Songs</p>
    </footer>
    <script src="index.js"></script>
    <script>
      let html = '';
      songData.forEach(song => {
        html += `<a href="${song.url}" target="_blank">
                  <div class="song-box">
                    <div class="song-title">${song.song}</div>
                    <div class="interpretation">${song.detail}</div>
                  </div>
                </a>`;
      });
      document.getElementById('song-list').innerHTML = html;
    </script>
  </body>
</html>


```
