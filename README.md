#include<iostream>
#include<string>
using namespace std;
int main(){
    string s,t,w;
    cin>>s>>t;
    int l=s.length(),x=0;
    for (int i = 0; i <l; i++)
    {
       if(t[i]==s[l-i-1]){
             x++;
       }
    }
    if(x==l){
        cout<<"YES";
    }
    else{
        cout<<"NO";
    }
    return 0;
}
