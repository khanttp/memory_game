# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Tapan Khanal

Time spent: 7 hours spent in total

Link to project: https://glitch.com/edit/#!/emerald-exuberant-bead

## Required Functionality

The following **required** functionality is complete:

* [yes] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [yes] "Start" button toggles between "Start" and "Stop" when clicked. 
* [yes] Game buttons each light up and play a sound when clicked. 
* [yes] Computer plays back sequence of clues including sound and visual cue for each button
* [yes] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [yes] User wins the game after guessing a complete pattern
* [yes] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [yes] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [yes] Buttons use a pitch (frequency) other than the ones in the tutorial
* [yes] More than 4 functional game buttons
* [yes] Playback speeds up on each turn
* [yes] Computer picks a different pattern each time the game is played
* [yes] Player only loses after 3 mistakes (instead of on the first mistake)
* [yes] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

* [] Users can see how many strikes they have 


- [ ] List anything else that you can get done to improve the app!


  

  

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](your-link-here)

<img src = "https://cdn.glitch.com/10088d4d-740f-42bf-aa06-3f3972fae601%2Fmemory_game_gif.gif?v=1616641210130"> </img>


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[YOUR ANSWER HERE]

  - https://www.w3schools.com/
  

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[YOUR ANSWER HERE]

  After I was done following the tutorial, the website didnt play the sequence patterns when I pressed "start".
  To de-bug this, I opened up the console, and saw that I was getting a null array error. When I went to the lines
  and looked around, I realised I forgot to change the button ID name when copying the lines. I also ran into bugs 
  when I was embedding images into the game buttons. I created a div in the HTML file and put the images
  inside the buttons, but they appeared behind it. After looking up solutions and playing around for a bit, 
  I realised I could just make each image the background and that solved it. When implementing the strikes, I realised
  there was no way for the user to see how many mistakes they've made, so I decided to add a display for that. 
  I wasn't sure how to update the strikes when a player makes a mistake, so I re-read the tutorial and noticed 
  I could use document.getElementByID. 
  
  
  

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

  - How are websites made more accessible to people with hard of hearing, blidness, non-english speaking, etc. 
  - What features are the most imporatnt to keep in mind when developing webpages? What features enhance accessblity? 
  - what features enchance user/customer loyalty?
  - What are the "proper" steps to developing and deploying a fully functional website? 
  - How do webapp, webpage, and websites differ? 
  - I've seen some websites that run without internet, how is that done? 
  - How do I go about adding more advanced features to a game? Like a multiplayer, scoreboard, different levels, etc
  - How do I deploy a game/page online 
  - How can databases be used to enchnace the game? Like storing player scores, levels completed, etc
  - What does it mean for a game to be online? 

 
  

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

  More visually appealing interface and design. I would change the colors, shapes of boxes, pictures, fonts, white space, and overall 
  visual balance of the web design to make it look more appealing. Make the webpage responsive so that the website can respond to the user's 
  behavior and environment based on their screen size, platform, and orientation. I would use sounds that correspond to the images that are 
  displayed (I did not have enough time for this feature). When the game is playing a pattern, make it so that the user cannot click on sounds 
  (currently, users are able to press the buttons as the sounds are being played to them). Add levels with increasing difficulty. The following features will take longer than few hours, but:
  
  create a point system to award the users when they complete levels. 3 stars to players who complete the level without getting any strikes, 
  2 stars to 1 strike, and so on. Each star will coresspond to to x amount of points. Each level will award x points, so have a scroeboard 
  that displays the highest scores for that level (option to see player's highscore for that level or the overall highscore out of all the 
  players that've played the level). For the entire game leaderboard, players will be listed by their total lifetime points earned. 
  Give players a chance to contuine playing the game even after they've hit 3 strikes. Call these "Lives", which players can earn by 
  completing challenges.   implement a daily challenges which awards players with either points or lives. 



## License

    Copyright [Tapan Khanal]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.