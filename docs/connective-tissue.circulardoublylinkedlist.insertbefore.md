<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [connective-tissue](./connective-tissue.md) &gt; [CircularDoublyLinkedList](./connective-tissue.circulardoublylinkedlist.md) &gt; [insertBefore](./connective-tissue.circulardoublylinkedlist.insertbefore.md)

## CircularDoublyLinkedList.insertBefore() method

Insert a new node with value `value` immediately before `mark`

If `mark` is not an element of the list, the list is not modified

`mark` must not be null

<b>Signature:</b>

```typescript
insertBefore(value: T, mark: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>> | null;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  value | T |  |
|  mark | INode&lt;T, CircularDoublyLinkedList&lt;T&gt;&gt; |  |

<b>Returns:</b>

INode&lt;T, CircularDoublyLinkedList&lt;T&gt;&gt; \| null
