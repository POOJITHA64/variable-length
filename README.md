# variable-length
class A 
{
    static void fun1(int a,int b)
    {
        System.out.println("non variable arguments");
        System.out.println("the value of a is"+a);
        System.out.println("the value of b is"+b);
    }
    static void fun(int c)
    {
        System.out.println("variable arguments");
        System.out.println("the length of c is:"+c.length);
        System.out.println("the arguments are");
        for(int i:c)
        {
            System.out.println(i);
        }
    }
}
class Main 
{
    A.fun1 (45,67);
    A.fun ();
    A.fun (12,34,56,78);
}

