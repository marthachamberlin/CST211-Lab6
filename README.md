# CST211-Lab6
Queue – Linked List Implementation
Description
Develop a Queue class based on a List (from Lab 2).
UML Class Diagram

template:T

Queue

private:
* m_queue: List
* m_size: int

public:
* Enqueue (in data:T): void
* Dequeue (): T
* <<const>> Peek(): T
* <<const>> getSize(): void
* <<const>> isEmpty(): bool

Stipulations
* Throw Underflow exceptions using your Exception class where appropriate.
* Although not shown in the UML class diagram, include the appropriate manager functions. (Be sure to have the correct ones! ☺)
* Selected function explanations:
** Peek – Return the data at the head/front of the queue.

Deliverables
One file including:
* Your code
* Your test(s) similar to Lab1_test.cpp & Lab2_test.cpp and their results

