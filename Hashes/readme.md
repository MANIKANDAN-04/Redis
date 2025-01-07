# Redis Hashes Example

This repository provides examples of how to use the **Hash** data type in Redis. Redis Hashes are maps between string fields and string values, making them ideal for storing objects like user profiles or configuration data.

## Features of Redis Hashes
- Store multiple fields and values under a single key.
- Perform CRUD operations on individual fields without retrieving the entire object.
- Increment or decrement numeric fields directly.

### Quick Examples
```plaintext
# Create a hash with fields
HSET user:1000 name "John Doe" age "30" email "john.doe@example.com"

# Retrieve a field
HGET user:1000 name

# Increment a field
HINCRBY user:1000 age 1
