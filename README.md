 # Spooky Tunes

 ```blocks
music.setTempo(160)
music.setVolume(255)
music.setVolume(255)
music.setTempo(160)
music.playMelody("- - - - - - - - ", 120)
```

```template
controller.A.onEvent(ControllerButtonEvent.Pressed, function () {
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
})
music.setVolume(255)
music.setTempo(160)
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