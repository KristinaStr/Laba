'''
#include

using namespace std;

int main()
{
unsigned int x,y,k;
char op, op1;
cin>>x;
cin>>op;
if (op=='>') {cin>>op1;}
else if(op=='<') {cin>>op1;}
cin>>y;
if(op=='+'){
k=x+y;
cout<<"result: "<<k;
}
else if(op=='-'){
k=x-y;
cout<<"result: "<<k;
}
else if(op==''){
k=xy;
cout<<"result: "<<k;
}
else if(op=='/'){
k=x/y;
cout<<"result: "<<k;
}
else if(op=='<',op1=='<'){

k =x << y;
cout<<"result: "<<k;

}
else if(op=='>',op1='>'){

k =x >> y;
cout<<"result: "<<k;

}
}
'''
