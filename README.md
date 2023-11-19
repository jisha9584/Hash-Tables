# Hash-Tables

**Overview**
<br>
The Hash Table Project is a comprehensive implementation of a hash table data structure in Python. It is designed to provide a deep understanding of how hash tables work, including handling of collisions, resizing, and various operations like insertion, deletion, and retrieval. The project also includes a real-world application to detect song plagiarism based on melody similarity, showcasing the practical use of hash tables.

<br>

**Features**
<br>
1. Custom Hash Table Implementation: A HashTable class with standard hash table functionalities.
2. Collision Handling: Implements double hashing to efficiently handle collisions.
3. Dynamic Resizing: Automatic resizing of the hash table to maintain optimal load factors.
4. Key-Value Storage: Supports storing and managing key-value pairs.
5. Basic Operations: Includes methods for insertion (__setitem__), deletion (__delitem__), and retrieval (__getitem__).
6. Additional Utilities: Methods for clearing the table (clear), retrieving keys (keys), values (values), and items (items).
7. Plagiarism Detection: An application to detect similarity in melodies between songs, demonstrating a practical use case of hash tables.

<br>

**Usage**
<br>
To use the hash table, import the HashTable class from the project's Python file. You can then create an instance of the hash table and use its methods to perform various operations.
<br>
**Example:**
<br>

from solution import HashTable

# Create a hash table
hash_table = HashTable()

# Insert key-value pairs
hash_table["key1"] = "value1"
hash_table["key2"] = "value2"

# Retrieve a value
value = hash_table["key1"]

# Delete a key
del hash_table["key2"]

# Check if a key exists
if "key1" in hash_table:
    print("Key1 exists in the hash table")

# Get all keys
keys = hash_table.keys()

# Clear the hash table
hash_table.clear()

<br>

**Plagiarism Detection Application**
<br>
To use the plagiarism detection feature, provide two lists of melodies (each melody represented as a list of integers) and a maximum similarity threshold. The function is_plagiarism will return True if the number of similar melodies exceeds the threshold.

<br>

**Requirements**
<br>
Python 3.x
