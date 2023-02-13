# Linear Search Code
This repositrary consists of c++ code for searching an key via linear search through a defined array....

#include<iostream>
using namespace std;
void Search(int arr[],int size,int key){
	for(int i=0;i<size;i++){
		if(arr[i]==key){
			cout<<"Key founnd at "<<i<<"th location...\n";
			return;
		}
	}
}
void Print(int arr[],int size){
	for(int i=0;i<size;i++){
		cout<<arr[i]<<" ";
	}
}
int main()
{
	int arr[6]={1,5,4,3,-6,8};
	int brr[5]={4,6,2,3,-1};
	Search(arr,6,-6);
	Search(brr,5,6);
	Print(arr,6);
	cout<<"\n";
	Print(brr,5);
	return 0;
}
