D. Fixed Password 
from - Codeforces

<< How I solved it >>

1 >> The user gives multiple inputs. I will run test cases based on user input.
I will declare a variable where I keep taking input from the user until the correct password is given.

Logic >>
while(scanf("%d", &x) != EOF)

2 >> Now I will use a simple if-else condition to check whether the password is correct or not.
If the password is correct, print "Correct" and use the break statement to stop taking input.
Otherwise, print "Wrong" and continue taking input from the user until the correct password is entered.

Here I am using EOF (End of File).

Logic >>
int password = 1999;

if (x == password)
{
    printf("Correct");
    break;
}
else
{
    printf("Wrong");
}

Courtesy - My mentor Mr. Rahat Khan


