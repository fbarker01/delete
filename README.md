# Bingo
![the world in a marble](DALL·E 2022-11-16 09.58.36.png)
This is an online bingo game. Here is the data diagram:

## Team
Name | Email | Phone
--- | --- | ---
john | john@example.com | (555) 555-5555
jane | jane@example.com | (555) 555-5556
jerry | jerry@example.com | (555) 555-5557

## APIs
[Join Game](README.md#join-game)

[Place Wager](README.md#Place-Wager)

[Draw Cards](README.md#Draw-Cards)


## Join Game
This API allows the user to join game. It uses the "GET" HTTP method.

Sample Call:
```http
http://bingo.com/api/joingame?name=Frances

```
This allows a player named Frances to join the game.

sample Response: 
```javascript
{"status":"success"}
```
Sample Error:
```javascript
{"status":"fail - player not old enough"}
```
## Place Wager

##Draw Cards
