#include<iostream>
using namespace std;
int main()
{
	int i,j,n,c,n1=0;
	cout<< " enter the number of limited perfect numbers :";
	cin>>n;
	for(i=0;i<=n;i++)
	c=0;
	{
		for(j=1;j<i;j++)
		{
			if(i%j==0)
			{
				c+=j;
			}
		}
		if(i==c)
		{
			cout<<i<<"\n";
			n1++;
			if(n1==n)
         break;
		}
		
	}
	return 0;
}
