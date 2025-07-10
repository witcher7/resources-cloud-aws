**IF YOU ARE USING UBUNTU** 
---
sudo -i
---
apt-get update
---
apt install nginx -y
> now go to html folder
> cd /var/www/html
> rm -rf *
> nano index.html
** there copy and paste the below code**

**IF YOU ARE USING AMAZON LINUX**
---
sudo -i
---
yum update 
---
yum install httpd
---
service httpd start
> now go to html folder
> cd /var/www/html
> rm -rf *
> nano index.html
** there copy and paste the below code**


### PEPPA PIG
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Welcome to Peppa's Playground!</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background-color: #fff0f5;
      color: #ff69b4;
    }

    header {
      background-color: #ffe4ea;
      text-align: center;
      padding: 2rem 1rem;
      border-bottom: 5px dotted #ffb6c1;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
    }

    .peppa-img {
      width: 120px;
      border-radius: 50%;
      margin-top: 1rem;
    }

    main {
      padding: 2rem;
      max-width: 800px;
      margin: auto;
      text-align: center;
    }

    section {
      background-color: #fff;
      border: 3px dashed #ff69b4;
      border-radius: 20px;
      padding: 1.5rem;
      margin-bottom: 2rem;
    }

    h2 {
      font-size: 2rem;
      color: #d147a3;
    }

    footer {
      background-color: #ffe4ea;
      text-align: center;
      padding: 1rem;
      font-size: 1rem;
      color: #d147a3;
      border-top: 5px dotted #ffb6c1;
    }

    .button {
      background-color: #ff69b4;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 15px;
      font-size: 1.2rem;
      cursor: pointer;
      margin-top: 1rem;
    }

    .button:hover {
      background-color: #ff85c1;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Peppa's Playground!</h1>
    <img class="peppa-img" src="https://upload.wikimedia.org/wikipedia/en/8/88/Peppa_Pig_character.png" alt="Peppa Pig" />
  </header>

  <main>
    <section>
      <h2>✨ Fun Learning with Peppa!</h2>
      <p>Join Peppa and her friends in learning ABCs, numbers, colors, and more through games and fun activities!</p>
      <button class="button">Start Learning</button>
    </section>

    <section>
      <h2>🎨 Peppa's Coloring Corner</h2>
      <p>Download coloring sheets and bring Peppa's world to life with your favorite colors!</p>
      <button class="button">Download Sheets</button>
    </section>

    <section>
      <h2>📚 Story Time with Peppa</h2>
      <p>Listen to cute bedtime stories and explore the adventures of Peppa and George!</p>
      <button class="button">Listen Now</button>
    </section>
  </main>

  <footer>
    © 2025 Peppa's Playground | Made with 💗 for kids
  </footer>

</body>
</html>
```
### RED HULK
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Red Hulk's Power Zone</title>
  <style>
    body {
      margin: 0;
      font-family: 'Bangers', cursive, sans-serif;
      background-color: #1a0000;
      color: #ff4c4c;
    }

    @import url('https://fonts.googleapis.com/css2?family=Bangers&display=swap');

    header {
      background-color: #330000;
      text-align: center;
      padding: 2rem 1rem;
      border-bottom: 5px solid #ff1a1a;
    }

    header h1 {
      font-size: 3.5rem;
      margin: 0;
      color: #ff1a1a;
      letter-spacing: 2px;
    }

    .hulk-img {
      width: 160px;
      border-radius: 10px;
      margin-top: 1rem;
    }

    main {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
      text-align: center;
    }

    section {
      background-color: #260000;
      border: 3px solid #ff1a1a;
      border-radius: 15px;
      padding: 1.5rem;
      margin-bottom: 2rem;
      box-shadow: 0 0 15px rgba(255, 0, 0, 0.4);
    }

    h2 {
      font-size: 2.5rem;
      color: #ff3333;
    }

    footer {
      background-color: #330000;
      text-align: center;
      padding: 1rem;
      font-size: 1rem;
      color: #ff4c4c;
      border-top: 5px solid #ff1a1a;
    }

    .button {
      background-color: #ff1a1a;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 10px;
      font-size: 1.2rem;
      font-weight: bold;
      cursor: pointer;
      margin-top: 1rem;
      transition: background 0.3s ease;
    }

    .button:hover {
      background-color: #ff4d4d;
    }
  </style>
</head>
<body>

  <header>
    <h1>Red Hulk's Power Zone</h1>
    <img class="hulk-img" src="https://static.wikia.nocookie.net/marveldatabase/images/e/e0/Thunderbolt_Ross_%28Earth-616%29_from_Hulk_Vol_2_23_001.png" alt="Red Hulk" />
  </header>

  <main>
    <section>
      <h2>💪 Unleash the Rage</h2>
      <p>Explore Red Hulk's story, strength, and battles across the Marvel Universe. Power up and smash through limits!</p>
      <button class="button">Learn His Story</button>
    </section>

    <section>
      <h2>🔥 Hulk Smash Challenge</h2>
      <p>Play the Red Hulk mini-game and test your reaction speed and power punches!</p>
      <button class="button">Play Now</button>
    </section>

    <section>
      <h2>🎨 Red Hulk Fan Art</h2>
      <p>Submit your own Hulk-themed drawings and view epic artwork by other fans.</p>
      <button class="button">Submit Art</button>
    </section>
  </main>

  <footer>
    © 2025 Red Hulk Zone | Power for the Strong 💥
  </footer>

</body>
</html>

```
### DORAEMON
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Doraemon's Fun World</title>
  <style>
    body {
      margin: 0;
      font-family: 'Comic Sans MS', cursive, sans-serif;
      background-color: #e0f7ff;
      color: #0066cc;
    }

    header {
      background-color: #b3e5fc;
      text-align: center;
      padding: 2rem 1rem;
      border-bottom: 4px dashed #03a9f4;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
      color: #01579b;
    }

    .main-img {
      width: 150px;
      margin-top: 1rem;
      border-radius: 10px;
    }

    main {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
      text-align: center;
    }

    section {
      background-color: #ffffff;
      border: 3px solid #81d4fa;
      border-radius: 20px;
      padding: 1.5rem;
      margin-bottom: 2rem;
      box-shadow: 0 0 10px rgba(0,0,255,0.1);
    }

    h2 {
      font-size: 2rem;
      color: #0288d1;
    }

    .button {
      background-color: #03a9f4;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 15px;
      font-size: 1rem;
      cursor: pointer;
      margin-top: 1rem;
    }

    .button:hover {
      background-color: #4fc3f7;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      justify-content: center;
      margin-top: 1rem;
    }

    .gallery img {
      width: 180px;
      height: auto;
      border-radius: 10px;
      border: 2px solid #03a9f4;
      transition: transform 0.2s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      background-color: #b3e5fc;
      text-align: center;
      padding: 1rem;
      font-size: 1rem;
      color: #01579b;
      border-top: 4px dashed #03a9f4;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to Doraemon's Fun World!</h1>
    <img class="main-img" src="https://upload.wikimedia.org/wikipedia/en/0/05/Doraemon_character.png" alt="Doraemon" />
  </header>

  <main>
    <section>
      <h2>🧳 Doraemon's Gadgets</h2>
      <p>Discover the coolest gadgets from Doraemon's pocket — from Anywhere Door to Time Machine!</p>
      <button class="button">Explore Gadgets</button>
    </section>

    <section>
      <h2>📷 Doraemon Gallery</h2>
      <p>Check out cute and funny moments from Doraemon's adventures!</p>
      <div class="gallery">
        <img src="https://static.wikia.nocookie.net/doraemon/images/6/6a/Doraemon.png" alt="Doraemon Pose" />
        <img src="https://static.wikia.nocookie.net/doraemon/images/f/f0/Doraemon_with_Bamboo-Copter.png" alt="Doraemon Flying" />
        <img src="https://static.wikia.nocookie.net/doraemon/images/0/0f/Doraemon_Gadgets.png" alt="Gadgets" />
        <img src="https://static.wikia.nocookie.net/doraemon/images/f/f1/Doraemon_Face.png" alt="Close-up Doraemon" />
      </div>
    </section>

    <section>
      <h2>🎮 Doraemon Games</h2>
      <p>Play fun Doraemon games and puzzles with your friends.</p>
      <button class="button">Play Now</button>
    </section>
  </main>

  <footer>
    © 2025 Doraemon Fun World | Made with 💙 for fans everywhere
  </footer>

</body>
</html>

```

