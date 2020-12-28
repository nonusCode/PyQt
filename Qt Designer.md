# Qt Designer



### UI 파일 불러오기

```python
import sys
from PyQt5.QtWidgets import *
from PyQt5 import uic

# 경로 지정
변수명 = '경로'

class MainDialog(QDialog):
    def __init__(self):
        QDialog.__init__(self, None)
        uic.loadUi(변수명, self)
        
app = QApplication(sys.argv)
main_dialog = MainDialog()
main_dialog.show()
app.exec_()
```

