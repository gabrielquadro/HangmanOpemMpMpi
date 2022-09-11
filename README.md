# HangmanOpemMpMpi

Jogo da forca com trabalho colaborativo
utilizando OpenMP e MPI desenvovlido em java.

Implementation
For the development of the game, it will be necessary to implement an interface of
game startup and player interfaces. In addition, it will be necessary to
programming language capable of easily handling parallelization and programming
parallel, since the game takes place simultaneously between the players.
With these aspects in mind, the game will be implemented in the Java language and in the Eclipse IDE.
When starting, players must be added to the game, as shown in the image below:

![image](https://user-images.githubusercontent.com/61526044/189543850-4b97ac2d-db0d-4e68-b44b-600f26cc4349.png)

From this data entry, it will be possible to perform the following operations:
Add: will add players to the game.
Start: will add the added players and start the game.
Minimize Game: Will minimize the game.

![image](https://user-images.githubusercontent.com/61526044/189543895-9808a51b-1570-4808-b6a6-be992a3226a0.png)


After starting the game, the program will create the interface for each player according to the
image below:

![image](https://user-images.githubusercontent.com/61526044/189543913-886a3851-9413-437c-8203-f8e611180b6e.png)


The game works as follows, when starting the game, one player at a time tries to
Discover the hidden word from letters chosen by players. In case the player
choose a letter that is not present in the word, the group loses a life and, if the
number of lives is 0 and the party cannot decipher the word means that the team
lost. The team is victorious if it manages to reveal all the letters of the word while the
number of lives is greater than 0. After hitting the word, the team receives 1 point in the
punctuation and a new word is generated.

![image](https://user-images.githubusercontent.com/61526044/189543955-8e5916c9-6bac-49a2-8e08-9d7d2da5e653.png)

From this interface, you can perform the following operations:
Current; indicates whose turn it is to play.
Send: sends the letter chosen by the player.
Send: send the message in chat.
Wrong letters: indicates the letters chosen by the player that are not contained in the
word.
Users: shows the players who are playing.
Performance test: performs the performance test of the program.
Total Lives: Indicates the number of available lives.
Score: informs the score of the game.

![image](https://user-images.githubusercontent.com/61526044/189543979-57d35099-5de3-48eb-89c8-6c64a7806ac4.png)

![image](https://user-images.githubusercontent.com/61526044/189543989-5c943250-7e6c-4047-80bd-69b4c2a50f37.png)


