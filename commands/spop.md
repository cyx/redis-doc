@complexity

O(1)


Removes and returns a random element from the set value stored at `key`.

This operation is similar to `SRANDMEMBER`, that returns a random
element from a set but does not remove it.

@return

@bulk-reply: the removed element, or `nil` when `key` does not exist.

