import java.until.Scanner;
public class productApp
{
privet final static Scanner scanner
= new Scanner (System.in);
private final staatic string[] menuItems
={"Έξοδος", "Προσθήκη προιόντος", "Ενημέρωση προιόντων", "Αναζήτηση προιόντων", "Διαγραφή προιόντος", "Έλεγχος πλήθους προιόντων", "Εμφάνιση προιόντων"};
static void printMenu()
{
int i = 0;
for (String item: menuItems)
{
System.out.printf("%d ->%s\n", i, item);
i++;
}
}
static int requesAction()
{
int choise;
printMenu();
System.out.println("Επέλεξε προιόν από το μενού:");
choice = scanner.nextInt();
return choice;
}
