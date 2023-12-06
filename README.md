# template-jvm
The Enigma Showdown template repository for Java, Kotlin, and other JVM languages. Gradle is utilized as the build system.

## Getting Started

On the [main page of this repo](https://github.com/EnigmaShowdown/template-jvm), click "Use this template", and "Create a new repository".
Give it a cool name!
Once a new repository is created, clone it locally.
Now, install IntelliJ, which you can easily do by first installing [Jetbrains Toolbox](https://www.jetbrains.com/toolbox-app/).

Open IntelliJ and open the project you cloned locally.
IntelliJ should take a second to download dependencies, and soon enough you'll be ready to use it!


### Running Enigma Showdown

This repository that you now have open in IntelliJ has a `game` module, which is set up to easily launch the game.
All you have to do is double tap control to open the "Run Anything" window inside IntelliJ.
Now run `gradle game:run`. The game should launch.

If you are unable to get the "Run Anything" window to open, you may alternatively open the Gradle tab (elephant icon in the upper right).
Inside the Gradle tab, navigate to bot-enigmashowdown -> game -> Tasks -> application -> run, and double click "run".

Go ahead and click "host", then click on level 1.
The Enigma Showdown window should be a blank screen.
Continue to the next step.

### Running `MyPlayerAI`

Now that you have the game open and running, it's time to launch `MyPlayerAI`.
Navigate to either `bot-kotlin/src/main/kotlin/enigmashowdown/my/ai/MyPlayerAI.kt` or the java equivalent.
The easiest way to do this is double tap shift to open quick search, and then search for "MyPlayerAI".
Once you have your MyPlayerAI class open, find the green run button on the left side of the screen near the line numbers.
Click this button and run it!

Assuming you correctly had Enigma Showdown running with a level selected, the Enigma Showdown window should no longer be blank,
and a count down will soon appear.
