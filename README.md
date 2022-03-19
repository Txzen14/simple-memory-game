# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Timothy Zeng

Time spent: 4 hours spent in total

Link to project: https://psychedelic-fierce-soldier.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![working game](https://i.imgur.com/PNbcIer.gif)

![starting and stopping](https://i.imgur.com/W4mUZkc.gif)

![game failure](https://i.imgur.com/cwVUvAd.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources to help complete my submission. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I did not encounter many problems creating the submissions. Overall, the instructions and guidance of the project was very clear. I took extra time creating this submission to understand what was going on instead of just copying and pasting each instruction. The only issue I had was in script.js, it occurred that my program would tell me that I had gotten the wrong pattern even if it was right. I didn’t know what the issue was at first, so I took these steps to figure out the issue and resolve it. First thing I did was understand where the possible location of the error was. Since it wasn’t an issue with the looks of the button and page, I knew the error would have been in the script.js file. From there I dry ran the program in my head and compared it to what one would expect to occur. Going through the functions that would be ran if the button were clicked. Quickly realizing it wasn’t the logic of the program I quickly realized the issue was in the declaration of the guessCounter variable. I had already created it in the global variable declarations and I had made the error of initializing it again in the function playClueSequence() as well. I quickly removed the Var declaration from the function. From there I reopened the page and tried the pattern again and it worked. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing my submission, I had a couple questions about web development. The first question I had was, how do professional web developers add complexity to the websites. How can we make the page more complex? I was also curious on how pages like these can be made more users friendly. Do those that work in web development focus on simplicity or complexity? Another question I had was what is considered web development? Is it just creating pages like these, other larger websites? What else? The final question deals with do web developers track how well their page is doing. How do they tell if users like their page and if it is providing everything they desire? 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had more time with this project, I would have liked to implement some of the optional features and some of my own features that I had thought about when creating the project. The first optional feature that I wish I could had implemented was creating a random pattern so the game can be played multiple times. I would have implemented this using a random function, where each position in the array pattern would have been chosen at random each time start was initialized. With this feature added I would have liked to add another feature on top of it, giving the player three strikes. This way the player would be able to have three attempts and try to solve as many patterns as possible. Those two optional features were the two I found the most interest in. A feature I thought about that I would’ve liked to implement is a counter on the screen that tells the player how many blocks they must guess on the specific turn. I would have also liked to implement a counter on the screen that shows how many totals wins a user has had. This way the game could be played more than one time, with random patterns, and they could play until three loses. In a past project, I had allowed users to choose their color using a gradient. I thought that would be interesting if users could choose the color of each block. 



## Interview Recording URL Link

[My 5-minute Interview Recording](https://psu.zoom.us/rec/share/vr4ekczXzPU7QmxsDCy54OtEYWPhJwd-foA8U-UiHBaQL8Hj3SRj5vwW3yRJRcXH.Wu24GGGoCMFvoV0R)


## License

    Copyright [Timothy Zeng]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.