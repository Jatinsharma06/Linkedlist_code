#include <iostream>
using namespace std;
class Node {
public:
    int data;      
    Node* next;    

    Node(int data) {
        this->data = data;
        this->next = NULL;
    }
};
Node* createNode(int data) {
    Node* newNode = new Node(data); 
    return newNode;                 
}

int main() {
    Node* node = createNode(10);

    cout << "Data in the new node: " << node->data << endl;

    if (node->next == NULL) {
        cout << "Next pointer of the new node is NULL." << endl;
    }
delete node;

    return 0;
}

Output:
Data in the new node: 10
Next pointer of the new node is NULL.
