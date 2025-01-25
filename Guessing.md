flowchart TD
    A[Start] --> B[Generate secret number]
    B --> C[Ask user to guess a number]
    C --> D{Is the guess correct?}
    D -->(Yes) E[Player wins!]
    D -->(No) F[Provide feedback (higher or lower)]
    F --> C
    E --> G[End]
    F --> G
Explanation of the flowchart:
A is where the game starts.
B is where the system generates a random secret number.
C is where The player is prompted to guess the secret number.
D is where The game checks if the guess is correct.
If Yes, the player wins and proceeds to E.
If No, feedback is given, and the game loops back to C for another guess.
E happens if the guess is correct, the player wins and the game ends at G.
F happens If the guess is incorrect, feedback is given (told "higher or Lower") and the player is asked to guess again.
G is the End of the game.
