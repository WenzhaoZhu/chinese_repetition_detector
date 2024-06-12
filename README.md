# chinese_repetition_detector
## Updates
### June 11, 2024
- Showing the number of characters in the text, excluding whitespaces only.
- Import text from a file, not a variable anymore.

## Requirements
- re
- nltk
## Run
```
python detector.py
```
## Parameters
- **RELA_PATH**: the path to the file.
- **FILE_NAME**: the name of the file, "Chinese_detector.txt" by default.
- **len_repe**: minimum length to be counted as repetition, default=3.
- **times_repe**: minimum times of occurrence to be counted as repetition, default=3.
