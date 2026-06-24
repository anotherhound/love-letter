<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Bebi ❤️</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Georgia', serif;
}

body{
    min-height:100vh;
    background:linear-gradient(135deg,#ff9a9e,#fad0c4);
    display:flex;
    justify-content:center;
    align-items:center;
    overflow:hidden;
}

.hearts{
    position:fixed;
    width:100%;
    height:100%;
    top:0;
    left:0;
    pointer-events:none;
}

.heart{
    position:absolute;
    color:white;
    font-size:20px;
    animation:float 8s linear infinite;
}

@keyframes float{
    from{
        transform:translateY(100vh);
        opacity:0;
    }
    20%{opacity:1;}
    to{
        transform:translateY(-120px);
        opacity:0;
    }
}

.container{
    text-align:center;
    padding:20px;
}

.card{
    background:rgba(255,255,255,0.95);
    max-width:850px;
    padding:40px;
    border-radius:25px;
    box-shadow:0 10px 40px rgba(0,0,0,0.2);
    backdrop-filter:blur(10px);
}

h1{
    color:#ff4d6d;
    margin-bottom:15px;
}

button{
    margin-top:20px;
    padding:15px 30px;
    border:none;
    border-radius:50px;
    background:#ff4d6d;
    color:white;
    font-size:18px;
    cursor:pointer;
    transition:0.3s;
}

button:hover{
    transform:scale(1.05);
}

.letter{
    display:none;
    text-align:left;
    margin-top:30px;
    line-height:1.9;
    color:#333;
    animation:fadeIn 1s ease;
    white-space:pre-wrap;
}

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

.signature{
    margin-top:40px;
    font-style:italic;
}
</style>
</head>
<body>

<div class="hearts" id="hearts"></div>

<div class="container">
    <div class="card">
        <h1>To: Shibi </h1>
    

        <button onclick="showLetter()">Open Letter 💌</button>

        <div class="letter" id="letter">

Hello,

I know this isnt like me doing something like this pero I think this problem has been going on for a few weeks already na and I think its about time that we should finally both decide kung san pa ba pupunta to kasiii nga,















I COULDNT HANDLE IT ANYMOREEEEEEEEEEEEEEEEEEEEEEEE!!!

I WANT MY BEBI BACKKKKK PLS!

I FKING MISS MY BEBI ALREADY I COULDNT EVEN EAT OR SLEEP PROPERLY THESE DAYS (I think you also).

I MISS EVERYTHING ABOUT MY BEBI AND I MISS KUNG WHATEVER ANO MERON TAYO.

Im probably just putting a face lang na it looks like doesnt bother me much pero deep inside its just you know.... lalo na when you already blocked me (well it was definitely my fault ass for joking like that) and that was the part where all hope was lost in me and I couldnt even control my thoughts for so long..

I opened up to ate luna not sure if she said everything about it to you pero I was desperately looking for answers na since I never open up about anything to others and just handle it everything on my own.....

aand thats where I learned everything kung ano ba pagkukulang ko sayo lahat lahat and nag sink in siya kasi totoo naman narealize ko na din na I was really the one behind this whole thing and it was everything my fault I really feel so bad kasi para akong kakampi kita pero para akong kalaban eh.

especially the part where you already blocked me na (I didnt know what the hell was going on there not until I spoke it with ate luna big thanks to her and I owe her one).

Going back...

since namimiss na talaga kita I checked the email where you sent me before since I remember something yung part where I was accepted to be your boyfriend there was a part there saying na:

"You've shown potential in key areas like cuddling, emotional support, spontaneous date ideas, and being my safe space."

and it seems na I have failed on those parts already and im probably no longer your safe space anymore and its really what was going on around here...

and since theres this part also where it says:

"No returns. No exchanges. Absolutely no take backs."

So basically, im not letting you get rid of me.

Ill do my best to make my bebi's safe space and emotional support back again, and since I've got the role of a lifetime then lets make it real.

I love youu so muchh bebi and no other words can express what I feel.

Ill wait for your response
(I wont accept no for an answer btw ❤️)

<div class="signature">
Love,<br><br>
Yung dumi sa gilid ng basurahan
</div>

        </div>
    </div>
</div>

<script>
function showLetter(){
    document.getElementById('letter').style.display='block';
}

function createHeart(){
    const heart=document.createElement('div');
    heart.classList.add('heart');
    heart.innerHTML='❤';
    heart.style.left=Math.random()*100+'vw';
    heart.style.fontSize=(Math.random()*20+15)+'px';
    heart.style.animationDuration=(Math.random()*5+5)+'s';

    document.getElementById('hearts').appendChild(heart);

    setTimeout(()=>{
        heart.remove();
    },10000);
}

setInterval(createHeart,300);
</script>

</body>
</html>