<html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>For You</title>

<link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;500&family=Dancing+Script:wght@500&display=swap" rel="stylesheet">

<style>

body{
margin:0;
font-family:'Poppins', sans-serif;
background:linear-gradient(135deg,#ff9a9e,#fad0c4);
height:100vh;
display:flex;
justify-content:center;
align-items:center;
}

.card{
background:white;
padding:35px;
border-radius:20px;
text-align:center;
width:300px;
box-shadow:0 10px 30px rgba(0,0,0,0.2);
}

.title{
font-family:'Pacifico', cursive;
color:#ff4b6e;
font-size:22px;
margin-bottom:20px;
}

input{
width:90%;
padding:12px;
border-radius:10px;
border:2px solid #ff8da1;
}

button{
margin-top:15px;
padding:10px 25px;
border:none;
border-radius:12px;
background:#ff4b6e;
color:white;
cursor:pointer;
}

#mainContent{
display:none;
width:100%;
height:100vh;
background:linear-gradient(135deg,#ff9a9e,#fad0c4);
padding-top:80px;
}


.letter{
background:white;
width:70%;
margin:auto;
padding:40px;
border-radius:15px;
box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

.letter h3{
font-family:'Pacifico', cursive;
color:#ff4b6e;
font-size:28px;
margin-bottom:15px;
}

.letter p{
font-family:'Dancing Script', cursive;
font-size:22px;
line-height:1.8;
color:#444;
}

#message{
display:none;
}

</style>
</head>

<body>

<div class="card" id="login">

<div class="title">Enter the secret code</div>

<input type="password" id="code">

<br>

<button onclick="checkCode()">Enter</button>

</div>

<div class="card" id="message">
<h2 style="font-family:Pacifico;color:#ff4b6e;">
welcome my baby, I hope you like it
</h2>
</div>

<div id="mainContent">

<div class="letter">

<h3>My baby</h3>

<p>
Hi baby, I hope this message finds you well. I just wanted to take a moment to let you know how much I appreciate you — your existence and the time we’ve spent getting to know each other over the past few days. Your kindness, your humor, the way you comfort me, and your intelligence have truly impressed me. I feel really grateful to have you in my life. 
<br><br>

I also want to say thank you for accepting me into your life. Even though we’re not in a relationship yet, I feel like we might get there someday. For now, we just need to continue getting to know each other. I know you still don’t know me that well, so please allow me to prove myself to you. I want to show you that not everyone leaves. I hope you can see that my intentions toward you are pure, because they truly are. I don’t want this to become something painful like what we may have experienced in the past. I’m willing to take the risks if it means having a chance to be with you in the end. I may not be the best person you’ve ever met, but I genuinely want to pursue you. I’ve never pretended about how I feel. I know you can be avoidant and that commitment may scare you sometimes, and I understand that. You don’t have to worry about it with me. I believe there’s a deep reason why you feel that way, and I’m willing to understand it. I will love every side of you — your imperfections, your insecurities, and even the parts of yourself that you think others might not accept.

<br><br>

And if the world ever feels cruel to you, always remember that you have me by your side no matter what happens. You can lean on me whenever things get heavy. I’m willing to be your kakampi through everything. You can run to me, talk to me, and share anything with me. As long as I exist, you’ll always have someone who’s here for you — someone who supports you, cares for you, and loves you. And please remember not to push yourself too hard, okay? Be gentle with yourself. You’re doing well, you’re doing great, and I’m really proud of you. 
</p>

</div>

</div>
<audio id="bgMusic" loop>
<source src="https://audio.jukehost.co.uk/IEEeBmgcBSRv8iWqg8QaB2AsOzII4HUK" type="audio/mpeg">
</audio>

<script>

function checkCode(){

var code=document.getElementById("code").value;

if(code==="baby"){

document.getElementById("login").style.display="none";
document.getElementById("message").style.display="block";

setTimeout(function(){

document.getElementById("message").style.display="none";
document.getElementById("mainContent").style.display="block";

var music=document.getElementById("bgMusic");
music.play();

},3000)

}else{

alert("Wrong code");

}
}

</script>
</body>
</html>
