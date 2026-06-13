const text =
"🎂 Selamat Ulang Tahun ke-4 ZOYA KHAIRUNNISA 🎂";

let i=0;

function typing(){
if(i<text.length){
document.getElementById("typing").innerHTML+=text.charAt(i);
i++;
setTimeout(typing,80);
}
}

typing();

const birthday =
new Date("June 25, 2026 00:00:00").getTime();

setInterval(()=>{

const now=new Date().getTime();

const distance=birthday-now;

document.getElementById("days").innerHTML=
Math.floor(distance/(1000*60*60*24));

document.getElementById("hours").innerHTML=
Math.floor((distance%(1000*60*60*24))/(1000*60*60));

document.getElementById("minutes").innerHTML=
Math.floor((distance%(1000*60*60))/(1000*60));

document.getElementById("seconds").innerHTML=
Math.floor((distance%(1000*60))/1000);

},1000);

let slides =
document.querySelectorAll(".slide");

let current=0;

setInterval(()=>{
slides[current].classList.remove("active");
current=(current+1)%slides.length;
slides[current].classList.add("active");
},3000);

document.querySelector(".card")
.addEventListener("click",()=>{
document.querySelector(".card")
.classList.toggle("open");
});

document.getElementById("secretBtn")
.addEventListener("click",()=>{
const msg=document.getElementById("secretMessage");

msg.style.display=
msg.style.display==="block"
? "none"
: "block";
});

const song=document.getElementById("song");

document.getElementById("musicBtn")
.addEventListener("click",()=>{
song.play();
});
