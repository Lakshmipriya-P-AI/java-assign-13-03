# java-assign-13-03
1.Create programme for the given pattern:


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

##OUTPUT:

![image](https://user-images.githubusercontent.com/93427923/224888661-53a389f7-5043-4a0b-8932-a7d0bcb9bc7a.png)

2.
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

##OUTPUT:

![image](https://user-images.githubusercontent.com/93427923/224888796-c5361f3b-6b86-43c9-a60a-70b952d5f353.png)

3.

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

##OUTPUT:

![image](https://user-images.githubusercontent.com/93427923/224888971-3a160772-47e9-4160-9488-caad4fcb405e.png)

