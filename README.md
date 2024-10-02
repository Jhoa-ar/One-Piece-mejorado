# One-Piece-mejorado
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>ONE PIECE</title>
    <style>
      * {
        margin: 0;
      }
      body {
          background: linear-gradient(to right, rgba(68, 68, 68, 0.8), rgba(255, 0, 0, 0.5));
        color: rgb(235, 213, 197);
      }
      header {
        display: flex;
        width: 90%;
        height: 20vh;
        margin-top: 50px;
        align-items: center;
        font-family: Monaco;
        padding-top: 5px;
      }

      header h1 {
        text-align: center;
        color: #FFF3E0;
        font-size: 60px;
      }

      nav {
        position: absolute;
        right: 50px;
      }
      nav a {
        color: #333;
        font-size: 25px;
        text-decoration: none;
        font-weight: 600;
        margin-left: 60px;
        transition: color 1s;
        /*text-transform: uppercase;*/
      }
      nav a:hover {
        color: #e85860;
        font-size: 30px;
      }
      .logo {
        margin: 25px;
        width: 20%;
        height: 155px;
        float: left;
        padding-left: 5px;
        cursor: pointer;
      }
      .caja {
        background-color: rgb(44, 47, 48);
        padding: 20px;
        margin: 10px;
      }
      h2 {
        font-size: 30px;
        color: #E57373 ;
        font-family: revert;
        transition: color 1s;
      }
      p {
        padding-top: 10px;
        padding-bottom: 5px;
        text-align: justify;
        font-size: 30px;
        color: #FAFAFA;
      }
      .pie {
        background-color: rgb(225, 190, 231);
        margin: 10px;
        padding: 10px;
        font-size: 12px;
        font-weight: 800;
        font-family: monospace;
        color: #17202A;
      }
      .center {
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 50%;
        margin-top: 10px;
        margin-bottom: 10px;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">
        <img src="one2p.png" alt="" />
      </div>
      <h1>ONE PIECE</h1>
      <nav>
        <a href="#ini">INICIO</a>
        <a href="#per">PERSONAJES</a>
        <a href="#tra">TRAILER</a>
      </nav>
    </header>
    <section class="caja">
      <article>
        <a id="ini"></a>
        <h2>INICIO</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
      </article>
      <article>
        <a id="per"></a>
        <h2>PERSONAJES</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
        <img src="lufy.webp" alt="" class="center" />
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
      </article>
      <article>
        <a id="tra"></a>
        <h2>TRAILER</h2>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
        <iframe
          width="453"
          height="280"
          src="https://www.youtube.com/embed/sSovEWQGTwg"
          title="One Piece: La Historia de LUFFY 🔶 | La vida de Monkey D. Luffy: Parte 1"
          frameborder="0"
          allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
          allowfullscreen
          class="center"
        ></iframe>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
        <p>
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quis
          reprehenderit laboriosam in minima deserunt, similique illum nobis,
          ipsam laborum debitis repellendus, velit hic perspiciatis tenetur
          architecto dolores eveniet. Pariatur, eos!
        </p>
      </article>
    </section>
    <footer class="pie">
      <p>DERECHOS RESERVADOS</p>
    </footer>
  </body>
</html>
