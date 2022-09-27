# google1998
Google'ın ilk versiyon çalışmam.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google</title>
    <link rel="stylesheet" href="style.css">
</head>



  
<body>
    <main>
        <img src="https://web.archive.org/web/19990504112211im_/http://www.google.com/google.jpg" alt="logo">
        <div class="gy-0">
            <span> Search the web using Google!</span>
            <input type="text" size="40">
            <Button>Google Search</Button>
            <Button>I'm feeling lucky</Button>
        </div>
        <div id="links">
            <div class="g-1">
                <div class="alt">
                    <span>Special Searches</span>
                    <a href="#">Stanford Search</a>
                    <a href="#">Linux Search</a>
                </div>
            </div>
            <div class="g-2">
                <a href="#" class="alt-1">Help!</a>
                <a href="#">About Google!</a>
                <a href="#">Company Info</a>
                <a href="#">Google! Logos</a>
            </div>
            <div class="g-3">
                <span>Get Google!</span>
                <span>updates monthly:</span>
                <input type="text" value="your e-mail">
                <Button>Subscribe</Button>
                <a href="#" style="display:inline;margin-left:9px;">
                    Archive</a>
            </div>
        </div>
    </main>
    <footer>Copyright ©1998 Google Inc.</footer>
</body>

</html>
*:not(input) {
    text-align: center;
  
  }
  main {
    width: 90%;
    margin: 0 auto 18px;
  }
  .gy-0 {
    background-color: #eeeeee;
    height: 61px;
  }
  .g-1 {
      background-color: #7ee5da;
      height: 75px;
  }
  .g-2 {
    background-color: #70ccc2;
    font-size: 13px;
    height: 75px;
  }
  .g-3 {
    background-color: #62b3aa;
    font-size: 13px;
  }
  #links {
    display: grid;
    grid-template-columns: 17fr 9fr 20fr;
    gap: 2px;
  }
  main div > *:not(Button) {
    display: block;
  }
  main > div {
    margin-bottom: 2px;
  }
  input {
    margin: 0 auto;
  }
  footer {
    margin-top: 1em;
    font-size: 13px;
  }
  .alt {
      margin-top:10px
  }
  .alt-1 {
      margin-top:5px
  }
  
