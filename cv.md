# Egor Krasnik

### Junior Frontend Developer

---

### Contact information:

Phone: +375(29) 172 7632

E-mail: egorkrfsnik@gmail.com

Telegram: https://t.me/KupalaNight

GitHub: github.com/kupalanight [https://github.com/kupalanight]

---

### Briefly About Myself: 
Hi! I’m a junior frontend developer. I want to upgrade my skills. Now I'm taking exams at the Linguistic University. In a future i’d like to work in strong team width the extraordinary prodjects. I'd like do beautiful interactive cites.

---

### Skills and Proficiency:
+ HTML5, CSS3
+ JavaScript Basics
+ Git, GitHub
+ VS Code

---

### Working on a school project
Participated in the project "Techno-intellect" at school. Developed a website dedicated to the culture of Belarus(https://kupalanight.github.io/culture/!Культура/Культура.html)

---

### Code example:

This is the code for my school project. This is music player.
```JavaScript
// Update song details
function loadSong(song) {
    title.innerText = song
    audio.src = `audio/${song}.mp3`
    cover.src = `img/${song}.jpg`
}

function playSong() {
    musicContainer.classList.add('play')
    playBtn.querySelector('i.fas').classList.remove('fa-play')
    playBtn.querySelector('i.fas').classList.add('fa-pause')

    audio.play()
}

function pauseSong () {
    musicContainer.classList.remove('play')
    playBtn.querySelector('i.fas').classList.add('fa-play')
    playBtn.querySelector('i.fas').classList.remove('fa-pause')

    audio.pause()
}

function prevSong() {
    songIndex--

    if(songIndex < 0) {
        songIndex = songs.length - 1
    }

    loadSong (songs[songIndex])

    playSong()
}

function nextSong() {
    songIndex++

    if(songIndex > songs.length - 1) {
        songIndex = 0
    }

    loadSong (songs[songIndex])

    playSong()
}

function updateProgress (e) {
    const {duration, currentTime} = e.srcElement
    const progressPercent = (currentTime / duration) * 100
    progress.style.width = `${progressPercent}%`
}

function setProgress(e) {
    const width = this.clientWidth
    const clickX = e.offsetX
    const duration = audio.duration

    audio.currentTime = (clickX / width) * duration
}

```
---

### Languages:
+ English
+ Russian - Native
+ Polish - Basic
