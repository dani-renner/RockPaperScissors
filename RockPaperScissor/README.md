# Rock! Paper! Scissors!

#### Play rock paper scissors by yourself (:

#### By Dani Renner and Glen Buck

## Technologies Used

* C#
* MSTest

## Description
_This program takes in two possible moves and tells which one wins, or if it's a draw! It runs in the console._

## Specifications
Describe Play()

Test: "It should gather Player 1's element choice" Expect(Play(userinput)).toEqual("Rock");
Test: "It should gather Player 2's element choice" Expect(Play(userinput)).toEqual("Paper");

Describe: Winner();

Test: It should determine which element wins
Expect: Winner(rock, paper).toEqual("Paper covers rock! Paper wins!");
Test: It should determine whether there is a tie.
Expect: Winner(rock, rock).toEqual("Tie!")

## Setup/Installation Requirements


* You can clone the repository to your desktop
* enter "dotnet run" (without the quotes) in the terminal to start

## Known Bugs

* 
* 

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright © 2021 Dani Renner

All Rights Reserved

## Contact Information

Dani Renner danijrenner@gmail.com
Glen Buck glenbuck503@gmail.com
