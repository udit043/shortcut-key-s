# shortcut-key-s
This project is for the coders who loves to use keyboard over mouse. Generally if you want to open any application, you move the cursor on that application and open it. But for some coders it's just irritating to use mouse if you are using keyboard for writing lines of code continuously because it's just break rhythm.

So I have created a C++ program to overcome this 'irritation', I have made various shortcut keys for opening applications at any time anywhere. I have used the concept of key logger here.
For example :

If I want to open cmd then I just need to type cmd anywhere, it will open cmd.
If I want to open music player then I just need to type music anywhere, it will open music player.
If I want to open Facebook then I just need to type udit anywhere, it will open Facebook site.

What I am doing is, I intercept what key is pressed and then matches the ASCII code of that key with the predefined cases. If any match occurs then it will check next keystroke else loop breaks. If match occurs till last condition then it will open the application associated with those keywords.

It does not matter where you type (notepad, chat, desktop, anywhereelse ), it just needs you to press keys and application associated with those keywords will be opened by program autocatically.


Video : https://youtu.be/xXnfW_pzV-c
Blog : http://udit043.blogspot.in/2015/11/customize-shortcut-keys-using-c.html
