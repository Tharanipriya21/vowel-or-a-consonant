//To find given alphabet is a vowel-or-a-consonant
#include<stdio.h>
#include<conio.h>
void main()
{
char ch;
char alphabet,a,e,i,o,u;
do{
printf("Enter the alphabet");
scanf("%s",&alphabet);
if(alphabet=='a'||alphabet=='e'||alphabet=='i'||alphabet=='o'||alphabet=='u')
{
printf("The given alphabet is a vowel");
}
else
{
printf("The given alphabet is a consonant");
}
printf("Do you want to check for another alphabet");
ch=getche();
}while(ch=='Y'||ch=='y');
getch();
}
