# Questions from an AngelList Quiz

3. Which one of these structures can not be used to build a stack by itself?
- Tree
- Set
- Array
- Linked List

7. Given a function to reverse a linked list, which one of these lines is not required?

``` java
public static Node reverseLinkedList(Node current) {
    Node prev = null;
    Node next;
    while (current != null) {
        next = current.next;
        current.next = prev;
        prev = current;
        prev.next = current;
        current = next;
    }
    return prev;
}
```
* `prev.next = current;`
* `current.next = prev;`
* `prev = current;`
* `current = next;`

9. What is the value of k?

``` java
int i = 4;
int j = 1;
int k = 0;
for (i = 0; i < 3; i++) {
    k += j;
    j = 1 - j;
}
```
* 5
* 4
* 1
* 2

## Answers

3. I'm pretty sure the answer is a tree..