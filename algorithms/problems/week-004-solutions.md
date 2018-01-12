
## Problem 3:

https://leetcode.com/problems/word-frequency/description/

### Solution

```bash
cat words.txt| tr -s ' ' '\n' | sort | uniq -c | sort -r | awk '{print $2" "$1}'
```
