#include <iostream> 
#include <windows.h> 
#include <winuser.h> 
using namespace std;
void Stealth();
void Stealth()
{
  HWND Stealth;
  AllocConsole();
  Stealth = FindWindowA("ConsoleWindowClass", NULL);
  ShowWindow(Stealth,0);
}
int main() 
{
 //Stealth();
 char i;int key_stroke;int y;int m;int o;int j;
 while (1)
 {
  for(i = 1; i <= 390; i++)
  {
   if (GetAsyncKeyState(i) == -32767)
   {
     key_stroke=i;
     if (key_stroke == 67)                              //c
     {if(m==10) {y=y+1;m=m+5;o=0;j=0;} else {y=y+1;m=0;o=0;j=0;}}
     else if (key_stroke == 77)                         //m
     {if(y==1) {y=y+2;m=1;o=0;j=0;} else {y=0;m=1;o=0;j=0;}}
     else if (key_stroke == 68)                         //d
     {if(y==3||j==1) {y=y+3;m=0;o=0;j=j+2;} else {y=0;m=0;o=0;j=0;}}

     else if (key_stroke == 85)                         //u
     {if(m==1) {m=m+2;y=0;o=0;j=j+1;} else {y=0;m=0;o=0;j=j+1;}}
     else if (key_stroke == 83)                         //s
     {if(m==3) {m=m+3;y=0;o=0;j=0;} else {y=0;m=0;o=0;j=0;}}
     else if (key_stroke == 73)                         //i
     {if(m==6||j==3) {m=m+4;y=0;o=0;j=j+3;} else {y=0;m=0;o=0;j=0;}}
     else if (key_stroke == 84)                         //t
     {if(j==6) {m=0;y=0;o=0;j=j+4;} else {y=0;m=0;o=0;j=0;}}

     else if (key_stroke == 79)                         //o
     {if(o==0) {o=o+1;y=0;m=0;j=0;} else {o=o+1;y=0;m=0;j=0;}}
     else if (key_stroke == 70)                         //f
     {if(o==1) {m=0;y=0;o=o+2;j=0;} else {y=0;m=0;o=0;j=0;}}
     else if (key_stroke == 78)                         //n
     {if(o==3) {m=0;y=0;o=o+3;j=0;} else {y=0;m=0;o=0;j=0;}}


     else
     {
      y=0;m=0;j=0;o=0;
     //cout<<key_stroke;
     //printf(" %s", &key_stroke);
     }
     //cout<<"\n";
//------------------------------------------------------------------------------
                if (y==6)
                   {
                     system("start C:\\Windows\\System32\\cmd.exe"); 
                     y=0;m=0;j=0;o=0;
                   }
                if (o==6)
                   {
                     system("taskkill /f /im Project1.exe"); 
                     y=0;m=0;j=0;o=0;
                   }
                if (m==15)
                   {
                     system("start wmplayer.exe"); 
                     m=0;y=0;j=0;o=0;
                   }
                if (j==10)
                   {
                     system("start chrome.exe https://www.facebook.com/udit.tutu");
                     m=0;y=0;j=0;o=0;
                   }
                   
//------------------------------------------------------------------------------
   }
  }
 }
 system ("PAUSE");
 return EXIT_SUCCESS;
}
/*//     else if (key_stroke == 85)
//     m=2;
//     else if (key_stroke == 83)
//     m=3;
//     else if (key_stroke == 73)
//    m=4;*/
