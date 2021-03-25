# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Jonah Noh**

Time spent: **2** hour spent in total

Link to project: https://night-responsible-plywood.glitch.me

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

## Video Walkthrough

Demo of the Start and Stop button functionality:

![](https://i.imgur.com/8V53hLc.gif)

Demo of gameplay in which the game is won:

![](https://i.imgur.com/iyc35YI.gif)

Demo of gameplay in which the game is lost:

![](https://i.imgur.com/S0JRUyl.gif)

## Reflection Questions
**<p>1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.</p>**
<p>N/A</p>

**<p>2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) </p>**
<p>While creating this submission, I encountered a bug when writing the code for the conditional statements in the game logic portion. As I was playing the game,
the clue sequence for the next turn would not flash any colors nor play and sounds after clicking the correct sequence. In order to overcome this issue, I tried
reordering my if-else statements to see if it was not reaching the correct conditional case due to early termination. However, this did not fix the problem. 
I then remembered that the web browser has a console in which you can log the actions that the user is performing. As a result, I used console.log() to
see which conditional statement I was entering after clicking the correct sequence. In doing so, I discovered that I was entering the correct clause, but I had forgot
  to call the playClueSequence() function. After I fixed this bug, my game worked correctly for both cases of winning and losing.</p> 

<p>By encountering this challenge, I debugged my first piece of JavaScript code, while also gaining more familiarity with using the console to debug the logic of my program. 
  Even though the bug was frustrating at first, I am glad that I came across it because I now feel more confident in my debugging skills with respect to JavaScript.</p>

**<p>3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) </p>**
<p>After completing my submission, I am curious about the potential of JavaScript and its use cases. In this project, I used JavaScript to create a simple memory game. However,
I want to know more about how JavaScript is used in conjuction with backend services (e.g., PHP server) and REST APIs to create a synchronous website that provides real time data
  to its users.</p>

<p>Additionally, I am curious to see if other website developing services, such as WordPress or Webflow, can truly replace traditional JavaScript + CSS websites in the future.
I know that JavaScript allows for fully customizable websites, but it seems like Webflow and other services have come a long way in allowing their users to develop websites
  without knowing how to code.</p>

**<p>4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) </p>**
<p>If I had a few more hours to work on this project, I would learn how to revamp the UI for the memory game so that it is more visually appealing for users. This could include custom button shapes for the various game buttons,
and 3D fonts so that the heading and body text stand out more. I would also refactor the guess() function so that the game logic is easier to understand for others that may review my code. I would have to do some more research
  on the various conditional statements available in JavaScript, but I think a switch statement would help to make the game logic more readable.</p>



## License

    Copyright Jonah Noh

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
