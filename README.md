# Array-using-C++
#include<iostream>
using namesapce std;

int fun(int arr[],int n,int key){


	for(int i=0;i<n;i++)
	{
		if(arr[i]==key)
		{
			retrun i;
		}
	}
	retutn -1;
}

int main()
{
	int n;
	cin>>n;
	int arr[n];
	for(int i=0;i<n;i++)
	{
		cin>>arr[i];
	}
	int key;
	cin>>key;
	cout<<fun(arr,n,key);
	return 0;
}
