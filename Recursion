#include<iostream>
using namespace std;
int fact(int n);
int main(){
    int n;
    cout<<"Enter the value: ";
    cin>>n;
    int  result=fact(n);
    if (result==-1)
        cout<<"Factorial does not exist for negative integers. ";
    else
        cout<<"Factorial of the given value : "<<result;
return 0;
}
int fact(int n){
    if (n<0)
        return -1;
    else if (n==0 || n==1)
        return 1;
    else
        return n*fact(n-1);
}
