# treasure
Clone the shell html file from https://github.com/RuinExplorer/treasure.git

You are going to create a small game. In this game, the user is presented with a treasure map and searches for a hidden treasure by clicking various locations on the map. With each click (event) the game updates the player with a hint using a cold-hot scale similar to a common children's game where the player is told they are getting 'warmer' as they approach an item.

(1 point) To make this game, you will need to establish the coordinates of the hidden treasure.

(3 points) Then, on each click event, calculate the distance between the treasure and the click event...
(3 points) updating the player with the number of clicks and how close they are with a verbal hint (don't disclose the distance).

(2 points) Use percentages for distance so the game can scale. Take the average side length of the map for your base distance (it's 700px btw).

    win condition = click within 2% of treasure
    hint = "Boiling hot!" within 2.5%
    hint = "Really hot" within 5%
    hint = "Hot" within 10%
    hint = "Warm" within 20%
    hint = "Cold" within 40%
    hint = "Really cold" within 80%
    hint = "Freezing!" for anything worse

(1 point) Use the "distance" element to update the player with status and number of clicks

(2 points) on the win condition - alert the player that they have found the treasure and how many clicks it took and then
rest the game (with a new hidden treasure location) so the player can start again if they wish.

(1 point) After 50 clicks, alert the player that the game is over and reset the game so the player can try again.

(2 points) Style as desired, add meaningful dialogue to keep the player informed on the state of the game.
