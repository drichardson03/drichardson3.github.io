### 1 to 100 Guessing Game
## Flowchart Diagram of my Guessing Game

```mermaid

flowchart LR;
    %% The beginning of the game
    A([Let's Begin!])--B(Guess a number 1 to 100!);
    %% This is where a number will be chosen
    B--C([Guessed number is chosen]);
    %% User will chose a number and see if its correct
    %% If the number is correct, then the user can play again
    C--D([You got it! Wanna play again?]);
    %%If the user is incorrect, then they will be asked to play again
    C--E([Computer checks if user answer is correct]);
    %% If the number is too high, then they will be asked to try again
    E--F([Too High! Please guess Again]);
    %% If the number is too low, then they will also be asked to try again
    E--G([Too Low! Please guess Again!]);
    %% If the user types something that is not a number or a number outside of the range, they will be asked to try again
    E--H([Wrong input! Try again, please!]);
    %% If the choice is not acceptable, the user will have to try again
    F--B;
    G--B;
    H--B;
    D--A;
    %% They will have to choose a new number.
```    
