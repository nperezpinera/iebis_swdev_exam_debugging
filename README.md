# iebis_swdev_exam_debugging solution
The first bug was explained during class. The regex "." was missing "\\", which was added.

The first bug I found was the fact that the first letter of the word before the email was not printed (the letters in the switch case). The problem was the single quotes, since the correct format is double quotes. This was changed and the letters were printed.

The second bug is that the code only outputs "Tour". This problem is that the cases keep playing out regardless of whether the previous ones were correct. I was unable to fix this.

Finally, the bound for the random int was incorrect. The cases are 0, 1, and 2. This means that the bound should be set at 3, as otherwise case 2 will never play out.

These are all the bugs in the code. Unfortunately I was unable to fix one of them within the time constraints.
