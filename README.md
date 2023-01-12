# sqtBot
This project was primarily made to learn C++, API requests, and the Windows API. The main goal was to eliminate the need for user input and resemble human behaviors when it comes to in-game actions. Menu was created using Dear ImGui and DirectX11 and HTTP requests were made using the WinInet library.

It's far from perfect, but it's a start.

# Key Features
<b>Currently Supported Champions: Yuumi | Soraka</b>

- Custom Behavior adjustable in UI

![image](https://user-images.githubusercontent.com/117426200/212136021-7f43de2d-e64a-443a-97e7-a7641df8daa0.png)  
<i>*settings are saved locally in the same directory</i>

- Instant Login
- Instant Lobby Creation (with roles!)
- Automated Queue/Champ Select
  - Automatic Hover
  - Instant Random Ban Pick
  - Rune Adjustment/Select
- In-Game Behavior
  - Item Purchasing
  - Heal Teammate when missing health detected
  - Spell Targetting (using bitmaps in memory to detect specific colors)
  - Use Summoner Spells
  - Automatic "Yes" FF vote
- Additional Settings
  - Disable API to run solely off of pixel detection
  - Automatically rename exe
  - Hide menu interface from screenshots/stream
