#include <iostream>
#include <iomanip>
#include <math.h>

using namespace std;

int main()
{
	int a;
	cout<<"number (between 1,1000) = ";
	cin>>a;
	if(a<=1000)
    {
	  switch(a)
	  {
	   	case 1000:cout<<"One thousand";break;
	  }
	  switch(a/100)
	  {
	 	case 1:cout<<" One hundred"  ;break;
	 	case 2:cout<<" Two hundred"  ;break;
	 	case 3:cout<<" Three hundred";break;
	 	case 4:cout<<" Four hundred" ;break;
	 	case 5:cout<<" Five hundred" ;break;
	 	case 6:cout<<" Six hundred"  ;break;
	 	case 7:cout<<" Seven hundred";break;
	 	case 8:cout<<" Eight hundred";break;
	 	case 9:cout<<" Nine hundred" ;break;     
	  }
       if(a%100 >=11 && a%100 <=19)
        switch(a%100)
       {
     	case 11:cout<<" Eleven"   ;break;
     	case 12:cout<<" Twelve"   ;break;
     	case 14:cout<<" Fourteen" ;break;
     	case 13:cout<<" Thirteen" ;break;
     	case 15:cout<<" Fifteen"  ;break;
     	case 16:cout<<" Sixteen"  ;break;
     	case 17:cout<<" Seventeen";break;
     	case 18:cout<<" Eighteen" ;break;
     	case 19:cout<<" Nineteen" ;break;
 	  }
      else
      {
      switch(a%100/10)
      {
     	case 1:cout<<" Ten"    ;break;
     	case 2:cout<<" Twenty" ;break;
     	case 3:cout<<" Thirty" ;break;
     	case 4:cout<<" Forty"  ;break;
     	case 5:cout<<" Fifty"  ;break;
     	case 6:cout<<" Sixty"  ;break;
     	case 7:cout<<" Seventy";break;
     	case 8:cout<<" Eighty" ;break;
     	case 9:cout<<" Ninety" ;break;
	  }
	  switch(a%10)
	  {
	 	case 1:cout<<" One"  ;break;
	 	case 2:cout<<" Two"  ;break;
	 	case 3:cout<<" Three";break;
	 	case 4:cout<<" Four" ;break;
	 	case 5:cout<<" Five" ;break;
	 	case 6:cout<<" Six"  ;break;
	 	case 7:cout<<" Seven";break;
	 	case 8:cout<<" Eight";break;
	 	case 9:cout<<" Nine" ;break;
      }
      }
    }
	else
	 cout<<"Its bigger than 1000 !!!";
}
