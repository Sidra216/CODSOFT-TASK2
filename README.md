CODSOFT
class marks
{
    public static void main(String args[])
    {
        int m,p,c,e,t;
        double per;
        m=57;
        //marks in maths
        p=78;
        //marks in physics
        c=70;
        //marks in computer
        e=79;
        //marks in english
        t=p+m+e+c;
        System.out.println("Total marks in all subjects"+t);
        per=t/400.0*100;
        System.out.println("Average percentage"+per);
        if(per>=90)
        {
        System.out.println("\n Grade A");
        }
        else if(per>=80)
        {
        System.out.println("\n Grade B");
        } 
        else if(per>=70)
        {
        System.out.println("\n Grade C");
        }
        else if(per>=60)
        {
        System.out.println("\n Grade D");
        }
        else if(per>=40)
        {
        System.out.println("\n Grade E");
        }
        else
        {
        System.out.println("fail");
        }
    }
}
