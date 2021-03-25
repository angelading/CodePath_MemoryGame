# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Yi Ding**

Time spent: **3.5** hours spent in total

Link to project: https://glitch.com/edit/#!/forest-comfortable-myrtle?path=README.md%3A9%3A17

## Required Functionality

The following **required** functionality is complete:

- [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [X] "Start" button toggles between "Start" and "Stop" when clicked.
- [X] Game buttons each light up and play a sound when clicked.
- [X] Computer plays back sequence of clues including sound and visual cue for each button
- [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [X] User wins the game after guessing a complete pattern
- [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [X] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] Users can pick the difficulty levels

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://i.imgur.com/Alah8QR.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   
   I used CSS color picker tool to generate colors that I like.
   https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Color_picker_tool

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it?
   
   Some challenges that I have gone through during the project were adding the sound to buttons and debugging. One problem that I had was having no sounds after clicking the buttons. At first, I thought that was the Internet issue, and I tried to refresh the page but there were still no sounds. Then, I started to think there should be something wrong with my code. Therefore, I went back to the script.js file to check if there were any errors within my sound synthesis functions. However, I didn't find any. Next, I considered the connections between the buttons and the sound. Buttons have implied the function of starting the tone and ending the tone. I traced back to the index.html file and found my error in the gameButtonArea eventually. 

When I got to the part where we need to complete the guess function, I tried to write the code by myself. But I ran into some errors after I finished the code. I recalled the console logging method mentioned in the tutorial. Therefore, I tried to print things out so that I can see what happens after my program executes. By using this method, I successfully found out one of my variables was not incremented and completed the function. 


3. What questions about web development do you have after completing your submission?
  
   Most websites now have more than one web page, I want to know how these web pages are connected together, and where the data used behind them comes from. I know the second question has to do with data management and SQL, and I am interested to learn more about these.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc)?
   
   This is a very interesting game which can be upgraded so that the players can have more ways to play. If I have more time, I would definitely add more features to the game, such as adding more buttons and more challenging levels to players. Since we can add different pitch frequencies, I think it will be nice to have different instrument sounds. It can be classical instrument sounds or modern electronic sounds and more. In order to increase the difficulty of the game, I will also speed up on each difficulty level. In this way, the player must remember these sequences faster. For more interesting features, I would also set a certain number of buttons to represent different keys of a certain instrument and then generate a pattern of tones that can play a simple song. This game mode can help players memorize sheet music. 

## License

    Copyright Yi Ding

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
