# shortcut-key-s
This post is for the coders who loves to use keyboard over mouse . Generally if you want to open any application , you move the cursor on that application and open it . But for some coders it's just irritating to use mouse if you are using keyboard for writing lines of code continuously because it's just break rhythm .

So i made a C++ program to overcome this 'irritation' , i made various shortcut keys for opening applications at any time anywhere.I used the concept of key logger here .
For example :

If i want to open cmd then i just need to type cmd anywhere , it will open cmd.
If i want to open music player then i just need to type music anywhere , it will open music player.
If i want to open Facebook then i just need to type udit anywhere , it will open Facebook site.

What i am doing is i intercept what key is pressed and then matches the ASCII code of that key with the cases. If match occurs then it will check next keystroke else loop breaks. If match occurs till last condition then it will open application that you linked with those keywords.
It does not matter where you type (notepad , chat , desktop ) it just need you to press keys and application associated with those keywords will be opened by program.

Video : https://youtu.be/xXnfW_pzV-c
Blog : http://udit043.blogspot.in/2015/11/customize-shortcut-keys-using-c.html
