//insertion operation on single inked list
#include<iostream>
using namespace std;
class node
{
	public:
	int data;
	node*link;
};
main()
{
      node *h=NULL, *cn=NULL, *t =NULL;
	  int value,op;
	  do{
	  	cn = new node();
		  cout<<"enter node data";
		  cin>>value;
		  cn->data= value;
		  cn->link=NULL;
		  if(h==NULL)
		  {
		  	h=cn;
		  	t=cn;
		  }
		  else
		  {
		  	t->link=cn;
		  		t=cn;
		  }

	  cout<<"\ndo you want to continue (1/0)";
	  cin >>op;
}while (op);

//displaying the linkedlist data 
cout<<"\nLINKED LIST DATA\n";
       t=h;
       while(t!=NULL)
       {
       	cout<<t->data<<" ";
       	t=t->link;
	   }

//insertion of node
t=h;
cn = new node();
		  cout<<"\nenter new  node data";
		  cin>>value;
		  cn->data= value;
		  cn->link=NULL;
		  cn->link=t;h=cn;
		  
		  //displaying the nodes
		  cout<<"\nLINKED LIST DATA\n";
       t=h;
       while(t!=NULL)
       {
       	cout<<t->data<<" ";
       	t=t->link;
	   }
}
