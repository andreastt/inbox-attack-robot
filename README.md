# InboxAttackPilot

This program is a robot playing the SVG/JavaScript game [Inbox Attack](#)
created by [Daniel Davis](#) using the [Selenium](http://seleniumhq.org/)
browser automation library.

## Playing the game

### Requirements

* [Java Development Kit (JDK)](http://www.oracle.com/technetwork/java/javase/downloads/index.html) is required to play the game.
* [Ant](http://ant.apache.org/) is required to use the simple build script.

### How to play

From the project's root directory, enter the following command in a command prompt:

    ant play

If you want to manually specify the location of the game, you can do this:

    ant -Durl=file://localhost/home/andreastt/dev/inbox-attack-pilot/inbox-attack.svg

Replace the URL with the location of your Inbox Attack game.

## Known issues

* Opera Desktop has a rather slow Scope implementation, so the game will only work in internal core-gogi builds
* Does not work with other WebDriver implementations yet, although it should be trivial to add support for that
* The robot always performs perfectly: Increase difficulty of game, or decrease accuracy of robot?
* The Inbox Attack game itself is not perfect in terms of debugging capabilities, and it should be refactored to take into account proper objects for everything instead of dealing with separate static variables for debugging

## Demo

Links to videos coming here.
