# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Angelene Estiandan

Time spent: 7 hours spent in total

Link to project: https://glitch.com/edit/#!/codepathprework---angelene-estiandan

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
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Alert messages pop up for mistakes.
- [x] Backdrop on buttons to make it more realistic.
- [x] Background music on loop when game is not active.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/kk8Lh9K.gif)
![](https://i.imgur.com/t6dC6XW.gif)
![](https://i.imgur.com/OVlgvS4.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

https://www.w3.org/wiki/CSS/Properties/color/keywords

https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Backgrounds_and_Borders/Resizing_background_images

https://stackoverflow.com/questions/3910736/how-to-call-multiple-javascript-functions-in-onclick-event

https://www.w3schools.com/jsref/met_win_setinterval.asp


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Despite taking introductory courses in Python, Javascript, and Java, I have not experimented with web development before, so the initial shock of having to experiment with HTML and CSS was intimidating. I was able to create the basic version of the light and sound game fairly easily, however, I struggled to implement some of the optional features, which quickly made me aware of my lack of experience in HTML and CSS. The optional feature I spent the most time on, surprisingly, was creating additional buttons within the game. Whether this was due to the fact that I was still warming up or my unfamiliarity with the languages, I failed to realize that I was missing semicolons at the end of my coding lines on the style.css file for the buttons. It took me 1 and a half hours to find my mistake, after going line-by-line, comparing my code to the basic tutorial provided. The second challenge I encountered was adding the audio as background music for the game. The instructions explained how to add new sounds to the buttons, but did not explain how to create background music. I had to use an outside source to find an idea of how to do it and thankfully, after 45 minutes of research, I learned how to auto loop the audio. I also gained familiarity with the .getElementbyId method to pause and play the audio when the “Start” and “Stop” buttons were pressed. 
The biggest challenge I faced was finding a way to express my individuality with the extent of coding knowledge I have. Since this program did not require resume submission, it was interesting to become creative with my aesthetic likes. When the buttons are pressed down, the buttons display Sanrio characters to represent my love for these characters from my childhood, along with my fascination for anything ~pink~ and girly. I chose the audio “Fairy tales of love” because it is one of my favorite piano instrumentals that sounds like it belongs on the opening screen of a video game. I went for the “cottage-core” like music to enhance feelings of comfort and ease.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I realized now that web developers have to be skilled in at least three different languages to effectively program a website. That being said, are web developers proficient in all of those languages? There are many websites, applications, and software that assist in making websites easily, such as WIX, Weebly, and WebFlow. Does raw programming allow the creation of websites to be better than using other services? What freedoms does programming from scratch give the developers in comparison to using services that can readily accept code for custom functions? After completing my submission, I am also curious about the implementations of web development in comparison to UI/UX design. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

Many video games do not accommodate users with disabilities. For example, a flashing screen may induce seizures or brightness and constant movement on the screen could exacerbate sensitivity, causing headaches or motion sickness. I would spend additional time ensuring that any user, with disabilities or not, would be able to play my Light and Sound game with ease. This includes having lower-contrast settings or displaying a tutorial at the beginning of the game to help those with cognitive disabilities. I would have a pop-up screen that asks the user if they would like a color-blind friendly version of the buttons, and an option to lower and increase the volume of the audio with 70 decibels as the maximum to prevent long-term hearing loss.
If I had a few more hours to work on this project, I would add a “survival” option, in which the pattern would continue to get longer and faster until the player made two mistakes to reach a “Game Over”. There would be a final score screen displayed that shows the longest sequence that the player was successfully able to complete and a “share” button to send their results to their friends to inspire playful competition. For user creativity, I would implement many user-choice settings, such as color choice, button shape, and audio selection to make the game more individualized based on user preference. For user convenience, I would include a progress bar to notify the player of their progress in completing the entire 8-peat pattern. In terms of refactoring certain functions, I would reconfigure my “createPattern” function to be a for loop that loops 8 times instead of individually generating a random integer for each index.




## Interview Recording URL Link

[[My 5-minute Interview Recording](your-link-here)](https://drive.google.com/file/d/1h0OT7yWppqvWIiEZlWu-v9Lu5hvD_kvv/view?usp=sharing)


## License

    Copyright Angelene Estiandan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.