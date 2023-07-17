# Audio Video Elements.

---

audio,
video,
img{
margin:2rem 0;
}

Adding audio to html

audio element: <audio src="file path goes here"></audio>
_file formats can be added into the audio element by using the source element._

<audio src="file path goes here" controls></audio>
"controls" adds visual representation onto the screen . (adds play/pause/mute/progress bar)
"muted" sets music to mute.
"autoplay" frowned apon.
"loop" replays audio
volume : 1.0 loudest

_can us javascript_

declare variable called audio

const audio = document.querySelector("audio")
audio.play();

<!-- query selector :selects first element of specific type. -->

const levees = document.getElementById("leeves");
levees.play();

document.getElementById("randomizer").addEventListener("click",function(){
leeves.volume = Math.random()
console.log(levees.volume);
});

---

# video

<video src="file path" width="400", height="600" muted controls></video>

grid{

    display:grid;
    grid-template-columns: 3fr 1fr 3fr;
    <!-- fr stands for fraction -->
    width:1024px
    margin: 3rem auto;

}

.grid section:nth-child(2){
grid-column-start: 3
}

---

main{

    width: 1024px;;
    margin 3rem auto;
    display:grid;
    gtc: 250px 4fr;
    gtr: 6.5rem 10rem 20rem 40%;

}

#siteLogo {
width250px;
z-index:2;
grid-row-start:1;

}
