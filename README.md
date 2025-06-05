<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport"
    content="width=device-widht, initial-scale=1.0">
    <title>button</title>
  </head>
  <style>
  body {
    background-image: url('sou-ni.jpg');
    background-size: cover;
    background-repeat: no-repeat;
  }
  h1 {
    font-family: 'georgia', serif;
    text-shadow: 2px 2px 1px white;
    border:1px solid white;
    width:fit-content;
    margin:auto;
    padding:5px;
    margin-bottom:15px;
    border-radius:20px;
    background: cyan;
    box-shadow: 0 0 20px #00ffff, 0 0 20px #00ffff, 0 0 40px #00ffff;
  }
    button {
      font-size: 20px;
      border:1px solid #00ffff;
      padding:7px 15px;
      border-radius: 20%;
      box-shadow:
         0 0 10px #00ffff,
         0 0 10px #00f0ff,
         0 0 20px #00ffff;
      cursor:pointer;
      background:cyan;
      
    }
    button:hover {
      background-color:purple;
      box-shadow: 0 0 10px purple, 0 0 10px purple;
      border: 1px solid purple;
    }
    button:active {
      transform: scale(0.9);
    }
    .pod {
      text-align: center;
      color: grey;
      font-size: 14px;
    }
    p {
      text-align: left;
      padding:6px;
      line-height: 25px;
      font-family: 'Georgia', serif;
      font-size:17px;
      color:black;
      text-shadow: 0.5px 0.5px 0px white;
    }
    hr {
  border: none;
  height: 2px;
  background: linear-gradient(to right, #fff, #abcc, #fff);
  margin: 30px 0;
}
.nu-ni {
  height:50vh;
  justify-content: center;
  align-items: center;
  object-fit: cover;
  display: flex;
  border:1px solid white;
  width:335px;
  box-shadow:0 0 20px blue, 0 0 20px blue, 0 0 20px cyan;
}
  </style>
  <body>
    <h1 style="text-align:center;">HELLO WORLD</h1>
   <div style="display: flex; justify-content: center;">
   <button onclick="location.href='website.html'">CLICK</button>
   </div>
    <hr>
    <p>My first experience with HTML and CSS was both exciting and challenging. I was thrilled to learn about the basic structure of a web page, including headings, paragraphs, images, and links, and how to style them with CSS. As I progressed, I discovered the power of CSS and how it could transform a plain HTML page into a beautiful and responsive website. With each problem I solved, I felt a sense of accomplishment and grew more confident in my abilities, and I knew that I was just scratching the surface of what was possible with web development.</p>
    <hr>
    <p>As I continue to explore more advanced concepts like layouts, flexbox, and responsive design, I realize how much potential there is in front-end development. Building projects from scratch not only helps me understand the theory, but also gives me the confidence to face real-world challenges. I’m excited to keep learning, improve my skills, and one day create websites and apps that people all over the world can use and enjoy.</p>
    <hr>
    <img src="bo-ni.jpg" class="nu-ni">
    <hr>
    <p class="pod">©2025:faizul ibnu:hak cipta </p>
  </body>
</html>
