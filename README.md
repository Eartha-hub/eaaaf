#include <iostream>

using namespace std;

int main() 
{

string username1,username2,M,F,gender;
double password1,password2,number1,number2;
int choice,grade,b,c;
char a;
bool v= false,f=false,login=false,k=false;


 


cout<<"\nWELCOME TO PORGRAM\n" ;

while(!login){
cout<<"\n######Register######";


cout<<"\nEnter username : " ;
cin>>username1;

cout<<"\nEnter password : " ;
cin>>password1;
cout<<"\n Login to Menu ";
cout<<"\nEnter username : " ;
cin>>username2;
cout<<"\nEnter password : " ;
cin>>password2;

cout<<"\nChoose gender : M-1,F-2 ";
cin>>gender;


if(username1==username2&&password1==password2) {
}else if (username1!=username2&&password1!=password2){
 cout<<" worng password " ;
 login =true;
 }



while(!f){

cout<<"Welcome To Login (Press show user)"<<endl;
cout<<"---Login Success---" <<endl;
cout<<"username : " << username2 << endl;
cout<<"password : " << password2  <<endl;
cout<<"gender   : " << gender <<endl;

while(!v){

cout<<"Press Menu"<< endl; 
  cout<<"1.Calculator"<<endl;
cout<<"2.Grade" <<endl;
cout<<"3 to Exit"<<endl;
cin>>grade;

switch(grade){
case 1: 

while(grade==1){ 
                        cout<<"###################### Press number example (_+_=?)###################### "<<endl; 
                        cout<<"Select to Menu " <<endl; 
                        cout<<"Enter Number : " ; 
                        cin>>number1; 
                        cout<<"Enter Number : "; 
						cin>>number2; 
                        cout<<"Select Operator"<<endl; 
                        cout<<"1.positive(+)"<<endl;
                        cout<<"2.Minus(-)"<<endl; 
                        cout<<"3.Nultipled()"<<endl;
                        cout<<"4.Divide(/)"<<endl;  
                        cout<<"###################### Press Select : ###################### "<<endl; 
                        cin>>grade;
						
                           switch (grade) {
                           case 1:
                            
                            cout<<number1<<"+"<<number2<<"="<<(number1+number2)<<endl;
                            
                            break;
                         case 2:
                              cout<<number1<<"-"<<number2<<"="<<(number1-number2)<<endl;
                            break;
            
                        case 3:
                                cout<<number1<<"*"<<number2<<"="<<(number1*number2)<<endl;
                                break;
                        case 4:
                                cout<<number1<<"/"<<number2<<"="<<(number1/number2)<<endl;
                                
                                break;
                           }

   cout<<"PRESS MENU NUMBER"<<endl;
                cout<<"1.Again" <<endl;
                cout<<"2.To grade"<<endl;
                cout<<"3.TO Register"<<endl;
                cout<<"4.Welcome To Login (Press show user)"<<endl;
                cout<<"5.Menu"<<endl;
                cin>>grade;
                if(grade==4){
                f = false;
                }else if(grade==3){
                	login = true;
				}else if(grade==5){
					v =true;
				}
				
				}
            }
             
				 
				 
			
switch (grade){
 case 2:
 while(grade==2){
     
 


cout<<"###################### Press Grade Number ######################" <<endl; 
cout<<"Enter grade"<< endl; 
cin>>grade;
if(grade>=90&& grade<100){ 
                    cout<<"A"<<endl;

            }else
                if(grade>=80&&grade<90){
                    cout<<"B"<<endl;
                    
            }else
                if (grade>=70&&grade<80){
                    cout<<"C"<<endl;
                    
                }else
                    if(grade>=60&& grade<=70){
                        cout<<"D"<<endl;
                        
                    }else
                        if(grade>0&& grade<60){
                            cout<<"F"<<endl;
                        }else if(grade<0||grade>100){
                        	cout<<"error";
						}
                    }
                }
                
            cout<<"PRESS MeNU NUMBER"<<endl;
            cout<<"1.Again" <<endl;
            cout<<"2.Register"<<endl;
            cout<<"3.Welcome To Login (Press show user)"<<endl;
            cout<<"4.To Calculator "<<endl;
            cout<<"5.Press Menu"<<endl;
            cin>>grade;
        
				}
            }
			}
		
    

}




