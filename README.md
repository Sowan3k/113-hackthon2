# 113-hackthon2
Wordgame
Description: "The Kingdom's Spellbreaker" is an engaging word guessing game set in a fantasy world. The game revolves around a kingdom under attack by a wicked witch. The player takes on the role of a Spellbreaker, whose mission is to break the witch's spells and free the kingdom from her curse. To achieve this, the player must correctly guess a series of shuffled words, with each correct guess breaking one of the spells. The game presents the player with random words from a dictionary, shuffles their letters, and challenges the player to guess the original word within a time limit. With each successful guess, the player earns points and progresses towards breaking the spells. However, failing to guess a word or exceeding the maximum number of failed attempts will end the game. The player must break a total of five spells by guessing fifteen words correctly to restore peace to the kingdom. With a captivating storyline, challenging gameplay, and a variety of words to guess, "The Kingdom's Spellbreaker" offers an immersive and entertaining experience for players seeking adventure and wordplay in a magical realm. 
Features: "The Kingdom's Spellbreaker" game features can be described segmentwise as follows:
1. Storyline: The game incorporates a captivating storyline where a kingdom is attacked by a wicked witch. The player takes on the role of a Spellbreaker to break the witch's spells and free the kingdom.
2. Word Guessing Gameplay: The core gameplay involves guessing shuffled words within a given time limit. The player receives random words from a dictionary, and their letters are shuffled to challenge the player's word recognition skills.
3. Spellbreaking Progression: Each correct word guess breaks one of the witch's spells. The player needs to guess a total of fifteen words correctly to break all five spells and restore peace to the kingdom.
4. Time Limit and Guess Count: The player has a limited time of ten seconds to guess each word. If the player fails to guess a word within the time limit or exceeds the maximum guess count, the game may end.
5. Score System: The game keeps track of the player's score, which increases with each correct word guess. The score reflects the player's progress and success in breaking the spells.
6. Player Interaction: The game prompts the player to enter their name and displays personalized messages throughout the gameplay, providing an immersive experience.
7. Additional Features: The game allows players to load previous game scores, add words to the dictionary, and displays a spell-breaking message when a spell is successfully broken. The game also includes proper error handling and clear screen functionality for enhanced user experience.
With these features, "The Kingdom's Spellbreaker" offers an engaging and challenging word guessing experience within a rich fantasy narrative, encouraging players to embark on a quest to save the kingdom from the wicked witch's curse.

how to play? To play "The Kingdom's Spellbreaker," follow these steps:

1. Launch the game and read the captivating storyline about a kingdom under attack by a wicked witch.
2. Enter your name as the Spellbreaker, who will break the witch's spells and save the kingdom.
3. The game will present you with a shuffled word from the dictionary on the screen. The letters of the word will be rearranged.
4. Within a time limit of ten seconds, analyze the shuffled letters and try to guess the original word.
5. Type your guess and press Enter to submit it. If your guess is correct, you will break one of the witch's spells.
6. The game will display a spell-breaking message and award you points for your success.
7. The process repeats as you are presented with a new shuffled word to guess. Try to guess and break as many spells as you can.
8. Remember, you need to break a total of five spells by guessing fifteen words correctly to free the kingdom from the witch's curse.
9. If you fail to guess a word within the time limit or reach the maximum number of failed attempts, the game may end. You can choose to start a new game or exit.
10. Enjoy the challenge, improve your word recognition skills, and strive to achieve a high score as you progress through the game.
"The Kingdom's Spellbreaker" offers an immersive word guessing experience intertwined with a captivating storyline, making it an engaging adventure for players seeking to break the witch's spells and save the kingdom.
Object-oriented concepts were used:
The development of "The Kingdom's Spellbreaker" game utilized several object-oriented concepts, enhancing the code structure and promoting modular design. Here's how these concepts were incorporated:

1. Encapsulation: Class objects were created to encapsulate related data and functionality. The `Game` class encapsulates the game logic, word manipulation, and player information. Encapsulation ensures data integrity and allows for better code organization.
2. Abstraction: Classes were used to represent abstract entities such as the game itself, the player, and the dictionary. Each class has defined attributes and methods, abstracted away the implementation details and provided a clear interface for interaction.
3. Inheritance: Inheritance was employed to create derived classes inheriting properties and behavior from base classes. For example, the `Game` class is inherited from the `Player` class, enabling access to player-related data and methods.
4. Polymorphism: Polymorphism was utilized through function overloading and virtual functions. Different versions of functions were implemented to handle various scenarios, such as shuffling the letters of a word and displaying game messages. Virtual functions allowed for dynamic dispatch and flexibility in method implementation.
5. Composition: Objects were composed by combining multiple classes to create more complex structures. For instance, the `Game` class utilizes the `Dictionary` class to store and retrieve words, and the `Player` class to manage player-related information. Composition allows for code reuse and promotes modular design.
6. Data Hiding: The principles of information hiding were followed by using private member variables and accessor methods. This ensures that internal implementation details are hidden and accessed only through appropriate methods, maintaining data encapsulation and preventing direct manipulation.
7. Class Relationships: Multiple classes were used to establish relationships, such as the association between the `Game` class and the `Dictionary` class. This association allows the game to load words from the dictionary and incorporate them into gameplay.
By incorporating these object-oriented concepts, "The Kingdom's Spellbreaker" game benefits from improved code organization, modularity, reusability, and encapsulation, making it easier to understand, maintain, and extend the game's functionality.

.

How linked lists/stacks/queues play a role in your game

In "The Kingdom's Spellbreaker" game, linked lists play a crucial role in storing and managing the words from the dictionary. Here's how linked lists are used:
1. Storing Words: The game reads words from the "Dictionary.txt" file and dynamically creates linked list nodes to store each word. Each node in the linked list represents a word from the dictionary.
2. Random Word Selection: To provide a random word for the player to guess, the game traverses the linked list and selects a node randomly. This ensures that each play session offers a different word from the dictionary.
3. Word Shuffling: When a word is selected from the linked list, the game shuffles the letters of the word to create a challenging puzzle for the player. This shuffled word is then presented to the player for guessing.
4. Progression and Node Removal: As the player successfully guesses a word and breaks a spell, the corresponding linked list node is removed. This progression is achieved by manipulating the links between nodes, effectively removing the completed word from the linked list.
5. Word Refresh: Once all the words in the linked list have been guessed and the spells are broken, the game can refresh the linked list by re-reading words from the "Dictionary.txt" file. This ensures that the player can continue playing and breaking spells with a new set of words.
By utilizing linked lists, "The Kingdom's Spellbreaker" game effectively manages and manipulates words, enabling random word selection, shuffling, progression, and refreshing of the game's vocabulary. Linked lists provide a flexible and efficient data structure to store and process the words, enhancing the gameplay experience.

youtubelink: https://youtu.be/1APTsHRgnuo
