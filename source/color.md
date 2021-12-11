
============

### 颜色转换

### 十六进制转RGB

```python
from zhenzi.color import hex2rgb

if __name__ == '__main__':
    print(hex2rgb('#eeeeee'))  # (238, 238, 238)
    print(hex2rgb('eeeeee'))  # (238, 238, 238)
```

### 十六进制转RGBA

```python
from zhenzi.color import hex2rgba

if __name__ == '__main__':
    print(hex2rgba('#eeeeee'))  # (238, 238, 238, 1)
    print(hex2rgba('eefff3a8'))  # ((238, 255, 243, 10.54)
```

### RGB转HSL

```python
from zhenzi.color import rgb2hsl

if __name__ == '__main__':
    print(rgb2hsl(r=255, g=255, b=0))  # (60, 100.0, 50.0)
    print(rgb2hsl(r=255, g=0, b=0))  # (0, 100.0, 50.0)
```

### 十进制转十六进制

```python
from zhenzi.color import ten2hex

if __name__ == '__main__':
    print(ten2hex(16711680))  # #ff0000
```

### 十进制转RGB

```python
from zhenzi.color import ten2rgb

if __name__ == '__main__':
    print(ten2rgb(16711680))  # (255, 0, 0)
```

### 十进制转RGBA

```python
from zhenzi.color import ten2rgba

if __name__ == '__main__':
    print(ten2rgba(16711680))  # (255, 0, 0, 1)
```

### 十进制转HSL

```python
from zhenzi.color import hex2hsl

if __name__ == '__main__':
    print(hex2hsl("#eeeeee"))  # (0, 0.0, 93.3)
```

