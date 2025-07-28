# Chase the Pizza
### @explicitHints true


### ~button /#tutorial:/tutorials/chase-the-pizza

Try this tutorial!

### ~

## Introduction @showdialog


Create a game where the goal is to eat as much pizza as you can 
before the time runs out! 



```blockconfig.global
let pizza: Sprite = null

scene.setBackgroundColor(13)
sprites.onOverlap(SpriteKind.Player, SpriteKind.Food, function (sprite, otherSprite) {})
randint(0, scene.screenWidth())
pizza.setPosition(randint(0, scene.screenWidth()), randint(0, scene.screenHeight()))
info.startCountdown(3)

```
