# tkinter-game-guess
Generate Secret Number:

A random number between 1 and 100 is generated as the secret number using the random.randint(1, 100) function.
Check Guess Function:

The check_guess function is defined to compare the user's input guess with the secret number.
The user's guess is retrieved from the Entry widget, converted to an integer, and stored in the guess variable.
The function compares the guess with the secret number and updates a result label to provide feedback to the user:
If the guess is correct, it displays "WINNER !!"
If the guess is less than the secret number, it displays "Little more !"
If the guess is greater than the secret number, it displays "Little less !"
Tkinter Window Setup:

The Tkinter window is created using Tk().
The window is titled "Guess the number !" using window.title("Guess the number !").
User Interface Elements:

A label instructs the user to guess a number between 1 and 100.
An Entry widget allows the user to input their guess.
A "Check" button triggers the check_guess function when clicked.
A result label displays the outcome of the guess.
Styling:

The font of the instruction label is set to 'keep on truckin' with a size of 20, and the text color is set to blue.
The "Check" button has a blue background and white foreground.
Event Loop:

The Tkinter event loop (window.mainloop()) is started to run the application, allowing the user to interact with the GUI.
The user can enter a guess, click the "Check" button, and receive feedback on whether their guess is correct or needs adjustment. The game continues until the user correctly guesses the secret number.






