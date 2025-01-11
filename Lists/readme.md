# Redis Lists Example

This repository provides examples of how to use the **List** data type in Redis. Redis Lists are ordered collections of strings, ideal for implementing queues, stacks, or ordered data storage.

## Features of Redis Lists
- Store an ordered collection of strings.
- Perform operations like push/pop from either side (left or right).
- Efficiently manage lists with varying sizes, from small queues to large logs.

### Quick Examples
```plaintext
# Create a list and push items to it
LPUSH mylist "value1" "value2"

# Get the length of the list
LLEN mylist  # Returns 2

# Pop an element from the right of the list
RPOP mylist  # Removes "value2" and returns it
