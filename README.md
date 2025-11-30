#include<iostream>

using namespace std;
int main()
{
  int temp;
cout<<"Enter room temperature in celsius";
cin>>temp;
if(temp < 15)
{
cout<<"Room is too cold,turn on the heater";
}
else if(temp>=15 && temp<=25)
{
  cout<<"Room temperature is normal,No action needed";
}
else if(temp>25 && temp<=35)
{
  cout<<"Room is warm ,turn on the fan";
}
else 
{ 
  cout<<"Room is too hot,Turn on the AC";
}
