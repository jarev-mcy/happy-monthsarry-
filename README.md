<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Hi my wifey</title>

  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #A47DAB;
      font-family: 'Arial', sans-serif;
    }

    .container {
      background: light violet;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      text-align: center;
    }

    h1 { 
      color: #560591; 
    }

    input {
      padding: 10px;
      border: 1px solid #b18cd1;
      border-radius: 5px;
      width: 200px;
    }

    button {
      padding: 10px 20px;
      background-color: #8b4513;
      color: #8b4513;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #8F00FF;
    }

    #love-letter {
    text-align: left;       /* easier to read */
    word-wrap: break-word;  /* prevents horizontal scroll */
    padding: 10px;          /* space inside the letter box */
}

#love-letter p {
    margin-bottom: 15px;    /* space between paragraphs */
      };
    }

    .hidden {
      display: none;
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>Login</h1>

    <form id="login-form">
      <input type="text" id="name" placeholder="Enter your name">
      <br><br>
      <button type="button" onclick="login()">Log In</button>
    </form>

<div id="love-letter" class="hidden">

<p>happy first monthsarry love</p>

<p>i cant believe its already our first monthsarry one month it's might sound small to other people, but to me?? it feels so huge because in this one month, you already change so many things in my life. my days feel brighter, my heart feel heavier with happiness, and my mind always thinking about you im sooo happy lalove that you notice my comment on your post, because if you didnt, maybe i wont even know you now. and now, look at us, here we are, celebrating our one month being together,i still can't believe it HAHAHA and i still remember the first time we talk, rye and i still together, and i cant lie, my heart was already doing some weird jumpy thing. i dont know why, but i feel like i like you na even before i understand it i was scared too HAHAHA, scared maybe i will mess it up or say something wrong, but my heart, my heart just knew and every message, every joke, every late call that still make me smile, made me fall little by little and then, that day i went on ur rant HAHAHA, total chaos, and somehow you became my safe place. my sandalan. the person i can cry to, the person i can rant to, the person i can just be me with, without hiding, without pretending and lalove, i really thankful for that because i realize, you are not just someone i like, you are someone i need someone i can trust someone i can lean on even if the world go crazy</p>

<p>also remember the first day i realize i like you? it was so weird i felt happy, nervous, scared, excited, all at the same time i tried to hide it, but i cant my heart already knows it i wanted to tell you na that time, but i just… keep pretending that i dont like u but somehow i always thinking about u, and thinking we can't be together but now, iloveeeyouuu btw looking back, i just wanna say thank you. thank you for being there, thank you for laughing with me, thank you for listening to my nonsense, thank you for becoming my person even when we far</p>

<p>lalove, i want you to know, i always here for you i will always choose you you are my priority always but if im sleepy imma sleep HAHAHA, but still thinking about you no sabit remember that  iloveeeyouuu lalove, btw lalove, lets be serious for a sec i want you to tell me what you feel not everything literally, but every thing heavy in your heart tell me what make you sad, what make you mad, what make you happy, what make your day hard because i care about you because you are my partner, my lover, my future wifey and i dont want you to hide anything from me as ur future wife even its small problem, even messy problem, even stupid problem it matters to me because its you</p>

<p>i want to be the person you lean on when you tired the person you cry to when you sad the person you run to when your world heavy dont keep things inside okay? tell me what happen, tell me who hurt you, tell me what make your heart heavy let me hold your heart let me share your pain i promise i do my best to make it lighter i promise i try to make you smile even when you dont feel like it,i promise i always choose you</p>

<p>you are my favorite notification, my favorite name to read, my favorite voice to hear, for you make my normal days special and my heavy days lighter even with distance, you make me feel loved, chosen, home. sometimes i just look at my phone and smile like idiot, then realize it's you, it's because of you always you naman eh and lalove, i cant stop thinking about our future, about how we laugh together, rant together, cry together, silly fights, inside jokes, late night talks, every little thing i want all of that with you, forever i want to make you happy, i want to be your safe place, i want to be the reason you smile even if your day bad, i want to be your everything,like you already became mine</p>

<p>happy first monthsarry love. thank you for noticing me thank you for staying, thank you for being my girl I always loveeeyouuu so much, more than these words can really say, more than i can ever type, more than i can ever show and lalove, i want more months, more years, more us.happy first monthsarry, my love lets make every month better, every day special, every moment ours</p>

</div>
    </div>
  </div>

  <script>
    function login() {
      const name = document.getElementById('name').value;

      if (name === 'princess') {
        document.getElementById('login-form').classList.add('hidden');
        document.getElementById('love-letter').classList.remove('hidden');
      } else {
        alert('Invalid name! Only princess can log in.');
      }
    }
  </script>

</body>
</html>
