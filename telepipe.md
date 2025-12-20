# [Telepipe](https://modrinth.com/plugin/telepipe)
This website is powered by Telepipe. Telepipe is a web-based teleporting system for Minecraft. Some of the tags in this guide are custom.

## Format (for Admins)
```json
"id": {
    "x": 0,
    "y": 0,
    "z": 0,
    "pitch": 0,
    "yaw": 0,
    "world": "world",
    "images":"https://fragmc.github.io/assets/images/lobby/1.png,https://fragmc.github.io/assets/images/lobby/2.png",
    "name": "example",
    "description": "example",
    "author": "example",
    "verified": 1,
    "verified-no-cp": 1,
    "difficulty": 1
}
```
X,Y,Z, Pitch, Yaw, World = Position<br>
Images = The images displayed (separated by commas)
Name = The name shown on the website
ID = The ID of the map
Description = The description
Author = The author of the map
Verified, Verified No CP = Excactly what it says (Has to be 1 or just not there)
Difficulty = 1: beginner 2: casual 3: intermediate 4: pro 5: god