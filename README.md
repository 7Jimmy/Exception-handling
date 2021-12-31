# Exception-handling
#include<iostream>
using namespace std;
int main(){
	int a,b;
	int x;
	
	cout<<"Enter two values"<<endl;
	cin>>a>>b;
	try{
		x=a/(a-b);
		if(x!=0){
			cout<<"Result="<<x;
			
		}
		else
		throw(x);
	}
	catch(int x){
		cout<<"x=0"<<endl;
	}
	
	return 0;
}
