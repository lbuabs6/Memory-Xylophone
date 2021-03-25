# Pre-work - *Memory Game*

**Memory Xylophone** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **LEO OHENE AFRIYIE-BUABENG**

Time spent: **6** hours spent in total

Link to project: https://glitch.com/edit/#!/expensive-kind-skipjack

## Required Functionality

The following **required** functionality is complete:

* [Y] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [Y] "Start" button toggles between "Start" and "Stop" when clicked. 
* [Y] Game buttons each light up and play a sound when clicked. 
* [Y] Computer plays back sequence of clues including sound and visual cue for each button
* [Y] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [Y] User wins the game after guessing a complete pattern
* [Y] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [Y] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [Y] Buttons use a pitch (frequency) other than the ones in the tutorial
* [Y] More than 4 functional game buttons
* [Y] Playback speeds up on each turn
* [Y] Computer picks a different pattern each time the game is played
* [N] Player only loses after 3 mistakes (instead of on the first mistake)
* [N] Game button appearance change goes beyond color (e.g. add an image)
* [N] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [N] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/Uo1koFa.gif)
![](https://i.imgur.com/HVli2p4.gif)




## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
    - w3schools.com

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    - I tried to add the strikes to the project. I was able to get it to count down from 3 to game over. However, I was unable to make the game continue. I placed the strike variable in the guess function, used a while loop so that the guesses reduce with every wrong guess. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
   - Are there other languages that will be better suited for the current project?
   - What level of full-stack development is used in this project and how huge is the gap from this to industry level?
   - In companies, are the index, script and style all done by one developer or they are done by different developers because of the volume?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
  - If I had a few more hours, I would add levels to the game. After successfully completing a game, the next level will have more buttons and the pattern will be longer. I would also make three more buttons: Easy, Medium Hard. The regular buttons will be hidden until a difficulty is selected. The higher the difficulty, the lengthier the patterns, the shorter the clue time gets, and more buttons. 



## License

    Copyright [LEO OHENE AFRIYIE-BUABENG ]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.