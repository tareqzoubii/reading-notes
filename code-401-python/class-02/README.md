## Read2:
# -----------------
### For Link 1: this article it talks about the TDS, what is TDS? TDS isTest-Driven Development  so as they say its a strategy to write and think, and how to write it like test file name should follow the same name of module name as shown below code
> mymodule/ — module.py — another_folder/ — — another_module.pytests/ — test_module.py — another_folder/ — — test_another_module.py

### For Link 2: it talks about the advantages of __name__ == "__main__" ---> 
### Advantages : 

### Every Python module has it’s __name__ defined and if this is ‘__main__’, it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
### If you import this script as a module in another script, the __name__ is set to the name of the script/module.
### Python files can act as either reusable modules, or as standalone programs.
### if __name__ == “main”: is used to execute some code only if the file was run directly, and not imported.

### For Link 3: this article is talks about the recusrsion and why we need it ? recursion is the process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called a recursive function, the properties of recrusion 

### Performing the same operations multiple times with different inputs.
### In every step, we try smaller inputs to make the problem smaller.
### Base condition is needed to stop the recursion otherwise infinite loop will occur

### For Link 4: Some methods in this article
### ist.append(elem) -- adds a single element to the end of the list. Common error: does not return the new list, just modifies the original.
### list.insert(index, elem) -- inserts the element at the given index, shifting elements to the right.
### list.extend(list2) adds the elements in list2 to the end of the list. Using + or += on a list is similar to using extend().
### list.index(elem) -- searches for the given element from the start of the list and returns its index. Throws a ValueError if the element does not appear (use "in" to check without a ValueError).
### list.remove(elem) -- searches for the first instance of the given element and removes it (throws ValueError if not present)
### list.sort() -- sorts the list in place (does not return it). (The sorted() function shown later is preferred.)
### list.reverse() -- reverses the list in place (does not return it)
### list.pop(index) -- removes and returns the element at the given index. Returns the rightmost element if index is omitted (roughly the opposite of append()).

### For Link 5: This article talks about the method used in strings to make it uper and lower and s.lower(), s.upper() -- returns the lowercase or uppercase version of the string
### s.strip() -- returns a string with whitespace removed from the start and end
### s.isalpha()/s.isdigit()/s.isspace()... -- tests if all the string chars are in the various character classes
### s.startswith('other'), s.endswith('other') -- tests if the string starts or ends with the given other string
### s.find('other') -- searches for the given other string (not a regular expression) within s, and returns the first index where it begins or -1 if not found
### s.replace('old', 'new') -- returns a string where all occurrences of 'old' have been replaced by 'new'
### s.split('delim') -- returns a list of substrings separated by the given delimiter. The delimiter is not a regular expression, it's just text. 'aaa,bbb,ccc'.split(',') -> ['aaa', 'bbb', 'ccc']. As a convenient special case s.split() (with no arguments) splits on all whitespace chars.
### s.join(list)