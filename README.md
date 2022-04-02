# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Huu Le**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/boggy-tar-leader

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
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [X] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/Z20tYTf.gif)
![](https://i.imgur.com/aSBnO13.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    I did not use any outside help on this project.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    The biggest challenge I encountered was figuring out how to make a “game” within a website. Since I have some experience with Unity, I understand that for games to work, there has to be some sort of “main game loop.” However, I do not have as much experience in getting a game loop working outside of the context of Unity. I usually assumed there was some sort of endless loop running that handled how the game handled, which is partially true for this assignment. By reading through the notes, I was able to eventually figure out that the game’s loop is handled in the “guess” function. This function continues to call “playClueSequence” until the game ends. At first, I was not entirely sure about this reasoning, so when I decided to add the additional feature of enabling the player to have multiple guesses, I was unsure about how to properly implement it. Even though there were tips at the bottom of the write-up, I thought it would be much more beneficial for me to try and figure it out on my own. I was correct that I had to write the code within the “guess” function, but as to how, I spent some time thinking about how to properly implement it. At one point, I even contemplated utilizing a while loop to handle the guesses, but better judgment and reasoning made me realize that that implementation would have used up all of the player’s guesses in a single button press. Naturally, my shortcomings came from my weak understanding about web development in general. I do not think I am very proficient in working with HTML, CSS, and Javascript together to create a website, so, of course, making a small game was bound to have a few, little, road bumps. Thankfully, the project was simple enough to understand, and with some thought, I was able to quickly add the features I desired. Ultimately, it was all a very great learning experience, and now, I have a better idea on how I can improve on my skills in web development as a whole.
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    The biggest question I have would be, “How are web developers able to make more intricate and aesthetic websites?” To specify this, I am very curious on how exactly programmers are able to organize different elements on the pages. Whether this be buttons, links, pictures, or even text, it seems that there must be a lot of calculations in order to place each piece perfectly on the page. This project only required a very simple layout, but, to my understanding, a majority of websites require something much more complicated. Simple padding and a flow order of elements does not seem to properly organize a website into clean sections. Therefore, I ask my questions in hopes of getting tips or examples on how real web developers build their websites, because being able to turn code into a very visually pleasing website seems like a fantastic skill to have in the coding world. Additionally, there are also all the different functionalities that a website can have, beyond simple links and buttons. Maps, games, animations, and more are all possible on a website, and I would love to learn how developers are able to put all the tools together like that. This project has given me a little glimpse into how it is done, and now, I would love to see it done on a much deeper level.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    With a few more hours, I would try to enhance the replayability of the game, while also polishing it. Firstly, I would try to add an area where players can input how many rounds they would like to have before playing. From there, it would make sense to randomly generate which buttons would be pressed in order to complete the game. In doing so, the game would feel much more complete and flexible. Adding onto the aspect of player customization, I would also add a variable amount of buttons, in case the player wanted more (or even less than) 4 buttons. This could up the difficulty of the game, encouraging players to challenge themselves and see how great their memory is. Additionally, if I was really confident in myself, I might even try to make the website look much more visually appealing. I could add a theme for the website, or even place a cohesive color scheme for everything (except the buttons that needed to be pressed). Ultimately, I want the players to have a very clean experience, so they can play this over and over if they desire to.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Huu Le

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
