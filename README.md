# Siobhan-Baines-MS2-Harry Potter-Themed-Game

The concept of this game is to follow a random light pattern generated automatically by the game once the player has started the game. In the first round the game will randomly select one of the 4 house crests and light it up. The player will need to 'click-on' the crest that lit up to be able to move to the next round. In the second round the crest from the first round will light up and the game will randomly select another of the 4 house crests to light up which could be the same as the first one. The player then needs to 'click' both crests in the same order as the game lit them. 
If the player is successful they will receive a message from Dobby the house elf.
If the player is unsuccessful they will receive a message from the house of the last crest in the pattern for that round of the game and will be taken back to the beginning of the game ready to start again.

 ![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/reference%20documents/testing%20images/ami_responsivedesign.png)

[View the live project here](https://siobhanbaines.github.io/Siobhan-Baines-MS2-HP-Game/)


## User Experience (UX)

### *User Stories*

1. **A new visitor to the site**
I am looking for a game that will help improve my memory, is easy to play and looks fun. The instructions need to easy to access and follow. It might be interesting to know aout the background to the game and its design. I love Harry Potter.
  
2. **The site creator**
I want a game that uses different coloured lights to create a 'copy me' routine. The game must give feedback in a fun way relating to Harry Potter and the Hogwarts houses. 
* Gryffindor are known for their bravery, helping others and chivalry
* Slytherin are known for their ambition, cunning, heritage and resourcefulness
* Hufflepuff are known for their hardwork, patience, loyalty and fair play
* Ravenclaw are known for their intelligence, knowledge, forward planning and humour.
Since I am using Harry Potter as the theme I feel it is only right to talk a little about the author of Harry Potter in an about section.

### *Strategy*
The objective of this project is to create an interactive and fun game for a player which they will want to play again and again. A player must want to interact with the website and the website must inturn react to the interaction of the player. When the player first enters the website, I want it to look exciting and make them want to 'have a go'. When the player is playing the game, I want the game to give the player feedback. Everything in the site must be relevant to Harry Potter.
### *Scope*
The concept of the game is based on the 'Simon' game of the 1980's in the style of Harry Potter. 
#### *In Scope*
Clicking on the crest on the landing page will take the player to the game.
There will be a play-button infront of the 4 house crests to enable the player to start the game.
The game will randomly select which house to light up.
Each house must be able to light up if the game selects it.
On subsequent levels the game must add a new randomly selected house to the list of houses to light up and each house must light up separately in sequence.
If the player successfully replicates the pattern, a message needs to appear letting them know and allowing them to click on the screen to return to the game at the next level. 
If the player is unsuccessful, a message relating to the house that was the last to be selected by the game must appear and when the player clicks on the message the game must return to the start of the game.
There needs to be a menu containing an instructions page and a page about both Harry Potter and J K Rawling to give background to the game. 
#### *Out of Scope*
It would be nice for the game to have a leader board and the ability to create a user account so that the player could compete against friends.

### *Structure*
The school crest will appear in the centre of the screen
The house crests will be grouped together in sqaure in the centre.
The win and lose messages will appear in the centre of the screen.
A dropdown menu will allow the player access to instructions of how to play the game and some details about the story of Harry Potter and the author, J K Rawling.

### *Skeleton*
#### Wireframes
###### Initial Design
[Desktop](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/89767e01a22aba418c6e45b7f594a5c2a83a05ab/reference%20documents/wireframes/MS2-HP-Game_Desktop.pdf)
[Tablet](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/89767e01a22aba418c6e45b7f594a5c2a83a05ab/reference%20documents/wireframes/MS2-HP-Game_Tablet.pdf)
[Mobile](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/89767e01a22aba418c6e45b7f594a5c2a83a05ab/reference%20documents/wireframes/MS2-HP-Game_Mobile.pdf)

###### Design modifications
Since the original design there have been some changes.
1. Originally there was only going to be a menu travelable instructions page but I decided to add an about page creating the need for a menu to select the pages.
The menu was moved to the left-hand side because, when using the bootstrap navbar 'hamburger icon' on the right on smaller devices, the icon jumped left to expand the dropdown menu which I thought looked untidy.  
2. I decided against a score tally because it seemed unnecessary for the enjoyment of the game. Instead, I decided the player would have a better UX if a recognisable friendly character from Harry Potter congratulated them. I tried to keep the wording of the message in tune with the character.
3. The wording of the losing messages stayed very close to the orignal design with some adjustments to help with the cosmetic UX.
4. My mentor suggested a wooden background for the losing messages and my daughter suggests a piece of parchment which was more in keeping with the Harry Potter theme.
5. I also decided clearing the screen and showing the losing message in the centre was more impactful and would be easier to read on smaller devices.

### *Surface*
1. The images I am using on the wesite include the school crest, the four house crests, Dobby and some parchment.(see below under Media)
2. The four house crests will act as the four buttons and give the colors red, green, yellow and blue which will have the ability to illuminate.
3. The background will be a dark regal/magical purple.
4. The headings will be in a bright yellow to represent gold.
5. The win message will appear below Dobby in yellow with a red boarder.
6. The lose messages will appear on the parchment in black.
The font on the main game pages will be in the 'Parry Hotter' font which is similar to the real Harry Potter lettering. [font by Anke Arnold](https://www.anke-art.de)
The font on the How to play and About pages will be white so it stands out from the page making it easy to read.
#### Hogwarts School Crest
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/assets/images/hogwarts_crest.png)
#### Gryffindor House Crest
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/assets/images/gryffindor_crest.png)
#### Slytherin House Crest
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/assets/images/slytherin_crest.png)
#### Ravenclaw House Crest
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/assets/images/ravenclaw_crest.png)
#### Hufflepuff House Crest
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/assets/images/hufflepuff_crest.png)
#### Parchment
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/assets/images/paper.png)
#### Dobby
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/assets/images/dobby.png)

## Features
### Existing Features
#### feature 1
When the home page loads its position and opacity changes bringing the webpage to life. 
#### feature 2
I wanted the transition from the home page to the game page to be softer to appear smoother for the player.
#### feature 3
When the player fails to follow the pattern created by the crests lighting up, a message relating to the last crest in the pattern pops up on a piece of parchment in the middle of the screen in black writing.
#### feature 4
When the player successfully follows the pattern, this image appears.
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/reference%20documents/testing%20images/dobby-screen.png)
#### feature 5
When the player does not successfully follow the pattern, these messages appear.
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/reference%20documents/testing%20images/lost-message-gryfindr.png)
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/reference%20documents/testing%20images/lost-message-slytherin.png)
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/reference%20documents/testing%20images/lost-message-hufflepuff.png)
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/360d1825cd9bcd90d9a500c425ff503ab356e807/reference%20documents/testing%20images/lost-message-ravenclaw.png)

### Future Features
#### feature 1
When the crests light up it might be fun to have a wizarding related sound for each house.
#### feature 2
The game could be expanded to become a multi-player game with the incorporation of a leader board. This would also require a scoreboard to be developed.
## Technologies Used
CSS3, HMTL5, Javscript, JQuery, Bootstrap Framework, Google, Fontawesome

##### Font style
Parry Hotter font [by Anke Arnold](https://www.anke-art.de) and Ubuntu.

## Credits
[J K Rowling](https://www.jkrowling.com/) originally created the very successful [Harry Potter](https://www.wizardingworld.com/collections/starting-harry-potter) series of books which is the core theme of this game.

### feature 1
I found out how to create the Home page movement and opacity from this YouTube video by [dcode](https://www.youtube.com/watch?v=zWB219zf1og)
### feature 3
My mentor Kyeza Arnold suggested a wooden background for the pop-up message. I found this more difficult to read and wanted a border around the font to make it stand out more. I added a black boarder and a red shadow. [css-font-border](https://stackoverflow.com/questions/2570972/css-font-border). I later changed the background to parchment which was suggested by my daughter.

I was struggling to centralise some of the items and came across this line of code in stackoverflow. Sadly, I did not keep a not of the web address or who provided it to stackoverflow. 
    left: 0; right: 0; top: 0; bottom: 0; margin: auto; /* center */
    
When using Google to find out more information about various parts of my code that were not working as I expected I often used[w3schools](https://www.w3schools.com/default.asp), [stackoverflow](https://stackoverflow.com/questions/tagged/html), [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) and [jQuery](https://jquery.com/).

### Media

The images used in this game are all free clipart available on [pinclipart](https://www.pinclipart.com) and [pngitem](https://www.pngitem.com). 
Below are the links for each piece of clipart:
[Hogwarts Crest](https://www.pngitem.com/middle/iJiiRhb_hogwarts-crest-transparent-background-hd-png-download/), 
[Gryffindor Crest](https://www.pngitem.com/middle/mRxxbi_transparent-gryffindor-png-harry-potter-house-crests-png/), 
[Slytherin Crest](https://www.pngitem.com/middle/iibxmTw_harry-potter-mug-slytherin-crest-png-download-slytherin/), 
[Ravenclaw Crest](https://www.pngitem.com/middle/TRwmxT_crest-png-for-free-download-on-ravenclaw-hogwarts/), 
[Hufflepuff Crest](https://www.pinclipart.com/pindetail/iTiJwxo_crest-banner-png-harry-potter-hufflepuff-crest-clipart/), 
[parchment](https://www.pinclipart.com/pindetail/mTmTw_old-paper-cliparts-old-burnt-paper-background-png/), 
[Dobby](https://www.pinclipart.com/maxpin/iihmho/)

I then used [icolorpalette](https://icolorpalette.com/) to get a colour palette from the Hogwarts School Crest. This did not give me the background colour.
[colour pallet](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/89767e01a22aba418c6e45b7f594a5c2a83a05ab/reference%20documents/ms2_hp_colour_pallet.pdf)
# Deployment
In Gitpod the bottom area of the screen is where git commands are entered.

1.	If you have been running the 8000 port you will need to use Ctrl + Z to escape back and use the command entry. This line will appear “gitpod /workspace/Siobhan-Baines-MS2-HP-Game $” allowing commands to be entered.
2.	Make sure any changes that have been made are save by selecting the ‘File’ tab and ‘Save All’
3.	Type “git add .” to add all the changes ready to be committed. Remember the full stop because this will add everything that has been save. If only one file has been changed that file name can be entered instead of the full stop
4.	Type “git commit -m” immediately followed by a description of the change(s) being committed to Github 
5.	Type “git push” which will push everything to Github
6.	Open Github and the repository the website is in. To the far right of the menu bar is the Settings tab. Select this and scroll down to “GitHub Pages”
7.	Under Source if the dropdown menu has “None” select the “master” branch which will bring up the “(root)” folder, and click “Save”
8.	Your page will initially show as ready to be published.
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/89767e01a22aba418c6e45b7f594a5c2a83a05ab/reference%20documents/testing%20images/deployment.png)
9.  After a few minutes the message will change and the site will be published.
![image](https://github.com/SiobhanBaines/Siobhan-Baines-MS2-HP-Game/blob/89767e01a22aba418c6e45b7f594a5c2a83a05ab/reference%20documents/testing%20images/deployed.png)