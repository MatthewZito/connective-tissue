## API Report File for "connective-tissue"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

// @public
export class CircularDoublyLinkedList<T> {
    constructor();
    static create(): CircularDoublyLinkedList<unknown>;
    head(): INode<T, CircularDoublyLinkedList<T>> | null;
    insert(node: INode<T, CircularDoublyLinkedList<T>>, at: INode<T, CircularDoublyLinkedList<T>> | ISentinel): INode<T, CircularDoublyLinkedList<T>>;
    insertAfter(value: T, mark: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>> | null;
    insertBefore(value: T, mark: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>> | null;
    insertValue(value: T, at: INode<T, CircularDoublyLinkedList<T>> | ISentinel): INode<T, CircularDoublyLinkedList<T>>;
    move(node: INode<T, CircularDoublyLinkedList<T>>, at: INode<T, CircularDoublyLinkedList<T>> | ISentinel): INode<T, CircularDoublyLinkedList<T>> | null;
    moveAfter(node: INode<T, CircularDoublyLinkedList<T>>, mark: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>> | null;
    moveBefore(node: INode<T, CircularDoublyLinkedList<T>>, mark: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>> | null;
    moveToBack(node: INode<T, CircularDoublyLinkedList<T>>): void;
    moveToFront(node: INode<T, CircularDoublyLinkedList<T>>): void;
    // Warning: (ae-forgotten-export) The symbol "INode" needs to be exported by the entry point index.d.ts
    next(node: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>> | null;
    pop(): INode<T, CircularDoublyLinkedList<T>> | null;
    prev(node: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>> | null;
    pushBack(value: T): INode<T, CircularDoublyLinkedList<T>>;
    pushBackList(other: this): void;
    pushFront(value: T): INode<T, CircularDoublyLinkedList<T>>;
    pushFrontList(other: this): void;
    remove(node: INode<T, CircularDoublyLinkedList<T>>): INode<T, CircularDoublyLinkedList<T>>;
    // Warning: (ae-forgotten-export) The symbol "ISentinel" needs to be exported by the entry point index.d.ts
    sentinel: ISentinel;
    size(): number;
    tail(): INode<T, CircularDoublyLinkedList<T>> | null;
}

// @public
export class CircularSinglyLinkedList<T> {
    constructor();
    static create(): CircularSinglyLinkedList<unknown>;
    // Warning: (ae-forgotten-export) The symbol "IForwardNode" needs to be exported by the entry point index.d.ts
    head: IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    insertAfter(value: T, mark: IForwardNode<T, CircularSinglyLinkedList<T>>): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    insertBefore(value: T, mark?: IForwardNode<T, CircularSinglyLinkedList<T>>): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    moveAfter(node: IForwardNode<T, CircularSinglyLinkedList<T>>, mark: IForwardNode<T, CircularSinglyLinkedList<T>>): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    moveBefore(node: IForwardNode<T, CircularSinglyLinkedList<T>>, mark: IForwardNode<T, CircularSinglyLinkedList<T>>): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    next(node: IForwardNode<T, CircularSinglyLinkedList<T>>): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    pop(): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    prev(node: IForwardNode<T, CircularSinglyLinkedList<T>>): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    pushBack(value: T): IForwardNode<T, CircularSinglyLinkedList<T>>;
    pushBackList(other: this): void;
    pushFront(value: T): IForwardNode<T, CircularSinglyLinkedList<T>>;
    pushFrontList(other: this): void;
    remove(node: IForwardNode<T, CircularSinglyLinkedList<T>>): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    removeHead(): IForwardNode<T, CircularSinglyLinkedList<T>> | null;
    size(): number;
}

// @public
export function ForwardNode<D, L>(value: D): IForwardNode<D, L>;

// @public
export function Node<D, L>(value: D): INode<D, L>;

// @public
export function Sentinel(): ISentinel;

// @public
export class SinglyLinkedList<T> {
    constructor();
    static create(): SinglyLinkedList<unknown>;
    head: IForwardNode<T, SinglyLinkedList<T>> | null;
    insertAfter(value: T, mark: IForwardNode<T, SinglyLinkedList<T>>): IForwardNode<T, SinglyLinkedList<T>> | null;
    next(node?: IForwardNode<T, SinglyLinkedList<T>> | null): IForwardNode<T, SinglyLinkedList<T>> | null;
    pop(): IForwardNode<T, SinglyLinkedList<T>> | null;
    pushBack(value: T): IForwardNode<T, SinglyLinkedList<T>>;
    pushFront(value: T): IForwardNode<T, SinglyLinkedList<T>>;
    remove(node: IForwardNode<T, SinglyLinkedList<T>>): IForwardNode<T, SinglyLinkedList<T>> | null;
    removeHead(): IForwardNode<T, SinglyLinkedList<T>> | null;
    size(): number;
}

// (No @packageDocumentation comment for this package)

```
