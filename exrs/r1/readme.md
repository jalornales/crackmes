The goal is make the program print `password OK`

First, execute the program:

![try](img/01-execute.png)

By running the program, it prints the ‘Usage’ of it. The Usage gave us a hint that the password is in plaintext (hard-coded in the program).

Using the strings program, then piping it to less:

![strings](img/02-strings.png)

We will get this output:

![output](img/03-strings-out.png)

just by skimming through the text, we see the string “my_password_to_easy”, by intuition, we thought that this might be the password and try it as an argument to the program.

![password](img/04-pass.png)

and we're done.
