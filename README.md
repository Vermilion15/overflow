<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        :root {
            --color-primary-dark: darkblue;
        }
       .text-overflow {
        width: 5rem;
        text-overflow: clip;
        overflow: hidden;
        white-space: nowrap;
       }
       h1 {
        color: var(--color-primary-dark);
       }
       h2 {
        color: saddlebrown
       }
       .parent {
        width:80vw;
        height: 50vh;
        border: 5px solid var(--color-primary-dark);
       }
       .box {
        display: grid;
        align-items: center;
        justify-content: center;
        border: 2px solid saddlebrown;
        aspect-ratio: 3/1;
       }
       .auto-grid {
        display: grid;
        grid-template-columns: repeat(1,30vw 30vw 30vw);
       }
       main {
        width: 100%;
        text-align: center;
        text-align: -webkit-center;
}
        .parent {
          overflow-x: scroll;
          overflow-y: scroll;
        }

    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>overflow</title>
</head>
<body>
   <p class="text-overflow">This text is overflow</p>
   <main>
    <h1>parent</h1>
    <div class="parent">
      <div class="auto-grid">
      <div class="box">
        <h2>child</h2>
      </div>
      <div class="box">
        <h2>child</h2>
      </div>
      <div class="box">
        <h2>child</h2>
      </div>
      <div class="box">
        <h2>child</h2>
      </div>
      <div class="box">
        <h2>child</h2>
      </div>
      <div class="box">
        <h2>child</h2>
      </div>
      <div class="box">
        <h2>child</h2>
      </div>
      <div class="box">
        <h2>child</h2>
      </div>
      <div class="box">
        <h2>child</h2>
      </div>
    </div>
  </main>

</body>
</html>
