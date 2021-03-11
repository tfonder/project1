# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Tyon Fonder**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/right-funny-yamamomo?path=README.md%3A42%3A19

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/G41QOBl.gif)



## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I challenge I encountered was getting the losing system to work correctly. This was because I had accidentally initialized the progress variable twice in a function. I was able to pinpoint that the issue was in the javascript section and found that I was only getting the issue of my game ending after three buttons. After I discovered the big in my code I did not have many other issues besides completing the readme section.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Some questions about web development that I have now are what are the lengths that the HTML and CSS languages are capable of? Are they Mainly only for aesthetics or could a website be coded only in one of these languages? Also, which front-end language does the industry consider the most important?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to complete the project I would have most likely added a few images to pop up on click and probably speed up the patterns of the game, as it can feel a bit slow after about the fifth step.



## License

    Copyright [Tyon Fonder]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.