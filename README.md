# codealpha_task
#include<iostream>
 #include<iomanip> 
using namespace std;
 int main() {
cout<"CGPA CALCULATOR";
 int n,i,gradepoint,subject,credit,totalcredit,totalpoint,cgpa; 
char grade; 
cout<<"enter the no of subject"; 
cin>>n; 
for(i=0;i<n;i++){
 cout<<"enter the credit"; 
cin>>credit;
 cout<<"enter the grade"; 
cin>>grade;
 switch(grade){ 
case 'A': 
gradepoint=9;
break;
 case 'B':
 gradepoint=8;
break; 
case 'C': 
gradepoint=7; 
break;
case 'D': 
gradepoint=6;
break;
 default: 
cout<<"failed";
 }
 totalpoint=credit*gradepoint;
 cout<<"totalpoint"<<totalpoint<<endl;
 totalcredit=credit;
 cout<<"totalcredit"<<totalcredit<<endl;
 }
 cgpa=totalpoint/totalcredit; 
cout<<"cgpa:"<<cgpa;
 }
