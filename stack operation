#include<stdio.h>
#include<conio.h>
int top,x,stack[100],ch,n,i;
void push();
void pop();
void show();
int main()
{
top=-1;
printf("enter the number of element in the stack:");
scanf("%d",&n);
while(ch!=4){
printf("enter the choice:");
scanf("%d",&ch);
switch(ch){
case 1:
{
push();
break;
}
case 2:
{
pop();
break;
}
case 3:
{
show();
break;
}
case 4:{
break;
}
default:
{
printf("\ninvalid choice:");
}
}
}
return 0;
}
void push()
{
if(top >= n-1)
{
printf("stack overflow:");
}
else{
printf("enter the value to push:");
scanf("%d",&x);
top++;
stack[top]=x;
}
}
void pop()
{
if(top<=-1)
{
printf("stack underflow");
}
else{
printf("popped value is %d:",stack[top]);
top--;
}
}
void show(){
if(top<0){
printf("stack is empty:");
}
else{
for(i=top;i>=0;i--){
printf("%d\n",stack[i]);
}
}
}
