<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [connective-tissue](./connective-tissue.md) &gt; [SinglyLinkedList](./connective-tissue.singlylinkedlist.md)

## SinglyLinkedList class

Implements a singly linked list. Optionally pass a type to define the shape of node data i.e. node member `value`<!-- -->.

<b>Signature:</b>

```typescript
export declare class SinglyLinkedList<T> 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)()](./connective-tissue.singlylinkedlist._constructor_.md) |  | Constructs a new instance of the <code>SinglyLinkedList</code> class |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [head](./connective-tissue.singlylinkedlist.head.md) |  | IForwardNode&lt;T, [SinglyLinkedList](./connective-tissue.singlylinkedlist.md)<!-- -->&lt;T&gt;&gt; \| null | The head node. The head is initialized to null; you must insert a node to initially populate the list. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [create()](./connective-tissue.singlylinkedlist.create.md) | <code>static</code> | Instantiate an 'uninitialized' singly linked list |
|  [insertAfter(value, mark)](./connective-tissue.singlylinkedlist.insertafter.md) |  | Insert a new node with value <code>value</code> immediately after <code>mark</code>. If <code>mark</code> is not an element of the list, the list is not modified. <code>mark</code> must not be null. |
|  [next(node)](./connective-tissue.singlylinkedlist.next.md) |  | Returns the next node from that given, if extant; else, null |
|  [pop()](./connective-tissue.singlylinkedlist.pop.md) |  | Remove the last node from the list |
|  [pushBack(value)](./connective-tissue.singlylinkedlist.pushback.md) |  | Push a new node with value <code>value</code> to the back of the list |
|  [pushFront(value)](./connective-tissue.singlylinkedlist.pushfront.md) |  | Push a new node with value <code>value</code> to the front of the list |
|  [remove(node)](./connective-tissue.singlylinkedlist.remove.md) |  | Remove a given node from the list |
|  [removeHead()](./connective-tissue.singlylinkedlist.removehead.md) |  | Excise the head of the list and return it; if the head is not extant, return null |
|  [size()](./connective-tissue.singlylinkedlist.size.md) |  | The current size of the list. This property does not account for a quasi-uninitialized head node. |

