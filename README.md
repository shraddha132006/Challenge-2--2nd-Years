This project solves 3 small problems.
where Each problem gives a clue, At the end, all clues are combined to make the Final Key.

Problem 1 :
Grid Rotation with clue1
We read a 5×5 grid of letters. Each row is rotated left or right based on instructions. After rotating all rows, we take the middle row and add the ASCII values of every character in that row.

Result is: 385
which is converted to hex decimal->181

Problem 2 :
String Processing with clue2
We take a string and reverse it , then remove every 3rd character shift each character’s ASCII code by +2,Count how many vowels are remain

result is:4

Problem 3 :
State Machine with Clue 3
We have a list of numbers ,each number moves through states based on simple rules:
 Prime numbers jump straight to the final state.
 Even numbers move forward by one state.
 Odd composite numbers stay where they are.
 We count how many reach the state.

result is:5

Final Key:
The final key is created by convert 385 to hex= 181
Repeat 4 exactly 5 times → 44444

Join them with a dash: 181-44444
