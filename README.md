# GDIM 33 In-Class Activities
## W1
### Activity 1
[W1 brainstorming ideas](https://miro.com/app/board/uXjVGoEk1YI=/?share_link_id=195517737741)

1. My inspiration images show that I am really interested in 2D games that have simple movement and a strong atmosphere. The kind of games that come to my head first are either a top-down 2D game, a running game, or a 2D platformer, all of which are built around moving through space, avoiding dangers, and needing to react quickly. I also found that the horror genre has really strong atmospheres and is easy to do, such as a closed island setting. These ideas inspired me to have a game with a mysterious, tense feeling where the player is trapped in one place and has to keep moving forward. Overall, the game pattern that I would like to create is a small-scale 2D game with easy core mechanics, but with a darker horror mood and an isolated visual style. 
2. I talked with one of the tablemates, and he said that his idea was also close to the horror genre. He was inspired by the show Supernatural and wants to make a top-down 2D ghost-hunting game where the player can build a team and use strategy to hunt ghosts. A really interesting idea, he said, about his setting is that the main character, who controls and forms the team, is actually a ghost too, but a good ghost that will help humans. I think there are a lot of similarities between my thoughts and his, because we both like horror settings, 2D game design, and also game ideas that can create a dark and mysterious atmosphere. We are also both thinking about game ideas that can be creative without being too complicated for a student project.
3. After I talked with my LA, Eric, about his taste in games, he said that he really likes multiplayer FPS games such as GTFO and Deep Rock Galactic. I think his taste is pretty similar to mine because those games can also create a lot of tension, danger, and action, which connects to the horror and survival feeling that I am interested in. Even though I am deciding to make a 2D platformer instead of an FPD, we both seem to like games where the player has to stay alert, react quickly, and also needs to deal with threatening situations. And I also think that we have a common liking for games that have a strong atmosphere and make the player feel pressure during gameplay.

### Activity 2
![GDIM 33 break down - Frame 1](https://github.com/user-attachments/assets/569fc37b-f900-4fe6-af85-497cb8d25dc3)


## W3
### Activity 1
![New update break-down](https://github.com/user-attachments/assets/55656017-8f0d-480b-a9e0-94875035a928)

### Activity 2
1. Saving the event name for the explore-to-dialogue transition as a Scene variable is helpful because a Scene variable can be shared across different graphs in the same scene. That makes it much easier to keep the event name consistent. If I want to change the event name later, I only need to change it in one place instead of editing many nodes by hand. And I think it also makes the graph a little cleaner and easier to understand.
2. I really think that using a Debug.Log() node helped me test my graphs step by step before the whole system was finished. For example, I could click the walrus and check the Console to see if the click event was really firing. That helped me know whether the problem was in the click graph, the custom event, or the state transition, and also, it was useful because I did not have to guess where the bug was.
3. The Set Cursor Lock State is not really important for my Vertical Slice right now. My game is a 2D platformer, so that means I need the player not to need the same mouse-look control as the Week 3 activity. Because of that, locking and unlocking the cursor is not one of the core mechanics of my project. And I may still use cursor settings later for menus or UI, but it is not a major part of the gameplay loop I pitched in the draft right now.
4. I do think that the idea of a game state is relevant to my Vertical Slice. My project's aim to has different parts of gameplay, like normal platforming, having no power-up, having the light power-up, fighting the boss, and reaching the end. A state system can really help organize those changes more clearly, because each state can control different behavior, appearance, or abilities. For example, my player can have a NoPower state and a Powered state, and the game can also later use states for the final enemy or win/lose conditions.

Continue adding additional headers below this one for future weeks and future activities.
