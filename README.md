<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Explications Linéaires</title>

    <link
      href="https://fonts.googleapis.com/css2?family=Carter+One&family=Kanit:wght@300&family=Madimi+One&display=swap"
      rel="stylesheet"
    />

    <style>
      body {
        font-family: "Kanit", sans-serif;
        background-color: #f5f5f5;
        margin: 0;
        padding: 0;
        box-sizing: border-box;
      }

      .header {
        text-align: center;
        padding: 20px;
        background-color: #333;
        color: white;
        font-family: "Madimi One", cursive;
        border-bottom: 3px solid black;
      }

      .container {
        width: 80%;
        margin: 20px auto;
        display: flex;
        flex-direction: column;
        align-items: center;
      }

      .explic {
        background-color: white;
        border: 2px solid #333;
        padding: 20px;
        margin-bottom: 20px;
        width: 80%;
        text-align: center;
        transition: transform 0.3s ease;
      }

      .explic:hover {
        transform: translateY(-5px);
      }

      button {
        cursor: pointer;
        font-family: "Kanit", sans-serif;
        font-weight: 600;
        font-size: 16px;
        padding: 10px 20px;
        background-color: #bdbdbd;
        color: rgb(0, 0, 0);
        border: none;
        border-radius: 5px;
        transition: background-color 0.3s ease;
      }

      h4 {
        color: #000000;
        font-family: "Carter One", cursive;
        font-size: 18px;
        margin: 10px 0;
      }
    </style>
  </head>
  <body>
    <div class="header">
      <h1>Explications Linéaires de la classe 1-G2</h1>
    </div>

    <div class="container">
      <div class="explic">
        <button onclick="toPage(1)">
          <h4>
            Explication Linéaire 1 : Voltaire, Candide, « Le nègre de Surinam »,
            1759.
          </h4>
        </button>
      </div>

      <div class="explic">
        <button onclick="toPage(2)">
          <h4>
            Explication Linéaire 2 : Olympe de Gouges, DDFC, « Hommes, es – tu
            capable d’être juste ? », 1791.
          </h4>
        </button>
      </div>

      <div class="explic">
        <button onclick="toPage(3)">
          <h4>
            Explication Linéaire 3 : Olympe de Gouges, DDFC, Postambule, du
            début à « vous n'avez qu'à le vouloir.», 1791.
          </h4>
        </button>
      </div>

      <div class="explic">
        <button onclick="toPage(4)">
          <h4>
            Explication Linéaire 4 : Postambule, de « Les femmes ont fait » à «
            nous serions toujours corrompus. », 1791.
          </h4>
        </button>
      </div>

      <div class="explic">
        <button onclick="toPage(5)">
          <h4>
            Explication Linéaire 5 : Abbé Prévost, Manon Lescaut, La scène de
            rencontre, 1753.
          </h4>
        </button>
      </div>

      <div class="explic">
        <button onclick="toPage(6)">
          <h4>
            Explication Linéaire 6 : Abbé Prévost, Manon Lescaut, La scène de
            retrouvailles, 1753.
          </h4>
        </button>
      </div>

      <div class="explic">
        <button onclick="toPage(7)">
          <h4>
            Explication Linéaire 7 : Abbé Prévost, Manon Lescaut, L'évasion de St-Lazare, 1753.
          </h4>
        </button>
      </div>
    </div>

    <script>
      function toPage(page) {
        // Redirection vers une autre page
        switch (page) {
          case 1:
            window.location.href = "explilineaire1.html";
            break;
          case 2:
            window.location.href = "explilineaire2.html";
            break;
          default:
            window.location.href = "accueil.html";
        }
      }
    </script>
  </body>
</html>
