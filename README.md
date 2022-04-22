# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **PRATIK KAMBLE**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/imported-aerial-winterberry

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

### Game Lost:

![](gif1-link-here)![](https://i.imgur.com/5nSNCKY.gif)

### Game Won:

![](gif2-link-here)![](https://i.imgur.com/UFUmOsN.gif)


## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   
   - The CodePath course for prework was more than sufficient for me to complete the submission. It had important information about the concepts along with hints to write my logic. 
   

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   - I had 2 bugs in my code, when (progess==3), I was going out of the program and "You lost" alert message was displayed. This took my most of the time to debug. I added a console log and realized that guessCounter is getting undefined during the execution. The reason for this was I had declared guessCounter again in the playSequence() method. On removing the declaring and just initalizing the counter worked.

   - 2nd bug was after adding 5th button, 4th button was not lighting up. This was a silly typo. It was resolved quickly.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   - The execution flow, I still have trouble understanding the execution flow in Javascript. I am confortable in Java, as I like as we can see the flow. I wish I can get the same intuition with Javascript too. 
   - I want to learn more how can host a website, as in the submission glitch made it easily available. How to do it without glitch would be a nice learning for me.


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   - If I got few more hours to work on this, I am confident that I would be able to do all the optional features, speeding it up with each pass, using random secret pattern, giving player strikes, adding images and different sounds to button and adding a ticking clock.
   - I also was wondering if I can convert the game to a different theme, making the buttons images and telling a story through the game maybe education users about climate change, when the click on the button show a before and now images of earth.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://loom.com/share/34b3a3cc93214809ab1149fbfda8dbb4)

## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
