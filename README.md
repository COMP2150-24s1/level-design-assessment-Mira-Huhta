[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Mira Huhta
### Student number: 47908602

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.
    

    My level design facilitates the player experience goal of discovery through the gradual introduction of core mechanics and areas that are heavily punishing if the player is unable to learn said mechanics. In my first section of the level, basic mechanics of acid, spikes and enemies are introduced in quick succession but in a way that is not too punishing for the player.
    Dying to the acid will only respawn you a few steps away from it, whereas in a later encounter, the acid will set you back extremely far.
    ![This is the alt text for an image!](DocImages/playerExperience1.png)

    The narrow spike jump is used later in more stressful situations with several enemies and moving platforms to land on, but here the only threat is the spike and even if you are damaged by it, the character's invulnerable state triggers and allows you to simply step over it without taking more damage.
    The enemy is large enough to force players into taking the route above them to avoid it. Circling behind the enemy gives players the gun pickup and introduces them to a very simple enemy interaction. In later encounters, a combination of jumping and shooting and dodging projectiles is required to deal with enemies.
    These simplified encounters of the three main threats present in the level allow players to discover mechanics as they go and the placement of each threat gives players time to learn in relative safety without being too slow or boring.




    My level design facilitates the player experience goal of drama through the steady increase in difficulty created by combinations of different mechanics. Tension is built throughout the level as the player must combine mechanics they've previously encountered, culminating in a highly stressful area requiring pushing a box off a moving platform, navigating said moving platforms, shooting enemies and avoiding falling in acid.
    2 (insert screenshot of section 3 bad zone)
    This area is preceded by a calmer area of puzzle solving, that introduces moving a box off a moving platform and only contains a few enemies.
    3 (insert screenshot of section 3 puzzle area)
    These areas, coupled with places that force the player to renavigate through previously explored areas allow a player to have moments of relief from the otherwise increasingly difficult level.
    (insert screenshot of places that put u back down)




    My level design facilitates the player experience goal of Challenge through an increasingly difficult level design that combines several mechanics into a "final area". This area is located before the third key and is what I would consider to be the main challenge of the game, however, smaller challenges are present before every key that you must collect.
    The first key's challenge is the easiest, requiring the player to navigate from 2 moving platforms with an enemy spitter in the middle.
    (insert screenshot of first key area)
    This combines what the player previously learns about acid, enemies and moving platforms and is simple and relatively easy for the player to complete. In addition to the key, the player must also trigger a switch to open a door to the next section. The lack of multiple enemies and simple platforming allows players to slowly get in the flow state while being challenging for a beginning area.


    The second key's challenge becomes much more difficult.
    (insert screenshot of second key area)
    The player is teased with the staff pickup that they can see through a destructible wall (that they cannot break), forcing the player to navigate through branching paths to get to the staff. If they choose to go down branching paths, they will find the key and the switch for the next section blocked behind destructible objects, forcing them to backtrack through difficult platforming (consecutive narrow spike jumps and vertical moving platform jumps) to get the staff first. The path to the staff has a narrow spike jump onto a moving platform, along with a few enemies and vertical moving platform jumps. Getting the key requires the player to break a destructible wall, which if not carefully done will drop players back to the beginning of the first section. The switch path introduces the concept of moving a box to use as a platform to jump higher. The addition of multiple paths and more difficult mechanics allows players to fully utilise their flow state as they proceed from one challenge to the next, as well as being a middle-ground between easy and difficult so the level doesn't feel like it gets too difficult too quickly.


    The final key's challenge is a combination of challenging platforming and puzzle solving, as well as managing enemies and branching paths.
    (insert screenshot of third area)
    Firstly, the key is hidden behind a breakable wall, forcing players to explore every branching path. The platforming is incredibly challenging, with moving platforms that are very small, as well as countless enemies. Once the key is obtained the player must still fight through a small area packed with enemies before the level is complete. This combination of puzzle solving, enemy management and challenging platforming is the perfect final challenge that requires players to be precise with their movements and make few mistakes.




    My level design facilitates the player experience goals of exploration through the use of branching paths and environment design that alludes to areas beyond line of sight. From the second section onwards, the game requires you to take multiple paths to continue. Some paths that do not directly progress the game reward players with health pickups, again encouraging them to explore. Areas have different plants and details to allow players to recognise and remember places they may need to go.
    (insert screenshots of tree places)
    The placement of clouds in one area point toward the path that the key is on,
    (insert cloud bit)
    The stalactites in the background tell players that the area they're in continues upward.
    (section 1)
    The flower in acid that is pointing towards the left hints players that the box on the platform should be moved in that direction.
    (box moving puzzle intro)
    These are the main examples of the environment alluding to different areas or hinting the player to where things are. The game's requirement of exploring several branching paths along with rewards for non-necessary ones, and the careful placement of decor in the environment all contribute to inviting the player to explore.


### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 
    include areas of puzzle solving and jumping that are calm

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid
Acid is introduced first to the player as it is used frequently throughout the rest of the level and is in my opinion the easiest mechanic to understand. Additionally, as the acid spawns the player back at the beginning or nearest checkpoint, I wanted it to not be annoying for players to backtrack to the encounter if they fall in.

### 2.8. Spikes
Spikes are introduced second to the player as they are frequently used thorughout the level in increasing difficulty and it is important for player's to understand their mechanics.

### 2.9. Spitters ### 2.7. Passthrough Platforms ### 2.10. Weapon Pickup (Gun)
Spitters, passthrough platforms and the gun are all introduced at the same time. Forcing players to jump through the passthrough platform as they have nowhere else to go due to the spitter blocking their way teaches them how the platforms work as well ass that spitters are enemies that hurt you. I think the gun has to be introduced at the same tinme as an enemy as it teaches players that shooting will kill enemies.

### 2.6. Moving Platforms
Moving platforms are introduced to the player in a low risk environment where dying in the acid below it doesn't send them back too far. Jumping onto a moving platform requires more precise inputs which is why it is introduced after more simple obstacles such as the acid or spikes.


### 2.2. Checkpoints ### 2.4. Health Pickups
Checkpoints and health pickups are introduced at the same time, allowing players to take damage, learn they respawn at the checkpoint and then heal directly afterwards. They are introduced later as they require the player to have progressed enough to have taken damage and to feel as if they are no longer at the spawnpoint.

### 2.5. Keys
Keys are introduced after most obstacles, allowing these obstacles to be used to block the path of the key.

### 2.3. Chompers
The chomper is introduced quite late so as to not overwhelm players with too many enemy types at once and instead allow them to get used to shooting enemies that won't move toward them.

### 2.11. Weapon Pickup (Staff)
The staff is introduced last as its main use as a tool to destroy walls and columns is more complicated and requires players to have a basic knowledge of the other mechanics so that destructible objects can be implemented in interesting ways.



## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

### 3.2. Level Map – Section 1

### 3.3.	Level Map – Section 2

### 3.4.	Level Map – Section 3

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.


## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


