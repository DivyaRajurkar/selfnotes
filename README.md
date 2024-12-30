# selfnotes
### **Short Notes on Python Strings**

1. **String Definition**: Strings are surrounded by single (`'`) or double (`"`) quotes.  
   Example:  
   ```python
   print("Hello")
   print('Hello')
   ```

2. **Quotes Inside Strings**: Use different quotes inside a string to include quotes.  
   Example:  
   ```python
   print("It's alright")
   print('He is called "Johnny"')
   ```

3. **Assign String to a Variable**: Use `=` to assign strings to variables.  
   Example:  
   ```python
   a = "Hello"
   print(a)
   ```

4. **Multiline Strings**: Use triple quotes (`'''` or `"""`) for multiline strings.  
   Example:  
   ```python
   a = """This is
   a multiline
   string."""
   print(a)
   ```

5. **Strings as Arrays**: Strings are arrays; access elements using indices.  
   Example:  
   ```python
   a = "Hello"
   print(a[1])  # Output: e
   ```

6. **Looping Through Strings**: Use a `for` loop to iterate through characters.  
   Example:  
   ```python
   for x in "banana":
       print(x)
   ```

7. **String Length**: Use `len()` to find the string's length.  
   Example:  
   ```python
   a = "Hello"
   print(len(a))  # Output: 5
   ```

8. **Check Substring Presence**: Use the `in` keyword.  
   Example:  
   ```python
   txt = "The best things in life are free!"
   print("free" in txt)  # Output: True
   ```

9. **Check Substring Absence**: Use `not in` keyword.  
   Example:  
   ```python
   txt = "The best things in life are free!"
   print("expensive" not in txt)  # Output: True
   ``` 

10. **Conditional Substring Checks**: Combine `in` or `not in` with `if` statements.  
    Example:  
    ```python
    if "free" in txt:
        print("Yes, 'free' is present.")
    if "expensive" not in txt:
        print("No, 'expensive' is NOT present.")
    ```
    ### **Short Notes on Python String Slicing**

1. **String Slicing**: Extract a portion of a string using `string[start:end]`.  
   Example:  
   ```python
   b = "Hello, World!"
   print(b[2:])  # Output: "llo, World!" (from index 2 to the end)
   ```

2. **Negative Indexing**: Use negative indices to slice from the end of the string.  
   Example:  
   ```python
   b = "Hello, World!"
   print(b[-5:-2])  # Output: "orl" (from index -5 to -2, excluding -2)
   ```
