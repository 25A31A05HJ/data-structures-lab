#include<iostream>
using namespace std;
class node
{
   public:
   int data;
   node *link;
};
 int main()
{
  node *top=NULL,*cn=NULL,*t=NULL;
  int val,op;
  do
   { 
    cout<<"1:PUSH\n2:POP\n3:PEEK\n4:DISPLAY\n5:EXIT\n CHOOSE ANY    ONE OPTION";
     cin>>op;
     
    switch(op)
       { 
          case 1: cn = new node();
                  
                  cout<<"enter node data";
                  cin>>val;
                  cn->data= val;
                  cn->link= NULL;
                  
                  if(top == NULL)
                  {
                     top=cn;
                     t=cn;
                  }
                 else
                  {
                    cn->link=t;
                    top=cn;
                    t=cn;
                  }
                  break;
         case 2: if(top ==  NULL)
                     cout<<"stack is underflow or empty";
                    else
                    {  cout<<top->data<<" is popped";
                       top = cn->link;
                       cn->link=NULL;
                       delete t;
                     }
                    break;
			case 3 : if(top ==  NULL)
			                     cout<<"stack is underflow or empty";
			             else
			                     cout<<top->data<<"is top node’s data";
			              break;
			case 4: if(top ==  NULL)
			                     cout<<"stack is underflow or empty";
			           else
			                {
			                   t=top;
			                   while(t!=NULL)
			                      {
			                           cout<<t->data<<" ";
			                           t=t->link;
			                     }
			                 }
			             break;
			case 5: exit(0);
			default: cout<<"INVALID OPTION SELECTED";
			}
			cout<<"enter 1 to continue or 0 to exit";
			cin>>op;
			}
			while(op);
			}
