<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [connective-tissue](./connective-tissue.md) &gt; [CircularSinglyLinkedList](./connective-tissue.circularsinglylinkedlist.md) &gt; [insertBefore](./connective-tissue.circularsinglylinkedlist.insertbefore.md)

## CircularSinglyLinkedList.insertBefore() method

Insert a new node with value `value` immediately before `mark`<!-- -->. If `mark` is not an element of the list, the list is not modified. `mark` must not be null.

<b>Signature:</b>

```typescript
insertBefore(value: T, mark?: IForwardNode<T, CircularSinglyLinkedList<T>>): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  value | T | The value with which to instantiate the inserted node |
|  mark | IForwardNode&lt;T, [CircularSinglyLinkedList](./connective-tissue.circularsinglylinkedlist.md)<!-- -->&lt;T&gt;&gt; | A node in the list before which to insert the new node |

<b>Returns:</b>

IForwardNode&lt;T, [CircularSinglyLinkedList](./connective-tissue.circularsinglylinkedlist.md)<!-- -->&lt;T&gt;&gt; \| null
