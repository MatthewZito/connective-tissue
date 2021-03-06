<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [connective-tissue](./connective-tissue.md) &gt; [CircularDoublyLinkedList](./connective-tissue.circulardoublylinkedlist.md)

## CircularDoublyLinkedList class

Implements a circular doubly linked list as a ring, such that the sentinel node is both the next node of the tail, and the previous node of the head

<b>Signature:</b>

```typescript
export declare class CircularDoublyLinkedList<T> 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)()](./connective-tissue.circulardoublylinkedlist._constructor_.md) |  | Constructs a new instance of the <code>CircularDoublyLinkedList</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [sentinel](./connective-tissue.circulardoublylinkedlist.sentinel.md) |  | ISentinel | The sentinel terminator node |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [create()](./connective-tissue.circulardoublylinkedlist.create.md) | <code>static</code> | Instantiate an empty circular doubly linked list |
|  [head()](./connective-tissue.circulardoublylinkedlist.head.md) |  | Returns the head node of the list or null if the list is empty |
|  [insert(node, at)](./connective-tissue.circulardoublylinkedlist.insert.md) |  | Insert a new node after a given node <code>at</code> |
|  [insertAfter(value, mark)](./connective-tissue.circulardoublylinkedlist.insertafter.md) |  | Insert a new node with value <code>value</code> immediately after <code>mark</code>. If <code>mark</code> is not an element of the list, the list is not modified. <code>mark</code> must not be null. |
|  [insertBefore(value, mark)](./connective-tissue.circulardoublylinkedlist.insertbefore.md) |  | Insert a new node with value <code>value</code> immediately before <code>mark</code>. If <code>mark</code> is not an element of the list, the list is not modified. <code>mark</code> must not be null. |
|  [insertValue(value, at)](./connective-tissue.circulardoublylinkedlist.insertvalue.md) |  | Convenience for inserting a given value into a new node after a given node <code>at</code> |
|  [move(node, at)](./connective-tissue.circulardoublylinkedlist.move.md) |  | Move given node to <code>at</code> |
|  [moveAfter(node, mark)](./connective-tissue.circulardoublylinkedlist.moveafter.md) |  | Move a given node to its new position after <code>mark</code>. If either the given node or mark are not an element of the list, or node == mark, the list is not modified. Both the node and mark must not be null. |
|  [moveBefore(node, mark)](./connective-tissue.circulardoublylinkedlist.movebefore.md) |  | Move a given node to its new position before <code>mark</code>. If either the given node or mark are not an element of the list, or node == mark, the list is not modified. Both the node and mark must not be null (return value will be null) |
|  [moveToBack(node)](./connective-tissue.circulardoublylinkedlist.movetoback.md) |  | Move a node to the back of the list If the given node is not an element of the list, the list is not modified The given node must not be null |
|  [moveToFront(node)](./connective-tissue.circulardoublylinkedlist.movetofront.md) |  | Move a node to the front of the list. If the given node is not an element of the list, the list is not modified. The given node must not be null. |
|  [next(node)](./connective-tissue.circulardoublylinkedlist.next.md) |  | Returns the next list node, if extant; else, null |
|  [pop()](./connective-tissue.circulardoublylinkedlist.pop.md) |  | Remove the last node from the list |
|  [prev(node)](./connective-tissue.circulardoublylinkedlist.prev.md) |  | Returns the previous list node, if extant; else, null |
|  [pushBack(value)](./connective-tissue.circulardoublylinkedlist.pushback.md) |  | Push a new node with value <code>value</code> to the back of the list |
|  [pushBackList(other)](./connective-tissue.circulardoublylinkedlist.pushbacklist.md) |  | Insert a copy of another list at the back of the caller list. The lists may be equivalent, but must not be null. |
|  [pushFront(value)](./connective-tissue.circulardoublylinkedlist.pushfront.md) |  | Push a new node with value <code>value</code> to the front of the list |
|  [pushFrontList(other)](./connective-tissue.circulardoublylinkedlist.pushfrontlist.md) |  | Insert a copy of another list at the front of the caller list. The lists may be the same, but must not be null. |
|  [remove(node)](./connective-tissue.circulardoublylinkedlist.remove.md) |  | Remove a given node from the list |
|  [size()](./connective-tissue.circulardoublylinkedlist.size.md) |  | The current size of the list, sans the sentinel node |
|  [tail()](./connective-tissue.circulardoublylinkedlist.tail.md) |  | Returns the tail node of the list or null if the list is empty |

