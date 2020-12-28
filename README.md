# PyQt



### 설치

```shell
$ pip install pyqt5
# pyside2 설치 시 Qt Desiner 자동 설치
$ pip install pyside2
```



### 다크모드

```shell
$ pip install qdarkstyle
```



```python
from qdarkstyle import *

# app 바로 밑
app.setStyleSheet(load_stylesheet())
```
