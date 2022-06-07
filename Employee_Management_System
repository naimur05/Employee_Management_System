#include<iostream>
#include<string.h>

#include<conio.h>

#include<windows.h>

#include <stdlib.h>

using namespace std;

struct emp{

	string name,id,designation,department,address,bloodgroup,admin,username,password;

	int salary,contact,age;

};

int total=0;

emp e[1000];

void empdata(){

	int user=0;
	cout<<"\t\t------------------------------------------------------"<<endl;
	cout<<"\t\t                        DATA ENTRY"<<endl;
	cout<<"\t\t------------------------------------------------------"<<endl;

	cout<<"\n\t\t How many employees data do you want to enter?"<<endl;



	cin>>user;

	for(int i=total;i<total+user;i++){

		cout<<" \n\t\t      Enter data of employee \n\n"<<i+1<<endl<<endl;

		cout<<"\n\t\t Enter employee name: ";

		cin>>e[i].name;

		cout<<"\n\t\t Enter id: ";

		cin>>e[i].id;

		cout<<"\n\t\t Enter designation: ";

		cin>>e[i].designation;

		cout<<"\n\t\t Enter department: ";

		cin>>e[i].department;

		cout<<"\n\t\t Enter age: ";

		cin>>e[i].age;

		cout<<"\n\t\t Enter blood group: ";

		cin>>e[i].bloodgroup;

		cout<<"\n\t\t Enter address: ";

		cin>>e[i].address;

		cout<<"\n\t\t Enter contact: ";

		cin>>e[i].contact;

		cout<<"\n\t\t Enter salary: ";

		cin>>e[i].salary;

	}

	total=total+user;

}

void show(){

	if(total!=0){

	for(int i=0;i<total;i++){

		cout<<"\n\t\t\t\t Data of employee "<<i+1<<endl;

		cout<<"\n\t\t Name: "<<e[i].name<<endl;

		cout<<"\n\t\t ID: "<<e[i].id<<endl;

		cout<<"\n\t\t Designation: "<<e[i].designation<<endl;

        cout<<"\n\t\t Department: "<<e[i].department<<endl;

        cout<<"\n\t\t Age: "<<e[i].age<<endl;

        cout<<"\n\t\t Blood group: "<<e[i].bloodgroup<<endl;

		cout<<"\n\t\t Address: "<<e[i].address<<endl;

		cout<<"\n\t\t Contact: "<<e[i].contact<<endl;

		cout<<"\n\t\t Salary: "<<e[i].salary<<" BDT"<<endl;

	}

    }

    else{

    	cout<<"\n\t\t No data is entered"<<endl;

	}

}

void search(){

	if(total!=0){

	string id;
	cout<<"\t\t-------------------------------------------------"<<endl;
	cout<<"\t\               DATA SEARCH"<<endl;
	cout<<"\t\t-------------------------------------------------"<<endl;

	cout<<"\n\t\t Enter id of employee which you want to search"<<endl;

	cin>>id;

	for(int i=0;i<total;i++){

		if(e[i].id==id){

		cout<<"\n\t\t Data of employee "<<i+1<<endl;

		cout<<"\n\t\t Name: "<<e[i].name<<endl;

		cout<<"\n\t\t ID: "<<e[i].id<<endl;

		cout<<"\n\t\t Designation: "<<e[i].designation<<endl;

        cout<<"\n\t\t Department: "<<e[i].department<<endl;

        cout<<"\n\t\t Age: "<<e[i].age<<endl;

        cout<<"\n\t\t Blood group: "<<e[i].bloodgroup<<endl;

		cout<<"\n\t\t Address: "<<e[i].address<<endl;

		cout<<"\n\t\t Contact: "<<e[i].contact<<endl;

		cout<<"\n\t\t Salary: "<<e[i].salary<<" BDT"<<endl;

		break;

		}

		if(i==total-1){

			cout<<"\n\t\t No such record found"<<endl;

		}

	}

}else{

	cout<<"\n\t\t No data is entered"<<endl;

     }

}

void update(){

	if(total!=0){

	string id;
	cout<<"\t\t-------------------------------------------------"<<endl;
	cout<<"\t\t                  UPDATE DATA"<<endl;
	cout<<"\t\t-------------------------------------------------"<<endl;

	cout<<"\n\t\t Enter id of employee which you want to update"<<endl;

	cin>>id;

	for(int i=0;i<total;i++){

		if(e[i].id==id){

		cout<<"\n\t\t\t\t Old data of employee "<<i+1<<endl;

		cout<<"\n\t\t Name: "<<e[i].name<<endl;

		cout<<"\n\t\t ID: "<<e[i].id<<endl;

		cout<<"\n\t\t Designation: "<<e[i].designation<<endl;

        cout<<"\n\t\t Department: "<<e[i].department<<endl;

        cout<<"\n\t\t Age: "<<e[i].age<<endl;

        cout<<"\n\t\t Blood group: "<<e[i].bloodgroup<<endl;

		cout<<"\n\t\t Address: "<<e[i].address<<endl;

		cout<<"\n\t\t Contact: "<<e[i].contact<<endl;

		cout<<"\n\t\t Salary: "<<e[i].salary<<" BDT"<<endl;

		cout<<"\n\t\t\t\t Enter new data"<<endl;

		cout<<"\n\t\t Enter employee name: ";

		cin>>e[i].name;

		cout<<"\n\t\t Enter id: ";

		cin>>e[i].id;

		cout<<"\n\t\t Enter dsignation: ";

		cin>>e[i].designation;

		cout<<"\n\t\t Enter department: ";

		cin>>e[i].department;

		cout<<"\n\t\t Enter age: ";

		cin>>e[i].age;

		cout<<"\n\t\t Enter blood group: ";

		cin>>e[i].bloodgroup;

		cout<<"\n\t\t Enter address: ";

		cin>>e[i].address;

		cout<<"\n\t\t Enter contact: ";

		cin>>e[i].contact;

		cout<<"\n\t\t Enter salary: ";

		cin>>e[i].salary;

		break;

		}

		if(i==total-1){

			cout<<"\n\t\t No such record found"<<endl;

		}

	}

}else{

	cout<<"\n\t\t No data is entered"<<endl;


    }
}


void del(){

	if(total!=0){

	int press;

	cout<<"\n\t\t Press 1 to delete specific record"<<endl;

	cout<<"\n\t\t Press 2 to delete full record"<<endl;

	cin>>press;


	if(press==1){

		string id;
		cout<<"\t\t-------------------------------------------------"<<endl;
	    cout<<"\t\t                DELETE DATA"<<endl;
	    cout<<"\t\t-------------------------------------------------"<<endl;


		cout<<"\n\t\t Enter id of employee which you want to delete"<<endl;

		cin>>id;

		for(int i=0;i<total;i++){

			if(e[i].id==id){

				e[i].name=e[i+1].name;

				e[i].id=e[i+1].id;

				e[i].designation=e[i+1].designation;

				e[i].department=e[i+1].department;

				e[i].age=e[i+1].age;

				e[i].bloodgroup=e[i+1].bloodgroup;

				e[i].address=e[i+1].address;

				e[i].contact=e[i+1].contact;

				e[i].salary=e[i+1].salary;

				total--;

				cout<<"\n\t\t Your required record is deleted"<<endl;

				break;

			}

			if(i==total-1){

			cout<<"\n\t\t No such record found"<<endl;

		}

		}

	}

	else if(press==2){

		total=0;

		cout<<"\n\t\t All record is deleted"<<endl;

	}

	else{

		cout<<"\n\t\t Invalid Input"<<endl;

	}

}else{

	cout<<"\n\t\t No data is entered"<<endl;

}

}

main(){
    start:
    cout<<"\t\t-------------------------------------------------"<<endl;
	cout<<"\t\t           EMPLOYEE MANAGEMENT SYSTEM            "<<endl;
	cout<<"\t\t-------------------------------------------------"<<endl;

	  string username,password;

    cout<<"\n\n\n\t\t\t\t     LOGIN"<<endl;

	cout<<"\n\t\t\t Enter username: ";

	cin>>username;

	cout<<"\n\t\t\t Enter password: ";

	cin>>password;

	cout<<"\n\n\t\t\t Verrifing";

	for(int i=0;i<3;i++)

	{

		cout<<".";

		Sleep(500);

	}


	if(username=="mahi"&&password=="3023")

	{

	system("CLS");

	char ch;

	while(1){
    cout<<"\t\t-------------------------------------------------"<<endl;
	cout<<"\t\t               ADMINISTRATOR MENU"<<endl;
	cout<<"\t\t-------------------------------------------------"<<endl;
	cout<<"\n\t\t Press 1 to Data Entry"<<endl;

	cout<<"\n\t\t Press 2 to Data Show"<<endl;

	cout<<"\n\t\t Press 3 to Data Search"<<endl;

	cout<<"\n\t\t Press 4 to Data Update"<<endl;

	cout<<"\n\t\t Press 5 to Delete Data"<<endl;

	cout<<"\n\t\t Press 6 to Logout"<<endl;

	cout<<"\n\t\t Press 7 to Exit\n"<<endl;

	ch=getch();

	system("CLS");

	switch(ch){

		case '1':

			empdata();

			break;

		case '2':

			show();

			break;

		case '3':

			search();

			break;

		case '4':

			update();

			break;

		case '5':

			del();

			break;

        case '6':

			goto start;

			break;

		case '7':

			exit(0);

			break;

		default:

			cout<<"\a  Invalid Input"<<endl;

			break;

	}

}

}

 else{

  	cout<<"\n\t\t\a  Invalid username/password\n\n";
  	Sleep(3000);

  	goto start;

  }




    FILE  *fPtr;

    char ch;


    fPtr = fopen("data.txt", "r");


    if(fPtr == NULL)
    {

        printf("Unable to open file.\n");
        printf("Please check whether file exists and you have read privilege.\n");
        exit(EXIT_FAILURE);
    }



    printf("File opened successfully. Reading file contents character by character. \n\n");

    do
    {

        ch = fgetc(fPtr);

        putchar(ch);

    } while(ch != EOF);

    fclose(fPtr);


    return 0;
}
