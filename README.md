# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Ben Pu

Time spent: 3-4 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)
https://glitch.com/edit/#!/tidy-past-grass

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

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](gif1-link-here)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- developer.mozilla.org
- https://www.w3schools.com/tags/tag_img.asp
- geeksforgeeks.org

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
- Most of the challenges that occurred came during the implementation of bonus features. One of these difficulties arised when I was trying to add images to the buttons. Aside from the fact that there are many different ways of going about the task, I realized that different images would cause the buttons to have awkward sizing. One alternative would have been to play around with the padding, so that the images would be aligned. Another option would have been to crop all the images before using them, so that they would have the same dimensions. I decided to just go with images of consistent dimensions which allowed the buttons to be more organized. Had this issue not been addressed, there would have been three buttons on some lines and two buttons on others- all with varying degrees of heights. Once the images were uploaded into the assets folder and referenced in the html file, I also had to implement the code that would allow for the images to be hidden unless the buttons were clicked. I implemented this by having all of the images hidden unless when the buttons were active, in which case the images would be shown until the buttons were inactive. Another potential option would have been to show the images whenever the button was hovered. Not only were there methods to implement this via CSS but there were also tons of options that used JS. 
Both of these problems were solved by me first writing down what could have caused the issue and potential alternatives. By playing around with the different properties, I was eventually able to get the desired effects.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
- Having been able to make this simple interactive game, I wonder what I would need to make this website "live" and how I would maintenance it in the long run (if I plan on scaling it or if a user reports bugs/errors). I also wonder how I would be able to allow for multiple players to play concurrently because single player would be too boring over time. This leads me to think about the traffic load that the web server would be dealing with and how I would need to handle these issues. In conclusion, I think it would be the natural progression to begin considering backend and explore what things are occurring behind the scenes to allow for smooth and comfortable user experience. Having been exposed to C, I wonder how the difference in machine would cause on the code or website. One example would be how an ipad would view the website versus a 64 RAM Windows PC- would they be able to play against each other?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
- Had I been given a few more hours to work on this project, I would have definitely wanted to consider a two player mode or if time permits- a multiplayer mode. The initial idea would be to have the players take turns going and the scores would be stored in a global variable(I can have a scoreboard at the top). Aside from adding this new feature, I would also need to consider the quality of the already existing code. I wish to make the website more aesthetically pleasing and comfortable for the user because I know from personal experience that it can detract from the experience if the webpage looks bad. These things include having consistently-sized buttons, images, and legible fonts. For example, having too many colors or different font sizes would cause the user's eyes to strain.


## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


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
