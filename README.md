#include <iostream>
using namespace std;
int main()
{
  int totalweight,adults,children,maxweight=600;
  cin>>totalweight;
  cin>>adults;
  cin>>children;
  totalweight=(adults*75)+(children*30);
  if(totalweight<=maxweight)
  {
    cout<<"Boat will run.";
  }
  else{
      cout<<"Boat will drow.";
  }

}
