# CatTrivia

This is a fun cat trivia game you can enjoy by yourself or with up to 3 friends! This game works by prompting a question from the server that waits for a response from all of the clients, whether it be you or your friends. Once the server recieves a response, it will wait until the each of the players has answered and can print out the correct answer. If the answer is correct, the server checks the order in which the responses were received, with the first response coming in being the one that is awarded the point. All other players who answered incorrectly or after the first correct response will not be rewarded points. This game is created by Isabella Barnard. This was made as an assignment for CS457. 
</br>

### How to Play:
1. **Start the server:** Run the server which will prompt a question asking how many friends will be playing the game with you, or if you will be playing alone. It will then wait for all players specified to join the game before it can start.
</br>

2. **Connect clients:** Run the client on all of the player's devices so that everyone can join the game. After everyone haas connected, the game will begin by asking the first question. 
</br>

3. **Play the game:** The server asks a question after everyone has connected. It will then wait for responses from the clients. If the response is incorrect, no points will be awarded. If the response is correct, the first client to send the correct response will receive the points. All other players, even if they got the answer correct, will not be awarded any points for that round. At the end of the game, the player with the most points will be awarded the title of "WINNER!". 
</br>

**Tedhnologies Used:**
*Python
*Sockets
</br>

**Additional resources:**
* [Link to Python documentation]
* [Link to sockets tutorial]
