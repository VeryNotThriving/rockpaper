# rockpaper
get prompted to enter rock, paper, or scisorze. random number generator that picks between the three. three if statements that check which of the 
three you entered. against the generated value. One else statement for inputs 
other than rock, paper, or scizzors that tells you yout input is wrong.

A count of three
For each count you say one of the following in order [rock,paper,scizzors]
After the count of three say 
while loop to make sure the correct values are chosen
while(userInput != r || userInput != p || userInput != s){
    document.write("Invalid input. Please type one of the following values");
    document.write("'r', 'p', 's',");
}
 random number generator from 0-2 ->(Math.random()*2)