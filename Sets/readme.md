# Redis Sets Example

This repository provides examples of how to use the **Set** data type in Redis. Redis Sets are unordered collections of unique strings, ideal for use cases like managing tags, unique user IDs, and performing set operations like union, intersection, and difference.

## Features of Redis Sets
- Store a collection of unique elements.
- Perform set operations such as union, intersection, and difference.
- Efficiently check membership and perform random sampling.

## Example Commands
You can find a detailed list of Redis Set commands in the [`examples/redis_sets_example.txt`](examples/redis_sets_example.txt) file.

### Quick Examples
```plaintext
# Add elements to a set
SADD myset "value1" "value2"

# Get all members of the set
SMEMBERS myset  # Returns {"value1", "value2"}

# Check if an element exists in the set
SISMEMBER myset "value1"  # Returns 1 (true)

# Get the number of elements in the set
SCARD myset  # Returns 2
