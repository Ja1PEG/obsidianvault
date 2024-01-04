---
tags:
  - sem5
  - C
  - computer-science
  - data-structures
---

# [[Root-Branch/Finished Courses/Data Structures|Data Structures]] How a linked List Works:

```c++
struct node{
	int val;
	node* next; //Holds the Value for the next pointer 
};

struct LinkedList{
	node* head=NULL;
	
	void append(int value){
		node newNode = new node(value, NULL)
		if(!head){
			head=newNode;
			return;
		}
		Node* current=head;
		
		while(current->next){
			current=current->next;
		}
		current->next=newNode;
	}

	void display(){
		node* current=head;
		while(current){
				cout<<current->val<<" ";
				current=current->next;
		}
		cout<<endl;
	}
};
```
