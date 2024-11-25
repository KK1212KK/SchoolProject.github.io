<!DOCTYPE html>
<html>


                                       <style>
       body {

    background-color: #000;
       }

     p {
         color: white;
     }
     h1 {
         color: white;
     }
       h5 {
           color: white;
       }
        ol {
            color: white;
        }
        .bar {

              transform: scale(1.5);
        }

        .TabButtons {


  position: absolute;
  top: 50%;
  left: 50%;

  transform: translate(-50%, -50%);
}

 .Back {


  position: absolute;
  top: 98%;
  left: 50%;

  transform: translate(-50%, -50%);
}
.Back button:hover {
  cursor: pointer;
}

.Lnk button:hover {
 cursor: pointer;
}




             .strt
        {

       cursor: pointer;
        }

             .BtnStart:active{
  display: block;
}


    </style>
    <script>
      window.onload = function Hide() {
          var mText = document.getElementById("MainText");
          var r = document.getElementById("Reflect");
          var Stabs = document.getElementById("Switch");


          mText.style.display = "none";
          Stabs.style.display = "none";
          r.style.display = "none";



      }
    </script>


 <body>

  <div class="TabButtons" id="TabButtons">

<button id="TabButton1" class="strt" onclick="SwitchToId('MainText')">The Movie</button>
<button id="TabButton2" class="strt" onclick="SwitchToId('Reflect')">My Reflection</button>
</div>

           <div id="MainText">
<h1 style="text-align: center;">The movie</h1>
    <p class="bar" style="text-align: center; font-size: 1px;">EEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEEE</p>

        <h5>Topic: Sonic movie 3
Audience: People waiting for Sonic 3
Purpose: To inform about the up and coming third sonic movie</h5>
<p style="font-size: 18px; text-align: center;">
This will be about the up and coming third sonic movie,
it is coming out this december and i am very excited about it. From
what we know, it is about team Sonic (Sonic, Tails, and knuckles)
meeting Shadow after he breaks out of containment, Shadow trys to
destroy everything and team sonic has to stop him.</p>

<h5>Key Points that seem to be in the movie</h5>
<ol>
    <li>Shadow is a being that calls himself "The Ultimate Lifeform" In other sonic media. He breaks out of what seems to be known as "Prison Island"</li>
    <li>The movie seems to be following more of a Sonic X story line, shown by maria in the trailer.</li>
    <li>The assumtion that the island that Shadow is contained on is called "Prison Island" Comes from Sonic X's Prison Island.</li>
</ol>
<img src="https://i.ebayimg.com/images/g/EhwAAOSw5mpmzfPX/s-l1200.jpg" jsaction="" class="sFlh5c FyHeAf iPVvYb" style="max-width: 809px; height: 399px; margin: 0px; width: 269px;" alt="Sonic The Hedgehog 3 2024 Movie PREMIUM POSTER MADE IN USA - LAS330 | eBay" jsname="kn3ccd" aria-hidden="false">
<img src="https://upload.wikimedia.org/wikipedia/en/f/f2/Sonic_the_Hedgehog_3_film_poster.jpg" jsaction="" class="sFlh5c FyHeAf iPVvYb" style="max-width: 809px; height: 399px; margin: 0px; width: 269px;" alt="Sonic the Hedgehog 3 (film) - Wikipedia" jsname="kn3ccd" aria-hidden="false">
<p>At the time of writing the statement above, there was only one trailer, so ill link both of them here</p>
<div class="LinkBtns">
</div>
<a href="https://www.youtube.com/watch?v=qSu6i2iFMO0">
    <button class="Lnk">Sonic 3 Trailer 1</button>
</a>
<a href="https://www.youtube.com/watch?v=LH1J1EbqCaI">
<button class="Lnk">Sonic 3 Trailer 2</button>
</a>
</div>
<div id="Reflect">
 <h1 style="text-align: center;">My reflection and problems</h1>
 <p>Firstly, this was very challenging and I loved it, mostly (we will get to that) I learned a lot from this. Now to the problems. <br> First problem I had was with the switch buttons, they didnt want to show the text no matter what. I spent 2 hours just to realize i forgot a semi-colon. The second big problem took me 5 days. i accidently used double quotes and it broke my script. heres what i did: onclick="SwitchToId("MainText")" The quotes didnt work because i put two. I shouldve made it like this onclick="SwitchToId('MainText')" Thats really all for the reflection</p>
</div>
<div class="Back">
<button id="Switch" text-align: bottom; onclick="SwitchToId('TabButtons')">Switch Tab</button>
</div>

 </body>

    <script>
       function SwitchToId(id) {
          var mText = document.getElementById("MainText");
          var r = document.getElementById("Reflect");
          var Stabs = document.getElementById("Switch");
          var x = document.getElementById("TabButtons");

          x.style.display = "none";
          mText.style.display = "none";
          r.style.display = "none";

          document.getElementById(id).style.display = "block"
          if (id === 'TabButtons') {
               Stabs.style.display = "none";
          } else {
               Stabs.style.display = "block";
          }



      }

    </script>




</html>
