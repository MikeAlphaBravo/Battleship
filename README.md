# _Battleship_

#### _A digital interpritation of the classic boardgame Battleship, July, 27 2017_

#### By _**Michael Brooks, Faunie Szeloczei, Nathan Mayer, Karla Buckner**_

## Description

_This is an online version of the classic Battleship game.  It is a 2 player dependent game.  Two can battle it out guessing via a coordinate system and seeing results of hit or miss on the grid. Once one player has sunk all of their opponent's ships the game is won!_

## Specifications

| Rank | Behavior                                   | Input      | Output                   |
|------|--------------------------------------------|------------|--------------------------|
| 1    | Display 10 x 10 grid playing board         | NONE       | NONE                     |
| 2    | Display P1 ship locations on playing board | Grid Coord | span id=P1-Occupado      |
| 3    | Hide P1 ship locations on playing board    | NONE       | NONE                     |
| 4    | Display P2 ship locations on playing board | Grid Coord | span id=P2-Occupado      |
| 5    | Show P1 playing board display              | NONE       | NONE                     |
| 6    | When isHit = true display "Hit!"           | True       | "Hit!"                   |
| 7    | When isHit = false display "Miss!"         | False      | "Miss!"                  |
| 8    | isSunk = True                              | True       | "Sunk!"                  |
| 9    | isSunk = True run isShipType               | True       | log(isShipType)          |
| 10   | Display type of ship sunk                  | True       | You Sunk my Battleship!  |
| 11   | Add 1 to isGameOver                        | Sunk       | isGameover +=1           |
| 12   | If isGameOver = 5                          | 5          | log("You Won!")          |
| 13   | Display "You Won" & Game Over              | 5          | "You Won! & "Game Over!" |
| 14   | Display Winners Board Layout               |            |                          |
| 15   | When isHit = false advance player turn     | False      | turnAdvance +=1          |
| 16   | isWhoseTurn () {turnadvance % 2 === 0}     | True       | P2 Turn                  |
| 17   | isWhoseTurn () {turnadvance % 2 === 0}     | False      | P1 Turn                  |

## Setup/Installation Requirements

* _Open in browser with link below_
* _https://mikealphabravo.github.io/Battleship/_

## User experience screenshots:

![alt text](/img/header.png)

![alt text](/img/setup.png)

![alt text](/img/select.png)

![alt text](/img/miss.png)

![alt text](/img/hit.png)

![alt text](/img/hitsunk.png)

![alt text](/img/win.png)

## Known Bugs

_There are no known bugs at this time but do not hesitate to contact us if you find something of interest._

## Support and contact details

_Contact at MikeAlphaBravo1982@gmail.com_

## Technologies Used

_HTML / CSS / JavaScript / JQuery / Bootstrap_

### License

_This software is licensed under the MIT license._

Copyright (c) 2017 _**Michael Allen Brooks, Nathan Mayer, Karla Buckner, Faunie Szeloczei**_
