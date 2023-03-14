# java-assign-13-03
###1.Create programme for the given pattern:

*****
*****
*****
*****
*****
```
public class pattern
{
    public static void main(String[] args) {
        int row = 5, i, j;
        for (i = 1; i <=row; i++) {
            for (j = 1; j <= row; j++)
                System.out.print("* ");
            System.out.print("\n");
        }
    }
}
```

###2.
*********
 *******
  *****
   ***
    *
```
public class pattern2
{
    public static void main(String[] args)
    {
        for(int i=5;i>=0;i--)
        {
            for(int j=0;j<=5-i;j++)
            {
                System.out.print("  ");
            }
            for(int k=1;k<=(2*i-1);k++)
            {
                System.out.print("* ");
            }
            System.out.print("\n");
        }
    }
}
```

###3.
*
**
***
****
*****
****
***
**
*

```
public class pattern3
{
    public static void main(String[] args)
    {
        for(int i=0;i<5;i++)
        {
            for(int j=0;j<=i;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
        for(int i=5-1;i>=0;i--)
        {
            for(int j=0;j<=i-1;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```
