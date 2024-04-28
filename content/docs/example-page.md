---
weight: 999
title: "Multiple methods of greeting"
description: "Using Python we print Hello World using a lot of different methods"
icon: "article"
date: "2024-04-28T19:25:27+02:00"
lastmod: "2024-04-28T19:25:27+02:00"
draft: true
toc: true
author: "Apa"
tags: ["Beginners"]
---
## Hello World in Python
Print the expression "Hello world" by various methods.

### Method 1
```python
print("Hello world")
```

### Method 2
```python
print('Hello' + 'world')
```

### Method 3
```python
print('Hello' + 'world')
```

### Method 4
```python
print('Hello', 'world')
```

### Method 5
```python
print('{} {}'.format('Hello','world'))
```

### Method 6
```python
word1 = 'Hello'
word2 = 'World¡
print(f'{word1} {word2})
```

### Method 7
```python
a = "!dlrow olleH"
b = a[::-1]
print(b)
```

### Method 8
```python
str = "!dlrow olleH"
print(''.join(reversed(str)))
```

### Method 9
```python
def greeting():
    print("Hello world!")

if __name__ == "__main__":
    greeting()
```

### Method 10
```python
while True: print('Hello world'); break
```
