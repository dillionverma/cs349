# Students Vs Assignments

By: Dillion Verma

![Students Vs Assignment Gif](img/game.gif)

Students vs Assignment is a game inspired by [One Finger Death Punch](https://en.wikipedia.org/wiki/One_Finger_Death_Punch).

## How to run

1. Install [AdoptOpenJDK](https://adoptopenjdk.net/) and [OpenJFX](https://openjfx.io/)
2. Set `JAVA_FX_HOME` environment variable in your `~/.bashrc` or `~/.zshrc` to the javafx download path. For example:

   ```
   export JAVA_FX_HOME='/Users/dillionverma/lib/javafx-sdk-11.0.2'
   ```

3. Clone this repository and then run `./run.sh` to run the game.

## How to play

- Press left or right arrow keys to throw a mark in that direction
- +1 students marked for hitting a student
- -1 students marked for missing a student (marks only travel a certain distance)
- -1 vacation days for letting a student touch the teacher

## Features

- Custom graphics made by my [sister](https://instagram.com/krittical_hit) to make gameplay fun
- Levels get progressively harder
