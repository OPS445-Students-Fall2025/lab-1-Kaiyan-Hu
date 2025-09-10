# OPS445 - Lab1 Analysis (Investigation 2 - Task 4)

## 1. Script Structure in sample.py
-Shebang line: '#!/usr/bin/env python3'
-Script level docstring: triple quotes at the beginning
-Import section: 'import os, sys'
-Function definition section: functions that create directories and handle errors
-Main script section: code under 'if _name_ == "_main_":'

## 2. Python Features in sample.py
-Python keywords: if, else, for, try, except, def, import, return
-Decision code segment: 'if/else' blocks
-Looping code segment: 'for' loop creating directories
-Error handling: 'try/except' for directory creation

## 3. Script Execution Results
-'python3 sample.py' → Directories already exist → skipped
-'python3 sample.py test' → Directories not created → errors
-'python3 sample.py 2>/dev/null' → only summary shown, error message hidden
-'python3 sample.py test 2>/dev/null' → summary shown with errors, details hidden
 
