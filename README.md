Lutemon Battle Out Android Studio Zip File: [LutemonBattleOut.zip](https://github.com/user-attachments/files/21467784/LutemonBattleOut.zip)

# Lutemons: Battle Out!
Inspired by Pokémon, ‘Lutemons: Battle Out!’ is a simple game for users to collect Lutemons, train them to increase their experience points (XP), and battle out to earn awards. Users can collect, train, and battle their Lutemons against other Lutemons! If the user wins against the enemy, they gain experience points (commonly referred to as XP) and level up!


## Members of Group Random Access
1. Shania Adittee Karim (00087972)
2. Suthinee Segkhoonthod (Suthinee Segkhoonthod)


## Game Features
### Home Page (Main Activity) 🏠
The Home Page displays all collected Lutemons in a card-based layout. Each card shows the Lutemon’s name, image, type, XP, and level. A counter in the top-right shows the total number of Lutemons in the user's collection. By tapping a Lutemon's card (View Details Activity), a scrollable popup appears with detailed information including type, XP, description, abilities, weaknesses, and awards.

To add a new Lutemon, users press the “Add Lutemon” button on the first card. This opens a new screen with a searchable RecyclerView list of available Lutemons. Each Lutemon card includes an info popup and an “Add to Collection” button, which triggers a confirmation dialog. Upon selecting "Yes," the Lutemon is added to the user’s collection.

### Training Page 🦾
Lutemons can increase XP by training with a randomly chosen opponent of similar strength. The user selects a Lutemon, and the game generates an opponent with comparable XP. Both characters are displayed with star bars and selectable attack/defense options.

Training ends when a Lutemon's health reaches zero. If the user’s Lutemon wins, XP is awarded and the victory is announced. Users can exit training at any time using the Home or Battle icons, with a confirmation dialog to prevent accidental exits.

### Battle Page 👾
Battles are high-stakes gameplay where Lutemons can win awards and gain larger XP boosts. The user chooses a Lutemon, and the game randomly generates a stronger opponent.
The opponent strikes first, followed by the user's choice of move. Health bars for both Lutemons track progress. The game announces victory with a huge star graphic or defeat with a retry/X screen. A retry button is provided in case of loss. As with training, users can exit via Home or Training icons, with a confirmation prompt


## UML Diagram 
<img width="210" height="278" alt="image" src="https://github.com/user-attachments/assets/0b7b5628-3b0d-4015-b225-124b8ac18e9f" />


## User Interface Designs
<img width="119" height="254" alt="image" src="https://github.com/user-attachments/assets/ed3161ac-7151-4128-adad-7cdc8c5298b0" />
<img width="119" height="254" alt="image" src="https://github.com/user-attachments/assets/6be4eeb6-67eb-4363-a13c-2904d6cfc01a" />
<img width="119" height="254" alt="image" src="https://github.com/user-attachments/assets/809cec63-e65c-4df6-ae2d-730a052ef697" />


## Utilized Tools
- UI Design: Figma 
- Programming Language: Java 
- Coding Platform: Android Studio (with Groovy as build configuration)
- ChatGPT: Additional assistance tool for providing coding issues elucidation (e.g., inappropriate functionality implementation and build configuration errors)


## Demonstration Video 
🔗 Link to demonstration video of the project work: https://lut-my.sharepoint.com/:f:/r/personal/shania_adittee_student_lut_fi/Documents/LUTEMON%20VIDEO?csf=1&web=1&e=fgao4C
