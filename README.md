# codepath-prework
Codepath Pre-Work Project | Memory Game

# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **vijay vadi**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/local-vivacious-catcher

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Counter to inform player which round the game is on

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
    1) Math.random() | Mozilla
       * https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random
       * Used to determine the proper syntax to generate a random number between a certain range.
       
    2) Javascript Output | w3Schools
       * https://www.w3schools.com/js/js_output.asp
       * Used to research the proper syntax in order to display text for the round counter in the frontend.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
    * The first challenge I had to overcome while working on this project was my lack of advanced Javascript knowledge. While I do have prior experience with HTML, CSS, and even more advanced languages such as Java, my lack of JavaScript specific syntax was an obstacle while working on the final parts of the project. Although this was an issue initially, a quick reference to the JavaScript docs and W3Schools helped me easily establish connections between JavaScript and the languages I already knew. Making these connections was a vital part of my success on this project since it helped me learn and move quickly. My second challenge appeared while I was trying to solve a problem that was naturally created by the way this project was implemented. To specify, while the project is displaying the pattern, users can still press the buttons, essentially allowing the users to cheat. To counter this, I attempted to implement a function that tracks when a user clicks a button when they are not supposed to. Ultimately, after trying a few solutions I had to scrap the idea due to time constraints.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
* My largest question prior to working on this project and now revolves around the different Javascript frameworks. These include, React JS, Angular JS, Vue, or Node. I have always wanted to make complex and responsive web applications to pair with current mobile app projects that I’m working on, so increasing my knowledge of these frameworks can help me achieve that goal. With this in mind, my question would be, “What specific benefits do JavaScript Frameworks, such as React, Vue, or Angular, provide over one another when developing complex and response web applications.”

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
* If I had a few more hours to work on this project, I would have added the anti cheat function I mentioned in response to the first question. To recap, while the project is displaying the pattern, users can still press the buttons, essentially allowing the users to cheat. To counter this, the anti cheat function essentially tracks when a user clicks a button when they are not supposed to. While I didn’t have this to do this in the current iteration of the project, I would implement it if I had more time. If it was still difficult to produce, as a counter solution I would simple disable the buttons until the pattern was completely displayed.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright vijay vadi

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
