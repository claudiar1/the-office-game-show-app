<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Phrase Hunter</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link href="css/styles.css" rel="stylesheet" />
    <link href="css/animate.css" rel="stylesheet" />
    <link
      href="https://fonts.googleapis.com/css?family=Montserrat"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Bitter:wght@400;700&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <div class="main-container">
      <div id="overlay" class="start">
        <img
          id="logo-image"
          src="images/phraseHunterLogo.png"
          height="auto"
          width="750"
        />
        <img id="game-over-img" width="750" />
        <h1 id="game-over-message"></h1>
        <button id="btn__reset">Start Game</button>
      </div>

      <div id="banner" class="section">
        <h2 class="header">Guess The Office Quote:</h2>
      </div>

      <div id="phrase" class="section">
        <ul></ul>
      </div>

      <div id="qwerty" class="section">
        <div class="keyrow">
          <button class="key" id="q">q</button>
          <button class="key" id="w">w</button>
          <button class="key" id="e">e</button>
          <button class="key" id="r">r</button>
          <button class="key" id="t">t</button>
          <button class="key" id="y">y</button>
          <button class="key" id="u">u</button>
          <button class="key" id="i">i</button>
          <button class="key" id="o">o</button>
          <button class="key" id="p">p</button>
        </div>

        <div class="keyrow">
          <button class="key" id="a">a</button>
          <button class="key" id="s">s</button>
          <button class="key" id="d">d</button>
          <button class="key" id="f">f</button>
          <button class="key" id="g">g</button>
          <button class="key" id="h">h</button>
          <button class="key" id="j">j</button>
          <button class="key" id="k">k</button>
          <button class="key" id="l">l</button>
        </div>

        <div class="keyrow">
          <button class="key" id="z">z</button>
          <button class="key" id="x">x</button>
          <button class="key" id="c">c</button>
          <button class="key" id="v">v</button>
          <button class="key" id="b">b</button>
          <button class="key" id="n">n</button>
          <button class="key" id="m">m</button>
        </div>
      </div>

      <div id="scoreboard" class="section">
        <ol>
          <li class="tries">
            <img
              class="heart"
              src="images/liveHeart.png"
              alt="Heart Icon"
              height="35"
              width="30"
            />
          </li>
          <li class="tries">
            <img
              class="heart"
              src="images/liveHeart.png"
              alt="Heart Icon"
              height="35"
              width="30"
            />
          </li>
          <li class="tries">
            <img
              class="heart"
              src="images/liveHeart.png"
              alt="Heart Icon"
              height="35"
              width="30"
            />
          </li>
          <li class="tries">
            <img
              class="heart"
              src="images/liveHeart.png"
              alt="Heart Icon"
              height="35"
              width="30"
            />
          </li>
          <li class="tries">
            <img
              class="heart"
              src="images/liveHeart.png"
              alt="Heart Icon"
              height="35"
              width="30"
            />
          </li>
        </ol>
      </div>
    </div>

  </body>

  <script type="text/javascript" src="js/Phrase.js"></script>
  <script type="text/javascript" src="js/Game.js"></script>
  <script type="text/javascript" src="js/app.js"></script>
</html>