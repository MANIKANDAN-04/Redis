# Redis Strings Example

This repository provides examples of how to use the **String** data type in Redis. Strings are the most basic and versatile data type in Redis, allowing you to store and retrieve text or binary data.

## Features of Redis Strings
- Store any type of text or binary data up to 512 MB per key.
- Perform operations like increment, decrement, append, and string length retrieval.
- Set expiration times on keys for temporary storage.

### Quick Examples
```plaintext
# Set and Get a key-value pair
SET mykey "Hello, Redis!"
GET mykey

# Increment a numeric value
SET counter 100
INCR counter
