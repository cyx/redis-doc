@complexity

O(1)


Renames `key` to `newkey` if `newkey` does not yet exist.
It returns an error under the same conditions as `RENAME`.

@return

@integer-reply, specifically:

* `1` if `key` was renamed to `newkey`.
* `0` if `newkey` already exists.

