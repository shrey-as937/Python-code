# Python-code
print('Hello World')
x = 10
y = 20
print(x+y)




# Sample string for demonstration
text = "  Hello, World! This is a Python string example. "

print(f"Original String: '{text}'\n")

# --- Case Modification Methods ---
print("--- Case Modification ---")
print(f"* upper(): {text.upper()}") # Converts to uppercase
print(f"* lower(): {text.lower()}") # Converts to lowercase
print(f"* capitalize(): {text.capitalize()}") # Capitalizes first character
print(f"* title(): {text.title()}") # Capitalizes the first character of each word
print(f"* swapcase(): {text.swapcase()}") # Swaps case of all characters
print(f"* casefold(): {text.casefold()}") # Converts to a casefolded version for caseless matching

# --- Trimming and Alignment Methods ---
print("\n--- Trimming and Alignment ---")
print(f"* strip(): '{text.strip()}'") # Removes leading/trailing whitespace
print(f"* lstrip(): '{text.lstrip()}'") # Removes leading whitespace
print(f"* rstrip(): '{text.rstrip()}'") # Removes trailing whitespace
print(f"* center(50, '-'): '{text.strip().center(50, '-')}'") # Centers string with padding
print(f"* ljust(50): '{text.strip().ljust(50, '.')}'") # Left-justifies string with padding
print(f"* rjust(50): '{text.strip().rjust(50, '.')}'") # Right-justifies string with padding
print(f"* zfill(60): '{text.strip().zfill(60)}'") # Pads with zeros on the left

# --- Searching and Finding Methods ---
print("\n--- Searching and Finding ---")
print(f"* count('o'): {text.count('o')}") # Counts occurrences of a substring
print(f"* find('Python'): {text.find('Python')}") # Finds first occurrence, returns index or -1
print(f"* index('string'): {text.index('string')}") # Finds first occurrence, raises error if not found
print(f"* startswith('  Hello'): {text.startswith('  Hello')}") # Checks if string starts with prefix
print(f"* endswith(' '): {text.endswith(' ')}") # Checks if string ends with suffix

# --- Modification Methods ---
print("\n--- Modification ---")
print(f"* replace('World', 'Pythonista'): {text.replace('World', 'Pythonista')}") # Replaces occurrences of a substring
print(f"* removeprefix('  Hello,'): '{text.removeprefix('  Hello,')}'") # Removes prefix if present
print(f"* removesuffix(' '): '{text.removesuffix(' ')}'") # Removes suffix if present
print(f"* split(): {text.split()}") # Splits string by whitespace into a list
print(f"* join(['a', 'b', 'c']): {'-'.join(['a', 'b', 'c'])}") # Joins elements of an iterable
print(f"* partition('Python'): {text.partition('Python')}") # Splits into a tuple of (before, sep, after)

# --- Status Checking Methods (return True/False) ---
print("\n--- Status Checking ---")
print(f"* isalnum() (on 'Python3'): {'Python3'.isalnum()}") # Checks if all chars are alphanumeric
print(f"* isalpha() (on 'Python'): {'Python'.isalpha()}") # Checks if all chars are alphabetic
print(f"* isdigit() (on '123'): {'123'.isdigit()}") # Checks if all chars are digits
print(f"* isspace() (on ' '): {' '.isspace()}") # Checks if all chars are whitespace
print(f"* istitle() (on 'Hello World'): {'Hello World'.istitle()}") # Checks if string is in title case

# --- Formatting Methods ---
print("\n--- Formatting ---")
name = "Alice"
age = 30
print(f"* format() example: 'My name is {} and I am {} years old.'.format(name, age)")
print(f"* f-string example: f'My name is {name} and I am {age} years old.'")

