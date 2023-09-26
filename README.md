# count-the-number-of-vowels-ind-given-string
import java.util.*;
public class Main{
    public static void main(String args[])
    {
        System.out.println("enter the string:-");
        Scanner sc= new Scanner (System.in);
        String str=sc.nextLine();
        char [] chars=str.toCharArray();
        int count=0;
        for(char c:chars)
        {
            switch(c){
                case'a':
                    case'e':
                        case'i':
                            case 'o':
                            case'u':
                            count++;
                            break;
            }
        }
        System.out.println("The number os vowels in string is:-"+count);
    }
}
