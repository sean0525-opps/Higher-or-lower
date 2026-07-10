# Higher-or-lower

The game first takes the users name this is for more personalised answers then it computes 2 random integers then those integers are converted to ASCII. The game then asks the users if the 1st integer is higher or lower than the 2nd integer. To compute the answers the program compares the two integers to figure out if the user is correct. The program also checks how many questions were answered right in a row and how many lives the user has. The way the conversion from int to ASCII is that the instruction xor rdx, rdx clears the remainder register. The program then sets rcx to 10 because the number will be divided by 10 to separate the digits. The quotient is then stored in rax and the remainder is stored in rdx.

<img width="864" height="1066" alt="image" src="https://github.com/user-attachments/assets/f90ed14c-847a-4b80-a580-ca39fd3f4295" />

Figure 1 The winning output for the full Higher or lower game.

<img width="855" height="588" alt="image" src="https://github.com/user-attachments/assets/35704cce-8bb4-4296-b680-d2ddaa664993" />

Figure 2 The losing output for the full Higher or lower game.

