# Hash-Tables

<h2>Overview</h2>
<p>
    The Hash Table Project is a comprehensive implementation of a hash table data structure in Python. It provides 
    an in-depth understanding of hash tables, including collision handling, dynamic resizing, and key-value operations.
    The project also includes an application for plagiarism detection in songs, showcasing the practicality of hash tables.
</p>

<h2>Features</h2>
<ul>
    <li><strong>Custom Hash Table Implementation</strong>: A fully featured `HashTable` class.</li>
    <li><strong>Collision Handling</strong>: Efficiently manages collisions using double hashing.</li>
    <li><strong>Dynamic Resizing</strong>: Automatically resizes for optimal performance.</li>
    <li><strong>Key-Value Storage</strong>: Stores and manages key-value pairs.</li>
    <li><strong>Basic Operations</strong>: Supports insertion, deletion, and retrieval.</li>
    <li><strong>Additional Utilities</strong>: Methods for clearing, and retrieving keys, values, and items.</li>
    <li><strong>Plagiarism Detection</strong>: Application to detect similarities in melodies between songs.</li>
</ul>

<h2>Usage</h2>
<p>
    Import the `HashTable` class from the project's Python file. Create an instance and use its methods for various operations.
</p>
<code>
    from solution import HashTable<br>
    <br>
    # Create a hash table<br>
    hash_table = HashTable()<br>
    <br>
    # Insert key-value pairs<br>
    hash_table["key1"] = "value1"<br>
    hash_table["key2"] = "value2"<br>
    <br>
    # Retrieve a value<br>
    value = hash_table["key1"]<br>
    <br>
    # Delete a key<br>
    del hash_table["key2"]<br>
    <br>
    # Check for key existence<br>
    if "key1" in hash_table:<br>
        print("Key1 exists in the hash table")<br>
    <br>
    # Get all keys<br>
    keys = hash_table.keys()<br>
    <br>
    # Clear the hash table<br>
    hash_table.clear()<br>
</code>

<h2>Plagiarism Detection Application</h2>
<p>
    To use the plagiarism detection feature, provide two lists of melodies (each melody represented as a list of integers) and a maximum similarity threshold. The function is_plagiarism will return True if the number of similar melodies exceeds the threshold.

</p>

<h2>Requirements</h2>
<ul>
    <li>Python 3.x</li>
</ul>


</body>
</html>
