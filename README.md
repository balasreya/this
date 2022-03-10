# this
class student
{
    int a,b,c;
    student(int a,int b,int c)
    {
    this.a=a;
    this.b=b;
    this.c=c;
    }
    void display()
    {
        System.out.println("enter the of a"+a);
        System.out.println("enter the of b"+b);
        System.out.println("enter the of c"+c);
        
    }
}
class Main
{
    public static void main(String[]args)
    {
        student s1=new student(11,22,33);
        s1.display();
    }
}
