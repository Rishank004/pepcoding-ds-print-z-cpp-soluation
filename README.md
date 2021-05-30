# pepcoding-ds-print-z-cpp-soluation

#include<iostream>
using namespace std;
int main(int argc, char** agrc){
    cout<<"*****"<<endl;
    cout<<"   *"<<endl;
    cout<<"  *"<<endl;
    cout<<" *"<<endl;
    cout<<"*****"<<endl;
}







another soluation// 


#include<iostream>
using namespace std;
int main(){
    int i,n,j,h;
    cin>>n;
    
    for(i=0;i<n;i++){
      if(i==0 || i==n-1){
        for(j=0;j<n;j++){
          
                cout<<'*';
                
            }cout<<'\n';
      }
            else{
            for( h=0; h<n-1-i;h++){
                cout<<" ";
                
        }      
        cout<<"*";  cout<<'\n'; 
            }
