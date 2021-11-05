# Solving The Lockbox Problem

## Task

### Lockboxes - [canUnlockAll](https://github.com/AnthonyArmour/holbertonschool-interview/blob/main/0x00-lockboxes/0-lockboxes.py "canUnlockAll")

You have n number of locked boxes in front of you. Each box is numbered sequentially from 0 to n - 1 and each box may contain keys to the other boxes. Write a method that determines if all the boxes can be opened.

```python
#!/usr/bin/python3

canUnlockAll = __import__('0-lockboxes').canUnlockAll

boxes = [[1], [2], [3], [4], []]
print(canUnlockAll(boxes))

boxes = [[1, 4, 6], [2], [0, 4, 1], [5, 6, 2], [3], [4, 1], [6]]
print(canUnlockAll(boxes))

boxes = [[1, 4], [2], [0, 4, 1], [3], [], [4, 1], [5, 6]]
print(canUnlockAll(boxes))
```

> True

> True

> False
