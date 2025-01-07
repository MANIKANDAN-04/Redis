# Redis Strings Examples

# 1. Set a key-value pair
SET key "value"

# 2. Get the value of a key
GET key

# 3. Increment a numeric string value
SET counter 10
INCR counter  # counter becomes 11
INCRBY counter 5  # counter becomes 16

# 4. Decrement a numeric string value
DECR counter  # counter becomes 15
DECRBY counter 3  # counter becomes 12

# 5. Append to a string
SET mykey "Hello"
APPEND mykey " World"  # mykey becomes "Hello World"

# 6. Get the length of a string
STRLEN mykey  # Returns 11

# 7. Set key with expiration (in seconds)
SET key_with_expiry "temporary value" EX 10  # Expires in 10 seconds
