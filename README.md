# data-of-5-employee
this program will display the data of 5 different employees

#include <iostream>
#include <cstring>
using namespace std;

struct employee{
    string name;
    string department;
    int id;
    int salary;
    string address;
};
int main(){
struct employee em1 ={"amir","nutrtion",789, 40000,"jinnah town"};
struct employee em2 ={" sherz"," biology",052, 80000,"wapda town"};
struct employee em3 ={"amar"," computer science", 653, 70000,"dtype town"};
struct employee em4 ={"ali","finance",234, 60000,"milat town"};
struct employee em5 ={"asad","agriengenreeing",854, 50000,"iqbal town"};

cout<<"employee 1 name"<<em1.name<<endl;
cout<<"employee 1 department"<<em1.department<<endl;
cout<<"employee 1 id"<<em1.id<<endl;
cout<<"employee 1 salary"<<em1.salary<<endl;
cout<<"employee 1 address"<<em1.address<<endl;


 cout<<"employee 2 name"<<em2.name<<endl;
cout<<"employee 2 department"<<em2.department<<endl;
cout<<"employee 2 id"<<em2.id<<endl;
cout<<"employee 2 salary"<<em2.salary<<endl;
cout<<"employee 2 address"<<em2.address<<endl;
    
std::cout<<"employee 3 name"<<em3.name<<endl;
cout<<"employee 3 department"<<em3.department<<endl;
cout<<"employee 3 id"<<em3.id<<endl;
cout<<"employee 3 salary"<<em3.salary<<endl;
cout<<"employee 3 address"<<em3.address<<endl;

cout<<"employee 4 name"<<em4.name<<endl;
cout<<"employee 4 department"<<em4.department<<endl;
cout<<"employee 4 id"<<em4.id<<endl;
cout<<"employee 4 salary"<<em4.salary<<endl;
cout<<"employee 4 address"<<em4.address<<endl;

 cout<<"employee 5 name"<<em5.name<<endl;
cout<<"employee 5 department"<<em5.department<<endl;
cout<<"employee 5 id"<<em5.id<<endl;
cout<<"employee 5 salary"<<em5.salary<<endl;
cout<<"employee 5 address"<<em5.address<<endl;


    return 0;
}

