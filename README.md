// # Project-C-
// Departmental Management System

#include<iostream>
#include<conio.h>
using namespace std;
class wellcome
{
	public:
	int wellcome_to_store()
	{
	cout << "\n\n\t\t\t******************************************************" << endl;
	cout << "\t\t\t*                                                    *" << endl;
	cout << "\t\t\t*       WELLCOME TO SCET DEPARTMENTAL STORE          *" << endl;
	cout << "\t\t\t*                                                    *" << endl;
	cout << "\t\t\t******************************************************" << endl;	
	}
};
class costumer
{
	private:
		int choice,q[40];
		double Total;
		char ch;
	public:	
	int wellcome_costumer()
    {
    cout << "\n\n\t\t******************************************************" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t*          WELLCOME TO COSTOMER SERVICES             *" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t*      -->  CHOOSE FORM THE GIVEN LIST  <--          *" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t******************************************************" << endl;
	}
	int list()
	{
	cout<<"\n\t\t *** BAKERY ITEMS ***";
	cout<<"\n\t  1. Biscuit \t\t  6. Sandwich";
	cout<<"\n\t  2. Nimko \t\t  7. Burger";
	cout<<"\n\t  3. Fruit Cake \t  8. Pizza";
	cout<<"\n\t  4. Cake \t\t  9. Chicken Bread";
	cout<<"\n\t  5. Pastrie \t\t 10. Patis";

	cout<<"\n\n\t\t *** GENERAL ITEMS ***";
	cout<<"\n\t 11. Floar \t\t 16. Ghee";
	cout<<"\n\t 12. Grains \t\t 17. Bottle";
	cout<<"\n\t 13. Masala \t\t 18. Rice";
	cout<<"\n\t 14. Sugar \t\t 19. Wheat";
	cout<<"\n\t 15. Oil \t\t 20. Water";
	
	cout<<"\n\n\t\t *** COSMETICS ITEMS ***";
	cout<<"\n\t 21. Shampoo \t\t 26. Makeup Kit";
	cout<<"\n\t 22. Soap \t\t 27. FaceWash";
	cout<<"\n\t 23. Conditionar \t 28. Lotion";
	cout<<"\n\t 24. Tooth Paste \t 29. Hair Colour";
	cout<<"\n\t 25. Brush \t\t 30. Perfumes";

	cout<<"\n\n\t\t *** ELECTRONIC ITEMS ***";
	cout<<"\n\t 31. Washing Machine \t 36. Mobile";
	cout<<"\n\t 32. TV \t\t 37. LED";
	cout<<"\n\t 33. Oven \t\t 38. Bulb";
	cout<<"\n\t 34. Fan \t\t 39. DC Invertor";
	cout<<"\n\t 35. Bike \t\t 40. Generator";

	}
	int choose_item()
	{
		ag :
			df :
		cout<<"\n########################################################################";		
		cout<<"\n\nEnter the choice From the above list --> ";
		cin>>choice;
		switch(choice)
		{
			case 1:
			cout<<"\nYou Press 1 : Biscuit : per pack = 20 Rs ";
   		    cout<<"\nEnter quantity = ";
            cin>>q[1];
            cout<<"Price is = "<<q[1]*20;
   		    Total += q[1]*20;
			break;
			case 2:
			cout<<"\nYou Press 2 : Nimko : per pack = 40 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[2];
            cout<<"Price is = "<<q[2]*40;
   		    Total += q[2]*40;
			break;
			case 3:
			cout<<"\nYou Press 3 : Fruit Cake : per pack = 80 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[3];
            cout<<"Price is = "<<q[3]*80;
   		    Total += q[3]*80;
			break;
			case 4:
			cout<<"\nYou Press 4 : Cake : per Poun = 400 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[4];
            cout<<"Price is = "<<q[4]*400;
   		    Total += q[4]*400;
			break;
			case 5:
			cout<<"\nYou Press 5 : Pastrie : per piece = 50 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[5];
            cout<<"Price is = "<<q[5]*50;
   		    Total += q[5]*50;
			break;
			case 6:
			cout<<"\nYou Press 6 : Sandwich : per pack = 60 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[6];
            cout<<"Price is = "<<q[6]*60;
   		    Total += q[6]*60;
			break;
			case 7:
			cout<<"\nYou Press 7 : Burger : per pack = 60 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[7];
            cout<<"Price is = "<<q[7]*60;
   		    Total += q[7]*60;
			break;
			case 8:
			cout<<"\nYou Press 8 : Pizza : per pack = 90 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[8];
            cout<<"Price is = "<<q[8]*90;
   		    Total += q[8]*90;
			break;
			case 9:
			cout<<"\nYou Press 9 : Chicken Bread : per pack = 90 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[9];
            cout<<"Price is = "<<q[9]*90;
   		    Total += q[9]*90;
			break;
			case 10:
			cout<<"\nYou Press 10 : Patis : per pack = 40 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[10];
            cout<<"Price is = "<<q[10]*40;
   		    Total += q[10]*40;
			break;
			case 11:
			cout<<"\nYou Press 11 : Flaour : per kg = 80 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[11];
            cout<<"Price is = "<<q[11]*80;
   		    Total += q[11]*80;
			break;
			case 12:
			cout<<"\nYou Press 12 : Grains : per kg = 90 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[12];
            cout<<"Price is = "<<q[12]*90;
   		    Total += q[12]*90;
			break;
			case 13:
			cout<<"\nYou Press 13 : Masala : per kg = 150 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[13];
            cout<<"Price is = "<<q[13]*150;
   		    Total += q[13]*150;
			break;
			case 14:
			cout<<"\nYou Press 14 : Sugar : per kg = 90 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[14];
            cout<<"Price is = "<<q[14]*90;
   		    Total += q[14]*90;
			break;
			case 15:
			cout<<"\nYou Press 15 : Oil : per kg = 200 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[15];
            cout<<"Price is = "<<q[15]*200;
   		    Total += q[15]*200;
			break;
			case 16:
			cout<<"\nYou Press 16 : Ghee : per kg = 250 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[16];
            cout<<"Price is = "<<q[16]*250;
   		    Total += q[16]*250;
			break;
			case 17:
			cout<<"\nYou Press 17 : Bottle : per Pet = 400 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[17];
            cout<<"Price is = "<<q[17]*400;
   		    Total += q[17]*400;
			break;
			case 18:
			cout<<"\nYou Press 18 : Rice : per kg = 140 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[18];
            cout<<"Price is = "<<q[18]*140;
   		    Total += q[18]*140;
			break;
			case 19:
			cout<<"\nYou Press 19 : Wheat : per kg = 120 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[19];
            cout<<"Price is = "<<q[19]*120;
   		    Total += q[19]*120;
			break;
			case 20:
			cout<<"\nYou Press 20 : Water : per Bottle = 80 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[20];
            cout<<"Price is = "<<q[20]*80;
   		    Total += q[20]*80;
			break;
			case 21:
			cout<<"\nYou Press 21 : Shampoo : per pack = 140 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[21];
            cout<<"Price is = "<<q[21]*140;
   		    Total += q[21]*140;
			break;
			case 22:
			cout<<"\nYou Press 22 : Soap : per pack = 40 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[22];
            cout<<"Price is = "<<q[22]*40;
   		    Total += q[22]*40;
			break;
			case 23:
			cout<<"\nYou Press 23 : Conditionar : per pack = 150 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[23];
            cout<<"Price is = "<<q[23]*150;
   		    Total += q[23]*150;
			break;
			case 24:
			cout<<"\nYou Press 24 : Tooth paste : per pack = 40 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[24];
            cout<<"Price is = "<<q[24]*40;
   		    Total += q[24]*40;
			break;
			case 25:
			cout<<"\nYou Press 25 : Brush : per pack = 90 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[25];
            cout<<"Price is = "<<q[25]*90;
   		    Total += q[25]*90;
			break;
			case 26:
			cout<<"\nYou Press 26 : Makeup kit : per pack = 200 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[26];
            cout<<"Price is = "<<q[26]*200;
   		    Total += q[26]*200;
			break;
			case 27:
			cout<<"\nYou Press 27 : FaceWash : per pack = 300 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[27];
            cout<<"Price is = "<<q[27]*300;
   		    Total += q[27]*300;
			break;
			case 28:
			cout<<"\nYou Press 28 : Lotion : per pack = 250 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[28];
            cout<<"Price is = "<<q[28]*250;
   		    Total += q[28]*250;
			break;
			case 29:
			cout<<"\nYou Press 29 : Hair Colour : per pack = 130 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[29];
            cout<<"Price is = "<<q[29]*130;
   		    Total += q[29]*130;
			break;
			case 30:
			cout<<"\nYou Press 30 : Perfumes : per pack = 200 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[30];
            cout<<"Price is = "<<q[30]*200;
   		    Total += q[30]*200;
			break;
			case 31:
			cout<<"\nYou Press 31 : Wahing Machine : per box = 12000 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[31];
            cout<<"Price is = "<<q[31]*12000;
   		    Total += q[31]*12000;
			break;
			case 32:
			cout<<"\nYou Press 32 : TV : per box = 15000 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[32];
            cout<<"Price is = "<<q[32]*15000;
   		    Total += q[32]*15000;
			break;
			case 33:
			cout<<"\nYou Press 33 : Oven : per box = 4000 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[33];
            cout<<"Price is = "<<q[33]*4000;
   		    Total += q[33]*4000;
			break;
			case 34:
			cout<<"\nYou Press 34 : Fan : per box = 1500 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[34];
            cout<<"Price is = "<<q[34]*1500;
   		    Total += q[34]*1500;
			break;
			case 35:
			cout<<"\nYou Press 35 : Bike : per bike = 70000 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[35];
            cout<<"Price is = "<<q[35]*70000;
   		    Total += q[35]*70000;
			break;
			case 36:
			cout<<"\nYou Press 36 : Mobile : per box = 20000 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[36];
            cout<<"Price is = "<<q[36]*20000;
   		    Total += q[36]*20000;
			break;
			case 37:
			cout<<"\nYou Press 37 : LED : per box = 50000 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[37];
            cout<<"Price is = "<<q[37]*50000;
   		    Total += q[37]*50000;
			break;
			case 38:
			cout<<"\nYou Press 38 : Bulb : per Box = 400 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[38];
            cout<<"Price is = "<<q[38]*400;
   		    Total += q[38]*400;
			break;
			case 39:
			cout<<"\nYou Press 39 : DC Invertor : per box = 40000 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[39];
            cout<<"Price is = "<<q[39]*40000;
   		    Total += q[39]*40000;
			break;
			case 40:
			cout<<"\nYou Press 40 : Generator : per box = 15000 Rs ";
			cout<<"\nEnter quantity = ";
            cin>>q[40];
            cout<<"Price is = "<<q[40]*15000;
   		    Total += q[40]*15000;
			break;
			default :
			cout<<"\n\n\t *** YOU ENTER WRONG CHOICE ***";	
			goto df;
		}
		og:
		cout<<"\n########################################################################";	
		cout<<"\n\n\t --> Press 'y' to buy anything else press 'n' to exit ";
		cin>>ch;
		if(ch=='y')
		{
			goto ag;
		}
		else
		if(ch=='n')
		{
			cout<<"\n\n%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%";
			cout<<"\nYour Total Bill is = "<<Total;
			cout<<"\nYour General Tax (3.5%) on these items = "<<Total*0.035;
			cout<<"\n--> You have to pay *** "<<Total+(Total*0.035)<<" *** Rs for these goods. ";
			cout<<"\n\n%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%";
		}
		else
		{
			cout<<"\t You enter Wrong choice other than 'y' & 'n' ";
			goto og;
		}
	}
};
class employee
{
	private:
		string og,g;
	public:
	int login_password()
	{	
	cout<<"\n########################################################################";
	cout<<"\nEnter Your Name : ";
	cin>>g;
	ex:
	cout<<"Enter Your Password : ";
	cin>>og;
	if(og=="12345")
	{
		system("CLS");
	}
	else
	{
		cout<<"--> Sorry enter ***right password*** Please! \n";
		goto ex;
	}
	}
	int wellcome_employee()
	{
	cout << "\n\n\t\t******************************************************" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t*          WELLCOME TO EMPLOYEE SERVICES             *" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t*      -->  CHOOSE FORM THE GIVEN LIST  <--          *" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t******************************************************" << endl;	
	} 
	int list_employee()
	{
	cout<<"\n\n\t\t *** LIST FOR EMPLOYES & WORKERS MANAGEMENT ***";
	cout<<"\n\n\t 1. Stock Managemnt ";
	cout<<"\n\t 2. Department Notices ";
	cout<<"\n\t 3. Pays & Loss/Profit Managemnt ";
	}
};
class stock:public employee
{
	private:
		string date_stock,coming_date_stock;
	public:
		int wellcome_stock()
		{
	    cout << "\n\n\t\t******************************************************" << endl;
     	cout << "\t\t*                                                    *" << endl;
    	cout << "\t\t*     AVAILABEL STOCK & COMING STOCK DETAILS         *" << endl;
    	cout << "\t\t*                                                    *" << endl;
    	cout << "\t\t******************************************************" << endl;		
		}
		int available_stock()
		{
		cout<<"\n\n\t\t *** AVAILABLE STOCK ***";
		cout<<"\n --> We have contact with all the dealers and all Racks are full right now ";
		cout<<"\n --> Enter Last stock date : ";
		cin>>date_stock;	
		}
		int coming_stock()
		{
		cout<<"\n\n\t\t *** COMING STOCK ***";
		cout<<"\n --> We have contact with all the dealers and our coming stock will be soon ";
		cout<<"\n --> Enter Coming stock date : ";
		cin>>coming_date_stock;	
		}
};

class management:public employee
{
	private:
	public:
		int wellcome_management()
		{
	    cout << "\n\n\t\t******************************************************" << endl;
     	cout << "\t\t*                                                    *" << endl;
    	cout << "\t\t*          NOTICES FOR DEPARTMENTAL STORE            *" << endl;
    	cout << "\t\t*                                                    *" << endl;
    	cout << "\t\t******************************************************" << endl;		
		}
	    int management_details()
		{
		cout<<"\n\n\t\t *** SECURITY MANAGEMENT ***";
		cout<<"\n\n --> Security management contains : \n --> 3 Security Guards at Enterence Gate \n --> 2 Security gurads at Parking \n --> 5 Cameras on Parking and Enterance \n --> 18 Cameras in differnt Racks \n --> For Further details contact us at *** SECURITY ROOM *** ";
		cout<<"\n\n\t########################################################################";
		cout<<"\n\n\t\t *** CLEAN MANAGEMENT ***";
		cout<<"\n\n --> Clean Management contains : \n --> 3 Sweapers for indoor \n --> 2 Sweapers for outdoor \n --> 1 Sweaper for Parking \n --> 2 Sweapers for washrooms ";
		cout<<"\n\n\t########################################################################";
		cout<<"\n\n\t\t *** RACKS MANAGEMENT ***";
		cout<<"\n\n --> Racks Management contains : \n --> 9 Racks at Enteracnce for Costumer Things \n --> 5 Racks for Cosmetics \n --> 6 Racks for Bakery items \n --> 16 Racks for Electronics items \n --> 20 Racks for General Items ";
		cout<<"\n\n\t########################################################################";
		cout<<"\n\n\t\t *** PARKING MANAGEMENT ***";
		cout<<"\n\n --> Parking management contains : \n --> 29 Cars parking on left side \n --> 30 Cars Parking for right side \n --> 100 Bikes parking at backside \n --> 10 RS chareged for Bike per day \n --> 20 RS charged for Car per day";
		cout<<"\n\n\t########################################################################";
		cout<<"\n\n\t\t *** LIGHTS MANAGEMENT ***";
		cout<<"\n\n --> Lights management contains : \n --> 50 Flash Lights in Parking \n --> 20 Lights in Enterance \n --> 91 Lights in Hall \n --> 30 Lights in room, washrooms and security room";
		cout<<"\n\n\t########################################################################";
		cout<<"\n\n\t\t *** SPECIAL DISCOUNTS ***";	
		cout<<"\n\n --> Special discounts are only for : \n --> 50% discount for the poor people \n --> 30% discount for the employee and workers of Store \n --> 20% discounts for zakat \n --> 70% discount for needy people \n --> 20% discount on Department Costumer Care Card \n --> 10% discount on the Electronics items having Guarentee";
		cout<<"\n\n\t########################################################################";
		}
};

class loss_profit:public employee
{
	private:
		double saving,pay_emp,worker_pay,bill,rent,other_charges;
		int emp,workers;
	public:
		int wellcome_lossprofit()
		{
	    cout << "\n\n\t\t******************************************************" << endl;
     	cout << "\t\t*                                                    *" << endl;
    	cout << "\t\t*      LOSS & PROFIT FOR DEPARTMENTAL STORE          *" << endl;
    	cout << "\t\t*                                                    *" << endl;
    	cout << "\t\t******************************************************" << endl;		
		}
		int check_loss_profit()
		{
		cout<<"\n\t Enter the Total Saving of this Month --> ";
		cin>>saving;
		cout<<"\n\t Enter the number of employes --> ";	
		cin>>emp;
		cout<<"\n\t Enter the pay of each Employee --> ";
		cin>>pay_emp;
		cout<<"\n\t Enter number of workers include (sweaper , security guards , cleaners) --> ";
		cin>>workers;
		cout<<"\n\t Enter the pay of each Worker --> ";
		cin>>worker_pay;
		cout<<"\n\t Enter the bill for this month --> ";
		cin>>bill;
		cout<<"\n\t Enter the rent for this month --> ";
		cin>>rent;
		cout<<"\n\t Enter the others charges (include food , interior work) --> ";
		cin>>other_charges;
		cout<<"\n\n\t########################################################################";
		double employee_pay_total=emp*pay_emp;
		cout<<"\n\n\t You pay to Employes : "<<employee_pay_total;
		double worker_pay_total=workers*worker_pay;
		cout<<"\n\t You pay to Workers  : "<<worker_pay_total;
		double charges_total=bill+rent+other_charges;
		cout<<"\n\t You pay Total for bill , rent & other charges : "<<charges_total;
		cout<<"\n\n\t########################################################################";
		long double grand_total_charges=employee_pay_total+worker_pay_total+charges_total;
		cout<<"\n\n\t You pay Total charges are --> "<<grand_total_charges;
		long double remaining_charges=saving-grand_total_charges;
		cout<<"\n\t Your Ramining savings are   --> "<<remaining_charges;
		cout<<"\n\n\t########################################################################";
		if(remaining_charges>0)
		{
			cout<<"\n\n\t\t *** CONGRATULATIONS YOU ARE IN PROFIT ***";
			long double our_charges=remaining_charges/4;
			cout<<"\n\n\t Total charges to MARIA ASGHAR  : "<<our_charges;
			cout<<"\n\t Total charges to OSAMA GHAFOOR : "<<our_charges;
			cout<<"\n\t Total charges to WAHAB MUNIR   : "<<our_charges;
			cout<<"\n\t Total charges to SYED MUDASSIR : "<<our_charges;
			cout<<"\n\n\t########################################################################";
		}
		else
		if(remaining_charges<0)
		{
			cout<<"\n\n\t\t *** SORRY YOU ARE IN LOSS ***";
			long double our_charges=remaining_charges/4;
			cout<<"\n\n\t Total charges to MARIA ASGHAR  : "<<our_charges;
			cout<<"\n\t Total charges to OSAMA GHAFOOR : "<<our_charges;
			cout<<"\n\t Total charges to WAHAB MUNIR   : "<<our_charges;
			cout<<"\n\t Total charges to SYED MUDASSIR : "<<our_charges;
			cout<<"\n\n\t########################################################################";
		}
		}
};

class dealer:public costumer,public employee
{
	private:
	string d_name,contact,comp_name,comp_num;
	public:
	int wellcome_dealer()
	{
	cout << "\n\n\t\t******************************************************" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t*         WELLCOME TO DEALER CARE SERVICES           *" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t******************************************************" << endl;
	}
	int dealer_list()
	{	
	cout<<"\n\t 1. Bakery Items Dealer \n\t 2. Cosmetics Items Dealer  \n\t 3. General Items Dealer \n\t 4. Electronics Items Dealer\n ";	
	}	
	int add_dealer_data()
	{
	cout<<"\n########################################################################";	
	cout<<"\nEnter your name (dealer) --> ";
	cin>>d_name;
	cout<<"Enter your Contact Number --> ";
	cin>>contact;	
	cout<<"Enter Your Company Name --> ";
	cin>>comp_name;
	cout<<"Enter Your Company Number --> ";
	cin>>comp_num;
	cout<<"\n########################################################################";	
	}
};

class dealing
{
	private:
	int deal;
	string thing_name;
	int things,quant;
	double carton;
	double total_carton,total_bill_dealer;
	public:	
	int deal_dealer()
	{
	cout<<"\nThe number of things you wants to Enter (as a stock) --> ";
	cin>>things;
	cout<<"\n########################################################################";
	for(int i=1;i<=things;i++)
	{	
	cout<<"\nEnter the name of Thing --> ";
	cin>>thing_name;
	cout<<"Enter the Quantity of Thing --> ";
	cin>>quant;
	cout<<"Enter the Price per Carton --> ";
	cin>>carton;
	total_carton=quant*carton;
	cout<<"\nYou have to pay ***Total*** for the stock is --> "<<total_carton<<" Rs...";
	cout<<"\n########################################################################";	
	total_bill_dealer += total_carton;		
	}
	cout<<"\n\n Dealer's Total bill is --> "<<total_bill_dealer;
	}
	dealing() : deal(){}
	friend int dealer_bill(dealing);	
};
int dealer_bill(dealing d)
{
	cout<<"\n\n\tCongratulations --> Your Data has been Entered ";
	cout<<"\n########################################################################";	
	return 0;
}

class exit_out
{
    public :
	int exit()
	{
	system("CLS");	
	cout << "\n\n\t\t******************************************************" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t*             THANKS COME BACK AGAIN :)              *" << endl;
	cout << "\t\t*                                                    *" << endl;
	cout << "\t\t******************************************************" << endl;	
	} 	
};

int main()
{
	cout<<"\n\n\t##########################################################################################";
	cout<<"\n\t This project has been done by : \n\t 1. Wahab Munir --> 2. Maria Asghar --> 3. Mudassir Hussain Shah --> 4. Osama Ghafoor \n\t Topic : Depaertmental Store Mnagement System :) ";
    cout<<"\n\t##########################################################################################";
	exit_out e2;
	wellcome w1;
	employee e1;
	costumer c1;
	w1.wellcome_to_store();
	int chh;
	cout<<"\n\n\t --> WELL COME TELL US YOU ARE : ";
	cout<<"\n\t 1. Costumer \n\t 2. Employee \n\t 3. Dealer \n\t 4. Exit";
	cout<<"\n\n\t Enter Your Choice Here --> ";
	cin>>chh;
	if(chh==1)
	{	
	system("CLS");
    c1.wellcome_costumer();
    c1.list();
    c1.choose_item();
    cout<<"\n\n\t\t *** THANKS FOR SHOPPING HERE *** ";
	}
	else
	if(chh==2)
	{	
	e1.login_password();
	e1.wellcome_employee();
	again:
	e1.list_employee();
	hh:
	int choices;
	cout<<"\n\n\t Enter Your Choice Here --> ";
	cin>>choices;
	if(choices==1)
	{
    system("CLS");
    stock s1;
    s1.wellcome_stock();
    c1.list();
    s1.available_stock();
    s1.coming_stock();
    cout<<"\n\n\t\t *** THANKS FOR CHECK STOCK MANAGEMENT SYSTEM ***";
	cout<<"\n\n\t########################################################################";
	}
	else
	if(choices==2)
	{
	system("CLS");
	management m1;
	m1.wellcome_management();
	m1.management_details();
	cout<<"\n\n\t\t *** THANKS FOR CHECK DEPARTMENTAL NOTICE MANAGEMENT SYSTEM ***";
	cout<<"\n\n\t########################################################################";
	}
	else
	if(choices==3)
	{
	system("CLS");	
	loss_profit lp1;
	lp1.wellcome_lossprofit();
	lp1.check_loss_profit();
	cout<<"\n\n\t\t *** THANKS FOR CHECK LOSS PROFIT MANAGEMENT SYSTEM ***";
	cout<<"\n\n\t########################################################################";
	}
	else
	{
	cout<<"\n\t You Enter Wrong Choice ";
	goto hh;	
	}
	char emp_choice;
	cout<<"\n\n\t --> Press 'y' for check any other process & 'n' for exit ";
	cin>>emp_choice;
	if(emp_choice=='y')
	{
		goto again;
	}
	else
	{
		e2.exit();
	}
	}
    else 
    if(chh==3)
    {
	e1.login_password();
	system("CLS");	
	dealer d1;
	d1.wellcome_dealer();
	d1.dealer_list();
	int dealer_type;
	dc:
	cout<<"\n\t --> Which Type Of Dealer You Are : Enter Your Choice Here : ";
	cin>>dealer_type;
	if(dealer_type<=4)
	{
	deal:	
	d1.add_dealer_data();
	dealing d2;
	d2.deal_dealer();
	cout<<dealer_bill(d2);
	char ch_dealer;
	dr:
	cout<<"\n\n\t --> Press 'y' for other dealer & 'n' for exit ";
	cin>>ch_dealer;	
	if(ch_dealer=='y')
	{
		system("CLS");
		d1.wellcome_dealer();
		d1.dealer_list();
		goto deal;
	}
	else
	if(ch_dealer=='n')
	{
		e2.exit();
	}
	else
	{
	cout<<"\n\t --> You Enter Wrong Choice ";
	goto dr;	
	}
	}
	else
	{
	cout<<"\n\t You Enter Wrong Choice\n";
	goto dc;	
	}
	}
	else
	if(chh==4)
	{
	e2.exit();
	}
}

