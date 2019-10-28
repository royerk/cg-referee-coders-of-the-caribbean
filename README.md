# cg-referee-coders-of-the-carribbean

A compatible referee for [cg-brutaltester](https://github.com/dreignier/cg-brutaltester/)

## Compile & Packaging

    $ javac -d . src/*.java
    $ jar cfe cg-cotc.jar Referee *.class

## Prebuilt

see [releases](../../releases/)

## Add logging

* Use timestamp as unique identifier for the game.
* Send timestamp to the bot.
* Send player identification (0 or 1) to the bot.
* Store timestamp and winner to disk.
