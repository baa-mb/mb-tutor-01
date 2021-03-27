# tutorial-basic


## It's time to code! @showhint
# Überschrift
Let's get real bright. We're going to make all the lights flash on your board!


## Make a new variable @showdialog
# Erste Zeile 


Mit diesem Kurs lernst du, wie du Microbit entdecken kannst!
During an interaction, the step description (all text before the first code block or image) is shown in the caption. If the paragraph length goes beyond the display length of caption, a "More" button appears in order to view the rest of the paragraph. It's best to keep the paragraph short enough to so all of it appears in the caption without requiring the user to click to see it all. If your instructions need more text, you can just create an additional step to split up the activity.
```block
    export function baa() {
        basis.showText("Alois")
        console.log("alois")
    }
``` 
![Agent building a tower](/static/mb-tutor-01/bild.png)

## Step 2
# Anleitung 

Sehr gut!

![bild](/static/tutorials/bild.gif)

## Introduction @unplugged

Have the agent build a tower! Make a command to tell it how many levels to build.
![Agent building a tower](/static/tutorials/bild.png)



## Show the temperature

Get a ``||input:temperature||`` block and place it in the value slot of ``||basic:show number||``.

```blocks
forever(function() {
    basic.showNumber(input.temperature())
    basic.pause(1000)
})

```

