# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Chaiwat Wongsatjachock**

Time spent: **11** hours spent in total

Link to project: https://glitch.com/edit/#!/outrageous-purple-ragamuffin

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

**Winning and losing 1 life**
![](https://i.imgur.com/GS4U2R8.gif)
**Losing all lives and showing different randomized pattern**
![](https://i.imgur.com/cr9yhg3.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

www.stackoverflow.com, www.w3schools.com, www.youtube.com, https://developer.mozilla.org/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

The first challenge that I encountered was when the required steps stop giving direct instruction and actually coding the game logic that will handle the guesses.
This was the only step that required thinking which is unlike the previous steps of simply copying the instructions. 
The problem for me was that I didn't know where to start solving the problem and was stuck figuring out what to do first. 
I overcome this problem is by taking on the problem one by one instead of doing it all together.
By taking on the game logic incrementally, I was able to make progress even if I don't fully understand the scope of the task.
While I did have some trouble interpreting some of the conditional statements on the flow chart, I eventually got to the right answer by taking a closer look at the code and gaining a better understanding of them.
With all of the individual pieces finished, it was much easier to connect them all together so that they form the full game logic. 
Another problem I encountered was when I was implementing one of my optional features. 
The one that I have the most trouble with was implementing the lives system which is mainly due to mixed information while I was researching online.
There were two issues that gave me the most trouble, lining up the text next to each other and changing the text within the Javascript.
The way I solve those two is by looking up documentation of Javascript instead of forums like Stack Overflow as they provide a more general view of the problem compared to the specific user issue found in forums.
With the right documentation, I was able to solve my problems and finish the lives system.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

The questions that came to my head after completing it would be how to format the location for the buttons.
I wanted to rearrange my buttons so that they could form a ring while I was doing the project and it made me wonder where to even begin.
The code for that seems to be in the CSS but I would not be surprised if I'm wrong. 
Another question that I have would be how to implement server-side things like having a leaderboard that shows every player's score.
The player's data have to be stored somewhere and I wonder how the user is able to have their name connected with their score.
There is also the fact that the leaderboard has to update dynamically so that it will show the current top scorers at all times. 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had more time to work on this project, I would first find out how to organize the button and move them around.
While it is certainly nice that the buttons would adjust themselves so that they could fit the screen, I don't like the way they reorganize themselves and would prefer them fixed.
The reason is simply that the placement of the buttons and their location are important in a memory based game.
I feel like the user experience would improve if I could find a way so that the placement of the buttons would not adjust with different screen sizes.
Another feature I would make would be to improve the UI so that it looks nicer than just text with a background.
This could be from having a different font to colorful graphics that would make this game more pleasant to the eye.
I would also implement more customization so that the player could decide on how difficult they want the game like how long the rounds would go on or the speed of the pattern repeating back.
This way the user gets to decide the experience they want to play aside from the default set by the creator of the game. 


## Interview Recording URL Link

[My 5-minute Interview Recording](https://drive.google.com/file/d/1oAAljXfkSGKQPGgyuYQMqGUyhcqnOK97/view?usp=sharing)

[Interview Recording Transcript](https://docs.google.com/document/d/1OynfCMJvPFL5r0qpDGI4ubMRSd6XeTnc5iH6H6SDTgg/edit?usp=sharing)



## License

    Copyright [Chaiwat Wongsatjachock]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.I