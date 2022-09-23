# -elab-little-lion-king-and-candy-quenstio

#include <iostream>
using namespace std;
int main()
{
 int t,N,C,temp;
 cin>>t;
 while(t--){
 cin>>N>>C;
 for (int i = 0; i < N; i++) {
 cin>>temp;
 C-=temp;
 }
 if(C>=0){
 cout<<"Yes\n";
 }
 else{
 cout<<"No\n";
 }
 }
return 0;
}
