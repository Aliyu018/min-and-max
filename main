
import javax.swing.*;
import java.util.Calendar;
import java.util.GregorianCalendar;

public class Hello
{
    public static void main (String [] args)
    {
        double a=0,Max=0,Min=0;
        int Answer = JOptionPane.showConfirmDialog(null, "Do You want to Continue? ");
        if (Answer == 0)
        Max=Min=Double.parseDouble(JOptionPane.showInputDialog("So, Enter the first Number: "));
        while(Answer==0)
        {
            Answer = JOptionPane.showConfirmDialog(null, "Do You want to Continue? ");
            if (Answer == 1) break;
            a=Double.parseDouble(JOptionPane.showInputDialog("So, Enter the next Number: "));
            if(a>Max)Max=a;
            else if(a<Min)Min=a;
        }
        JOptionPane.showMessageDialog(null,"Max= "+Max+"  Min= "+Min);
    }
}
