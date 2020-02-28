# Tic Tac Toe Tech Test

## Overview

[Makers Week 10 Individual Challenge Tech Test](https://github.com/makersacademy/course/blob/master/individual_challenges/tic_tac_toe.md)

### Application Overview

- Javascript
- JQuery

### Installation

- clone this repo
- run

```bash
> cd tic-tac-toe-tech-test
> bundle install
> rspec # to check all tests pass and show the coverage from simplecov
> rubocop # to check all tests pass
>
```

### User stories

```
As a user
So that I can play tic tac toe with other player
I want the game to have two players (X and O)
```

```
As a user
So that I can play tic tac toe in turns with other player
I want to take turns with other player until the game is over
```

```
As a user
So that I can claim a field if it is not already taken
I want to be able to pick an empty field
```

```
As a user
So that I know it's my turn
The turn ends once a player claims a field
```

```
As a user
So that I can win the game
I win when I claim all the fields in a row, column, or diagonal
```

```
As a user
So that I know the game is over
The game announces the winner when a player wins
```

```
As a user
So that the game is over
The game ends when all fields are taken
```

### The brief

The rules of tic-tac-toe are as follows:

- There are two players in the game (X and O)
- Players take turns until the game is over
- A player can claim a field if it is not already taken
- A turn ends when a player claims a field
- A player wins if they claim all the fields in a row, column or diagonal
- A game is over if a player wins
- A game is over when all fields are taken
