<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [connective-tissue](./connective-tissue.md) &gt; [CircularDoublyLinkedList](./connective-tissue.circulardoublylinkedlist.md) &gt; [prev](./connective-tissue.circulardoublylinkedlist.prev.md)

## CircularDoublyLinkedList.prev() method

Returns the previous list node, if extant; else, null

<b>Signature:</b>

```typescript
prev(node: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>> | null;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  node | INode&lt;T, [CircularDoublyLinkedList](./connective-tissue.circulardoublylinkedlist.md)<!-- -->&lt;T&gt;&gt; | A valid node, which must be a member of this list (return null if the given node is not a member). If this constraint is satisfied, return the previous node relative to the given node. |

<b>Returns:</b>

INode&lt;T, [CircularDoublyLinkedList](./connective-tissue.circulardoublylinkedlist.md)<!-- -->&lt;T&gt;&gt; \| null

