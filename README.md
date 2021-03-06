 # Spooky Tunes

 ```blocks
music.setTempo(160)
music.setVolume(255)
music.setVolume(255)
music.setTempo(160)
music.playMelody("- - - - - - - - ", 120)
```

```template
game.showLongText("Press the A button (or press the Z key) to hear a spooky tune.", DialogLayout.Center)
controller.A.onEvent(ControllerButtonEvent.Pressed, function () {
    mySprite.setImage(img`
    ................................
    ................................
    ................................
    ................................
    ................................
    ..........888888888888..........
    ........8887777777777888........
    ......88877666666666677888......
    .....8877666667777666667788.....
    ....887666667788887766666788....
    ....866666677888888996666678....
    ...88666667788877889976666688...
    ...88666677888677688877666688...
    ...88666778888888888887766688...
    ...88667788888888888888776688...
    ..cc866788866777777668887668cc..
    .ccbc8668866666666666688668cbcc.
    .fcbcc86666666666666666668ccbcf.
    .fcbbcc886666666666666688ccbdcf.
    .f8bbbccc88888888888888cccbddcf.
    .f8cbbbbccccccccccccccccbdddbcf.
    .f8ccbbbbbccccccccccccb11dddccf.
    .f6ccccbbbdddddddddddd111ddcccf.
    .f6ccccccbbddddddddddd11dbbcccf.
    .f6cccccccccccccbbbbbbbbbdbcccf.
    ..f6cccccccccbbbbbbbbbbbddbccf..
    ..f6cccccccccbbbbbbbbbbbddbccf..
    ..ff6ccccccccbbbbbbbbbbbddbcff..
    ...ff6cccccccbbbbbbbbbbbddbff...
    ....ffcccccccbbbbbbbbbbbdbff....
    ......ffccccbbbbbbbbbbbbff......
    ........ffffffffffffffff........
    `)
    music.playTone(220, music.beat(BeatFraction.Half))
    music.playTone(196, music.beat(BeatFraction.Half))
    music.playTone(220, music.beat(BeatFraction.Whole))
    music.rest(music.beat(BeatFraction.Half))
    music.playTone(196, music.beat(BeatFraction.Quarter))
    music.playTone(175, music.beat(BeatFraction.Quarter))
    music.playTone(165, music.beat(BeatFraction.Quarter))
    music.playTone(147, music.beat(BeatFraction.Quarter))
    music.playTone(139, music.beat(BeatFraction.Whole))
    music.rest(music.beat(BeatFraction.Quarter))
    music.playTone(147, music.beat(BeatFraction.Double))
    mySprite.setImage(img`
    ..........666666666666..........
    ........6667777777777666........
    ......66677777777777777666......
    .....6677777779999777777766.....
    ....667777779966669977777766....
    ....677777799668866117777776....
    ...66777779966877861197777766...
    ...66777799668677686699777766...
    ...88777796688888888669777788...
    ...88777788888888888888777788...
    ...88977888679999997688877988...
    ...88977886777777777768877988...
    ...88997777777777777777779988...
    ...88799777777777777777711788...
    ...88679997777777777779117688...
    ..cc866679999999999999976668cc..
    .ccbc6666679999999999766666cbcc.
    .fcbcc66666666666666666666ccbcf.
    .fcbbcc666666666666666666ccbdcf.
    .f8bbbccc66666666666666cccbddcf.
    .f8cbbbbccccccccccccccccbdddbcf.
    .f8ccbbbbbccccccccccccb111ddccf.
    .f6ccccbbbddddddddddddd111dcccf.
    .f6ccccccbbddddddddddddddbbcccf.
    .f6cccccccccccccbbbbbbbbbdbcccf.
    ..f6cccccccccbbbbbbbbbbbddbccf..
    ..f6cccccccccbbbbbbbbbbbddbccf..
    ..ff6ccccccccbbbbbbbbbbbddbcff..
    ...ff6cccccccbbbbbbbbbbbddbff...
    ....ffcccccccbbbbbbbbbbbdbff....
    ......ffccccbbbbbbbbbbbbff......
    ........ffffffffffffffff........
    `)
})
let mySprite = sprites.create(img`
    ..........666666666666..........
    ........6667777777777666........
    ......66677777777777777666......
    .....6677777779999777777766.....
    ....667777779966669977777766....
    ....677777799668866117777776....
    ...66777779966877861197777766...
    ...66777799668677686699777766...
    ...88777796688888888669777788...
    ...88777788888888888888777788...
    ...88977888679999997688877988...
    ...88977886777777777768877988...
    ...88997777777777777777779988...
    ...88799777777777777777711788...
    ...88679997777777777779117688...
    ..cc866679999999999999976668cc..
    .ccbc6666679999999999766666cbcc.
    .fcbcc66666666666666666666ccbcf.
    .fcbbcc666666666666666666ccbdcf.
    .f8bbbccc66666666666666cccbddcf.
    .f8cbbbbccccccccccccccccbdddbcf.
    .f8ccbbbbbccccccccccccb111ddccf.
    .f6ccccbbbddddddddddddd111dcccf.
    .f6ccccccbbddddddddddddddbbcccf.
    .f6cccccccccccccbbbbbbbbbdbcccf.
    ..f6cccccccccbbbbbbbbbbbddbccf..
    ..f6cccccccccbbbbbbbbbbbddbccf..
    ..ff6ccccccccbbbbbbbbbbbddbcff..
    ...ff6cccccccbbbbbbbbbbbddbff...
    ....ffcccccccbbbbbbbbbbbdbff....
    ......ffccccbbbbbbbbbbbbff......
    ........ffffffffffffffff........
    `, SpriteKind.Player)
music.setVolume(255)
music.setTempo(145)
```

## Step 1
You found the Tesla coil and its eerie beat. Now's your chance to make your own little tune.

## Step 2
For this project, we have already translated a famously creepy song into MakeCode, but this is your chance to explore and experiment.

## Step 3
All the blocks you need can be found in the ``||music.Music||`` folder. From there, you can change the volume or tempo (speed) of the music, and select different notes to play.

You can also use the ``||music.play melody||`` block to quickly create a piece of music to play.

## Step 4
Take as much time as you would like playing around and making some ghostly tunes.