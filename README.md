## RawShell
Custom 32 bit shellcode generator based on the OSED course with added features.

### Pre-Reqs
* python 3+
* keystone-engine
  * `pip3 install keystone-engine`

### Features
* Reverse and bind support
* Command and powershell support
* Prints the length
* Prints the SC in a format that can be used straight into python
* Supports a debug flag that sets a breakpoint at the start of your shellcode for debugging purposes

### Usage
```
py.exe .\rawshell.py -s cmd -t bind -d true
```
![image](https://github.com/user-attachments/assets/52a379b7-d96e-42cb-80d4-b78841f41082)
