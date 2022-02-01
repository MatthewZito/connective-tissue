<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [connective-tissue](./connective-tissue.md) &gt; [CircularDoublyLinkedList](./connective-tissue.circulardoublylinkedlist.md) &gt; [insertValue](./connective-tissue.circulardoublylinkedlist.insertvalue.md)

## CircularDoublyLinkedList.insertValue() method

Convenience for inserting a given value into a new node after a given node `at`

<b>Signature:</b>

```typescript
insertValue(value: T, at: INode<T, CircularDoublyLinkedList<T>> | ISentinel): INode<T, CircularDoublyLinkedList<T>>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  value | T | The value with which to instantiate the inserted node |
|  at | INode&lt;T, [CircularDoublyLinkedList](./connective-tissue.circulardoublylinkedlist.md)<!-- -->&lt;T&gt;&gt; \| ISentinel | A node in the list before which to move <code>node</code> |

<b>Returns:</b>

INode&lt;T, [CircularDoublyLinkedList](./connective-tissue.circulardoublylinkedlist.md)<!-- -->&lt;T&gt;&gt;
