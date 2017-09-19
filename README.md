# Questions from an AngelList Quiz

3.

Which one of these structures can not be used to build a stack by itself?
- Tree
- Set
- Array
- Linked List


7.

Given a function to reverse a linked list, which one of these lines is not required?

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


11. What's the run-time complexity of this function?

``` java
int mystery(int n) {
    if (n == 0) return 0;
    if (n == 1) return 1;
    return mystery(n-1) + mystery(n-2);
}
```

* O(1)
* O(n)
* O(mystery)
* O(2^n)


12. What does this function do?

``` python
def mystery(alist):
    for index in range(1, len(alist)):
    pos = index
    current = alist[index]
    while pos > 0 and alist[pos-1] > current:
        alist[pos] = alist[pos-1]
        pos = pos - 1
    alist[pos] = current
```

* reverses list
* does nothing
* sorts list
* removes smallest element from alist



## Answers

3. I'm pretty sure the answer is a tree..

7. ?

9. ?

11. ?

12. ?