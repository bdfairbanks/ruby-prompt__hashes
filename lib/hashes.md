---
title: Hashes
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a Hash?

A Hash is a collection of keys and their values. 

# What are some examples of information that would be Hashes as opposed to some other data type?

Hashes contain two part bits of data, where most other data types do not. A hash is {name => data},  where as integers and floats are data, strings are "data", arrays are any 
combination of data, "data" and [data] within [] brackets.

# How are Hashes and Arrays similar? How are they different?

Arrays and hashes are both collections of objects. Tha main difference seems to be that while Arrays are ordered lists (objects are tagged 0,1,2... from the left and -1,-2-3 from the back)
Hashes are collections of key/value pairs, so the indexing is done via the keys.  The Array is more of a bag that holds things where the Hash is more of a reference table. 

# How do you retrieve a particular value from a Hash?

to retrieve a perticular value in a Hash you would reference the hash name then the key associated with the value you wished for.  hash['key']

# How do you add information to a Hash?

To add information to a hash you would use hash['key'] = "information"

# How would you perform an operation on every element inside a Hash?

.each seems to be the way that you access every element within the hash, which can be specified to wether you want keys, values or both.

# How would you change the value of a particular element in a Hash?

Changing the value is relatively easy, its simply hash("element") = new_value

# How do you delete an element from a Hash?

hash.delete("element") seems to do the trick

# What happens if you try to retrieve an element from a Hash that does not exist in the Hash?

It returns a nil value, which can be assigned as a different response if you have the need or simply feel fancy.

# How do you determine how many elements are in a Hash?

hash.length will tell you how many elements there are in a hash.