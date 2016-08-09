# Deck Application

## Table of Contents

* Introduction
* Running the Program
* Compile the Program


## Introduction:

This program solves a coding problem that involves shuffling a deck of cards. It will determine how many rounds it will take to put a deck back into the original order.

## Brief Logic

  - Create a deck of cards
  - Clone the deck of cards into a buffer
  - If it's odd-numbered index, put the card into the table then pop the first element of the array
  - Otherwise, if it's even-number index, shift the array to the left
  - Do the above steps till the deck is empty
  - Compare the original deck vs. the table

## Running the Program:

1. Download `deckapp.txt` and rename the file to `deckapp.exe` 
  
2. Run it in a command-line or console with a specified parameter - which is the number of cards:
  
  ```
  C:\deckapp> deckapp 13 
  ```

  The program will compare the original deck vs cards on the table on each round.

  ```
  compare original deck vs. table:
  Ac 2c 3c 4c 5c 6c 7c 8c 9c 10c Jc Qc Kc
  Ac 3c 5c 7c 9c Jc Kc 4c 8c Qc 6c 2c 10c
  is Equal? False
  ```


   The final output would be the number of rounds that it took to put the deck back into the original order.
     
## Compile the Program

  * Pre-Requisites:

    - Visual Studio (Community Edition 2015 or Pro/Enterprise)
    - .NET Framework,Version=v4.5.2
  
1. Extract the file `ConsoleApplication1.zip`. This will automatically create a folder named `ConsoleApplication1`.

2. Run `Visual Studio`, then Open the solution file (`DeckApplication.sln`)

3. Set the parameter in `Project-><Projectname> Properties`. Then click on the `Debug` tab and fill in your arguments in the textbox called `Command line arguments`

4. Hit Save

5. Hit `F5` or `Ctrl+F5`.