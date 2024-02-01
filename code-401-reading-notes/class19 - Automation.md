# Class 19 - Automation

## [Python Regular Expressions](https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security/xcae6f4a7ff015e7d:data-encryption-techniques/a/encryption-decryption-and-code-cracking)

- Regex is a sequence of characters used to check if a pattern exisits in a given string
- Import the regex modules by using the script ```import re```
- ChatGPT is useful here by telling it to convert the sequence of characters into regex

## [shutil](https://pymotw.com/3/shutil/)

- Provides operations like copying and archiving files on an operating system
- Import the shutil module by using the script ```import shutil```
- Useful for large scale operations to directory trees and preserves metadata

## [os](https://pymotw.com/3/os/)

- Provides operations with the system's operating system
- Import the os module by using the script ```import os```
- Can also manage system files but not at a large scale like shutil

## Additional Resources

[Automation Ideas](https://www.youtube.com/watch?v=qbW6FRbaSl0&t=69s)

[Automating Your Browser and Desktop Apps](https://www.youtube.com/watch?v=dZLyfbSQPXI)

[Watchdog](https://pythonhosted.org/watchdog/)

### Questions

1. How can you use regular expressions in Python to search for specific patterns in a string, and what is the primary module to work with them?

- Regex checks for a sequeunce of specified characters and you can use their built in functions to execute additional actions based on the prescense of those specified characters.
- The primary module is the regex module and is imported using ```import re```

2. What is the purpose of the shutil module in Python, and provide an example of a common use case for file or directory management with this module?

- It provides operations like copying and archiving files on an operating system. A use case is making a duplicate of your files for a backup

3. Compare and contrast the os and shutil modules. When would you choose to use one over the other? 

- os modules enables interaction with the operating system and while it can also manage system files, it's not recommended to manage large system files spanning directory trees. The shutil module will also preserve the files metadata

## Things I want to know more about

- How do you combine the shutil and os modules to develop an automated operation that regularly empties your recycle bin or removes aged data to clear up system storage?