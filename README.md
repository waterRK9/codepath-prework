# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ivy Liu**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/battle-olive-bear

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] Pattern length modified each round by a prompt given to the player after clicking start button

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
[GIF](https://recordit.co/KLcyTJIRHJ)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random - to find out if I was able to generate psuedo random numbers in JS.
My friends: Nicole, Johan, Prem, Uyen, and Kate - for feedback on implementing features.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
Upon implementing what I did, I was left with the question "Should I keep going?". I felt the urge to check off every
box we were given, but they don't seem beneficial to the program in terms of making the game better to play. I of course, am only one opinion on
whether I made the best choices. So I asked my friends to play my game and tell me if it broke or if there was something they wanted implemented. 
The responses were generally lukewarm, it's a game of Simon Says. Simple as that. One of my friend wanted me to show a unique meme for each
square that lit up and play the Waluigi, but another friends said it was would be too distracting and would get annoying. The latter friend 
friend is also red-green colorblind, so they relied on the sounds to know which squares to hit. I hadn't realized could be an acessiblity
feature until they brought it up, and so I didn't modify the game. But, I could've modified the button images. Maybe made the entire game Pokemon
themed so it was distinct. But that doesn't appeal to everyone, what if some people didn't like Pokemon or didn't understand what I was going for? 
I was back to square one. In the end, my motto of "make it stupid simple" prevailed. Less references, less superfluous features, and less chances of breakage.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I'm wondering how to make this website more "stateful" so that we can take advantage of the fact that this is a
website connected to the internet and not just an app or program on a single device. I would like to figure out
if I'm able to incorporate storing score histroy of players. I'm also curious about if there is a point
where more "features" are excessive. Many of the optional features we were given the option to implement seem
like a good way to encourage us to explore the capabilities of web develepment, but they also seem like they'd muddle
the main focus: which is the game. I wonder how often developers have say in what they believe is best practice versus
simply following the direction of clients for implementation.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would want to display a scoreboard (i.e. top 10 players across all time or maybe all scores) and allow the game go on 
"forever"/until the player lost. I would have the player enter their name when they lose or hit the upperlimit
of whatever variable size I was using to store the score (not sure how many bytes numbers get in JS).
I would probably want to store this information in a table on database on a server somewhere so any player
that visits the site could see it, but I'm not sure how to do that without having a server provided to me.
I think I would place the scoreboard below the game itself so it doesn't get in the way of the players who want 
to play for fun without the pressure of competiting, or to let them toggle the scoreboard visibility. 
I might also implement an "easy" and "hard" mode, where the easy mode player can have the clue played 
again by pressing a button, but the hard mode player cannot.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://mit.zoom.us/rec/share/imSmpAUeKtS73HCKbkdHCcG6QvEhiHhFB8XUGBQCNHQiekBaWJ8j9IMJJpMPgBk.I9OTPphsPQJz9_u7?startTime=1648564784000)


## License

    Copyright Ivy Liu

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.