import java.util.Scanner;
public class resibojava{
public static void main (String[] args) {
 Scanner al=new Scanner(System.in);
   int a=0;
   int b=0;
   String cashname="";
    System.out.println (" PURCHASE RECEIPT SYSTEM\n INPUT DETAILS BELOW");
    System.out.println ("********************************************************");
    System.out.println ("Enter Cashier Name :");
    cashname=al.next();
    System.out.println ("Enter O.R No: :");
    b=al.nextInt();
    System.out.println ("*******************************************************\n");
    System.out.println ("Enter Number of items :");
    a=al.nextInt();
    System.out.println ("*******************************************************\n");
    String itemname[]=new String[b];
int itempri[]= new int[b];
int itemqua[]=new int[b];
Double totalpay=0.0;
int costpay=0;
Double vat=0.0;
Double vatpay=0.0;
Double change=0.0;
for (int x=0;x<b;x++)
{
System.out.println ("Enter item name: ");
itemname[x]=al.next();
System.out.println ("Enter item Quantity: ");
itempri[x]=al.nextInt();
System.out.println ("Entee item quantity: ");
itemqua[x]=al.nextInt();
System.out.println ("---------------------------\n");
totalpay=totalpay+(itempri[x]*itemqua[x]);
}
vat= totalpay/20;
vatpay=totalpay+vat;
System.out.println ("Total Payment: "+vatpay);
System.out.println ("\n*****************************************\n");
do{
System.out.println ("Enter costumer payment: ");
costpay=al.nextInt();
}
while (costpay<totalpay);
System.out.println ("***********************************************");
System.out.println ("\n SM City Mall");
System.out.println (" Mc Arthyr Highway, Digos City");
System.out.println (" Tel.no:553-2847 Fax: 679652382");
System.out.println (" GST Reg. No.00023648294");
System.out.println (" RCB:529873290\n");
System.out.println ("PURCHASE RECEIPT");
System.out.println ("Cashier:"+cashname);
System.out.println ("Date: Febuary 3,2020 O.R.No:"+b);
System.out.println ("***********************************************");
System.out.println ("QTY Item/s Price/s");
System.out.println ("------------------------------------------------");
for (int z=0;z<a;z++)
{
System.out.println (itemqua[z]+" "+itemname[z]+"+"+itempri[z]);
}
System.out.println ("*************************************************");
System.out.println ("SUBTOTAL Php "+totalpay);
System.out.println ("VAL(5%) Php "+vat);
System.out.println ("\n");
System.out.println ("TOTAL Php "+vatpay);
change=costpay-vatpay;
System.out.println ("\n");
System.out.println ("CASH Php "+costpay);
System.out.println ("%.2f",change);
System.out.println ("\n\n THANK YOU FOR SHOPPING!!");
}
}
