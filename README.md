
#include <iostream>
#include <cmath>
using namespace std;
int main()
{
  double a=1, n ,c ,b;
  cin >> n;
  
  for(int i=0;a<=n;i++)
  {
    b=a;
    for(int x=0;b<=n;x++)
    {
      c=b;
      for(int y=0;c<=n;y++)
      {
        if(a*a+b*b==c*c)
        {
          cout << a <<" "<< b <<" "<< c << endl;
          c+=1;
          } else
          c+=1;
      }
      b+=1;
    }
    a+=1;
    }
  return 0;
}
