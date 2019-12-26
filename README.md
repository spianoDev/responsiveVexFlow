# responsiveVexFlow
A quick start guide to setting up a dynamic use of the VexFlow API.

## This repo is part of a series of tutorials.

### Navigation is set to the side with the clickable links moving you down the page through the tutorial
screen shot of nav bar
![Nav Example]() 

### Code snippets are highlighted in blue for easy copy/paste
code example
![Code Example]() 

typical presentation of code in README.md

```
function writeNote(pitch, rhythm){
    document.getElementById('score');
// add additional if statements to include more rhythmic options
    if (rhythm === '/8') {
        score.set({time: "1/8"})
    } else if (rhythm === '/q') {
        score.set({time: "1/4"});
    } else if (rhythm === '/h') {
        score.set({time: "1/2"});
    }
    system.addStave({
        voices: [score.voice(score.notes(pitch + rhythm))]
    }).addClef('treble');
    vf.draw();
}

```
### Links to supporting documents are in red at the bottom
![Link Example]()

All tutorials are built with **HTML** and **CSS**

Please submit bugs and problems via the *issues* tab in this repo
