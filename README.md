//advanced java
//# Overridejava
//Learning override in java.
import package override; //importing package override
class Override{ //declaring class override
int x; //declaring x;
Override(int x) //declaring constructor with single argument
{
this.x=x; //Can someone tell me what this line of code does in java
void display() //creating display function
{
System.out.println("x="+x); //output x;
}
class sub extends Override //inheriting sub from override
{
int y;
sub(int x,int y) //constructor with two arguments
{
super(x); //what it does?
this.y=y; //what this line does?
}
void display() //Inheriting method from baseclass but overriding the definition 
{
System.out.println("x="+x); //output x
System.out.println("y="+y); //output y
}
public static void main[string args[]) //main function
{
sub s1 = new sub(15,10) //creating object s1 to pass value to constructor sub(int x,int y)
s1.display(); //using object to call method display for output of x and y
}
}
//please check for errors if any because this code is not running. i want to learn override in java
