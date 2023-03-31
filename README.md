<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />

    <title>Clear Valley Window Cleaning</title>

    <style>
      body {
        background-image: url("https://upload.wikimedia.org/wikipedia/commons/0/0a/Newlands_-_geograph.org.uk_-_283875.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
        background-attachment: fixed;
      }
      .container:before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        right: 0;
        bottom: 0;
        width: 1500px;
        box-shadow: inset 0 0 2000px rgba(255, 255, 255, 0.5);
        filter: blur(10px);
        background: inherit;
      }

      .container {
        background: inherit;
        position: relative;
        width: 500px;
        height: 500px;
      }
      #logo {
        width: 300px;
        filter: transparent(5px);
        border: 3px solid black;
        border-radius: 50%;
        z-index: 1;
      }

      /*
            #window {
              background-color: rgb(218, 226, 245);
              filter: blur(50px);
              z-index: 0;
              width: 1000px;
              height: 500px;
              position: absolute;
              top: 500px;
              left: 0px;
            }
      */

      #slogan {
        font-family: Cambria, Cochin, Georgia, Times, "Times New Roman", serif;
        font-size: 25px;
        margin-left: 40px;
        color: white;
      }
    </style>
  </head>

  <body>
    <img id="logo" src="images/clear_valley.jpeg" alt="Company logo" />

    <p id="slogan">
      Satisfaction guaranteed
    </p>
    /*
    <div id="window"></div>
    */

    <div class="container"></div>
  </body>
</html>
