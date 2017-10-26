# Answers

Q: Why does FixedArrayQueue require an explicit constructor?

A: Because the queue needs to be initialized

Q: What happens when you offer an item to a full FixedArrayQueue?

A: The array is already full so it returns false

Q: What happens when you poll an empty FixedArrayQueue?

A: the result is null

Q:What is the time and (extra) space complexity of each of the FixedArrayQueue methods?

A:
    offer(final E obj): O(1)
    peek(): O(1)
    poll(): O(1)
    isEmpty(): O(1)
    size(): O(1)
    asList(): O(n)