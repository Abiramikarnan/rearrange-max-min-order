# rearrange-max-min-order
rearrange the given in max min order

#include <iostream>
using namespace std;

int main() {
	//code
	int i,j,n,n1,n2;
	int arr[100];
	cin>>n;
	cin>>n1;
	for(i=0;i<n1;i++)
	{
	  cin>>arr[i];  
	}
	
	
		for(i=n1-1,j=0;i>=n1/2;i--,j++)
	{
	    cout<<arr[i];
	    cout<<" ";
	    cout<<arr[j];
	    
	    cout<<" ";
	}
cout<<"\n";
		cin>>n2;
	for(i=0;i<n2;i++)
	{
	    cin>>arr[i];
	}

		for(i=n2-1,j=0;i>=n2/2;i--,j++)
	{
	    cout<<arr[i];
	    cout<<" ";
	    if(i==j)
	    {
	        break;
	    }
	    else
	    {
	    cout<<arr[j];
	    }
	    cout<<" ";
	}
	
	
	return 0;
}
